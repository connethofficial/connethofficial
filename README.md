Conneth
Connecting people in a decentralized way
Project Overview
Conneth is a decentralized connectivity platform combining cloud computing, VPN, mesh Hotspots, and social journaling into one blockchain-powered ecosystem. It follows the DePIN (Decentralized Physical Infrastructure Network) model, where networks of people and hardware use token incentives and blockchain to build real-world infrastructure
phantom.com
. By pooling user resources instead of relying on centralized servers, Conneth offers resilient services: for example, our Conneth Cloud enables peer-to-peer storage and compute services (much like Storj or Sia) across user nodes
fierce-network.com
. The platform also features a community-driven VPN, user-operated WiFi/IoT Hotspots, a privacy-focused social journaling app (“JournAI”), and a native $CONN token for rewards. All components work together so that users own and earn from the network – there is no single point of control.
Mission
Conneth’s mission is to “connect people in a decentralized way.” We believe everyone should control their own data and connectivity, free from centralized gatekeepers. This vision mirrors emerging decentralized networks: for example, NetSepio (a decentralized VPN/Hotspot project) aims to “democratize cybersecurity access” by turning individuals into “empowered nodes” in a community-run network
aptosfoundation.org
. Conneth shares that goal by empowering users to contribute resources (computing power, bandwidth, etc.) and earn tokens in return, ensuring privacy and freedom from censorship
phantom.com
aptosfoundation.org
.
Features
Conneth Cloud: A decentralized cloud service where users share computing and storage resources. Instead of relying on a single company, Conneth Cloud runs on a peer-to-peer blockchain network
fierce-network.com
. As one report explains, decentralized cloud systems create a “peer-to-peer marketplace for cloud computing, networking, and storage services” by linking together many independent nodes
fierce-network.com
. This makes data more secure (no single point of failure) and empowers the data owner with sole access rights. Conneth Cloud lets anyone contribute spare disk space or CPU cycles and get rewarded.
Decentralized VPN: Conneth’s VPN lets users route their internet traffic through a network of volunteer-operated nodes. This provides anonymity and privacy similar to other decentralized VPNs (like Orchid or Mysterium) by encrypting traffic and removing central servers. In Conneth, anyone can run a VPN server node and earn $CONN for each session they handle. The result is a user-owned private network where no single provider controls your data. This approach aligns with DePIN principles: community-run VPN networks use tokens to incentivize participants who provide secure routing capacity
phantom.com
phantom.com
.
Hotspot (Mesh WiFi/IoT): Conneth supports a mesh Hotspot network. Users can operate Wi-Fi or IoT Hotspot devices that extend connectivity to nearby devices, effectively creating a community wireless network. Hotspot operators earn $CONN tokens in exchange for sharing their internet access. This is analogous to Helium’s model, where anyone can “share your internet and earn” by hosting a hotspot
helium.com
. Over 420,000 Helium hotspots worldwide already demonstrate that peer-to-peer wireless networks can scale; Conneth brings this idea to general internet access.
Social (JournAI): JournAI is Conneth’s built-in social/journaling platform, enhanced by AI. It allows users to privately record and share diary entries, notes, or articles within the network. As a Web3 social application, JournAI emphasizes user ownership and privacy: content and identities belong to the user, not a centralized company. This follows the Web3 social trend where platforms give back data ownership to users
coinsbench.com
. In practice, JournAI lets creators “tokenize” their content or write-to-earn, and governance (moderation, features) can be community-driven, as seen in other decentralized social projects
coinsbench.com
.
$CONN Token: $CONN is the native SPL token on Solana that powers the network. All Conneth services use $CONN for payments and rewards. It has a fixed supply of 10 billion tokens on Solana
coinstats.app
. Token holders can stake $CONN for network rewards, pay for premium cloud/VPN data, and participate in governance. A large portion of the supply is reserved for community rewards: for context, the Solana Name Service token also had a 10B supply and allocated ~40% to users
coinstats.app
. Conneth will similarly allocate most tokens to incentives (staking rewards, community grants, airdrops to early supporters) and reserve the rest for development, liquidity, and the team.
Tokenomics
Conneth’s tokenomics are designed to promote growth and fairness. The total supply is capped at 10,000,000,000 $CONN tokens on Solana
coinstats.app
. Key allocations will include community incentives and staking rewards (e.g. ~40% of supply), ecosystem development (grants/partnerships, ~25%), dev/team reserves (locked with vesting, ~20%), and liquidity support (~5%). For example, Solana Name Service (SNS) also had a 10B supply and allocated 40% to user airdrops and ~26% to ecosystem programs
coinstats.app
. Conneth plans a similar distribution to reward node operators and loyal users while funding ongoing development and partnerships. All tokens and rules will be transparently documented in our tokenomics specifications.
Roadmap (5-Year Plan)
Conneth’s development is structured in phases over five years:
Year 1: Research and MVP. Define core architecture; build and audit initial smart contracts; launch testnet with basic VPN/cloud functionality. Publish whitepaper.
Year 2: Mainnet and Alpha Launch. Release Conneth mainnet; distribute initial tokens (e.g. airdrop to early testers); onboard first users and hotspot operators; release basic JournAI alpha. Develop mobile/desktop apps for services.
Year 3: Network Expansion. Scale up node network (target thousands of VPN/Hotspot nodes globally); optimize performance; integrate AI features in JournAI; begin strategic partnerships (e.g. device makers, communities). Launch governance token voting mechanisms.
Year 4: Feature Growth. Expand Conneth Cloud services (larger storage pool, compute sharing); improve UX and add advanced features (e.g. privacy settings in JournAI, split-tunneling in VPN). Grow community programs and grant funding.
Year 5: Maturity and Ecosystem. Establish Conneth as a mature decentralized network. Expand to new regions; achieve sustainability with a large user base. Evaluate new innovations (mesh networking, cross-chain support). Transition governance to community-led DAO.
Developer Instructions
To set up and build Conneth from source, follow these steps:
Clone the repo:
bash
Copy
Edit
git clone https://github.com/your-org/conneth.git
cd conneth
Install prerequisites: Ensure you have Node.js (for frontend and scripts), Rust, the Solana CLI tool suite, and the Anchor framework for Solana programs.
Build & deploy smart contracts:
bash
Copy
Edit
cd contracts
anchor build         # Compiles the Solana programs
anchor test          # Run contract tests on localnet
anchor deploy --provider.cluster devnet  # (Optional) Deploy to Solana devnet
Run the frontend/app:
bash
Copy
Edit
cd ../frontend
npm install
npm run start
Then visit the local web app (usually at http://localhost:3000) to interact with Conneth.
Additional setup: Any config (e.g. RPC endpoints, network IDs) can be found in the config/ directory. Update or create .env files as needed.
Contributing: Contributions are welcome! Please follow the contribution guidelines in CONTRIBUTING.md
medium.com
. Common steps: fork the repo, create a feature branch, write tests, and submit a pull request. Keep code style consistent and update this README or docs if you add features.
Note: As best practice, our README includes clear instructions, and the LICENSE file contains our open-source license (see below)
medium.com
. Please see CONTRIBUTING.md and CODE_OF_CONDUCT.md for more details on contributing.
License
Conneth is released as open-source software under the MIT License (see the LICENSE file). This means anyone is free to use, modify, and distribute the code. Including an explicit license is strongly recommended for open-source projects
docs.github.com
, so we ensure all users know their rights.
Contact
For support, questions, or partnership inquiries, please contact the core team at contact@conneth.org. You can also join our community channels (Discord/Telegram/Twitter – links on our project homepage) to connect with developers and other users. We encourage issue reports and feature discussions on our GitHub Issues and Discussion pages.
Suggested Repository Structure
To organize the codebase, a typical structure might be:
contracts/ – Solana smart contracts (Anchor programs)
frontend/ – Web/mobile app user interface code
hotspot/ – (Optional) Hotspot firmware or management scripts
vpn/ – (Optional) VPN service implementation or configs
social/ – (Optional) JournAI service/backend code
whitepaper/ – Whitepaper PDF and related research documents
docs/ – Additional documentation, specs, API references
CONTRIBUTING.md – Contribution guidelines
LICENSE – License file (MIT)
docs.github.com
README.md – This overview document
Each folder should include its own README or index explaining contents. This structure keeps contracts, apps, and documentation organized and easy for new contributors to navigate. All information above is current as of 2025. For updates, please check our GitHub repository and official communications. References: Decentralized cloud and VPN concepts
fierce-network.com
phantom.com
phantom.com
aptosfoundation.org
helium.com
; Web3 social networks
coinsbench.com
coinsbench.com
; Solana tokenomics (SNS token example with 10B supply)
coinstats.app
coinstats.app
; README and licensing best practices
medium.com
docs.github.com
.






Sources








