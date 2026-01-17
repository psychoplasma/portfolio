---
layout: default
title: "Software(Blockchain and AI) Developer Portfolio"
---

# Hi, I'm Mustafa 👋

Welcome to my portfolio! I am a software developer from Turkey and have been living in South Korea for the last 10 years. Also looking for remote work possibilities.

## About Me

I'm passionate about building high-impact software, especially at the intersection of blockchain and artificial intelligence. I enjoy working on decentralized applications, smart contracts, and leveraging AI to create innovative solutions.

## Contact

- Email: _Please reach me out through LinkedIn DMs_
- GitHub: [psychoplasma](https://github.com/psychoplasma)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/mustafa-morca-a2472931/)

---

## PROFESSIONAL SUMMARY

Experienced Senior Blockchain Developer with over 7 years of expertise in blockchain technology, smart contracts, and decentralized applications (over 13 years of experience in software development). Proven track record in leading and developing innovative blockchain solutions with a strong background in software development and cloud architecture. Hands-on experience at GenAI application development and cutting-edge AI technologies. Seeking to leverage my skills in a challenging and dynamic environment.

---

## WORK EXPERIENCE

### Senior Blockchain/AI Developer | [Blockchainglobal](https://blockchainglobal.co.kr/)

**Feb 2024 - now**

**Financial Analysis Report Generation for Stock Companies:**

I developed RAG-agentic generative AI application for our client, Korea Investor Relations Service(KIRS - 한국IR협의회). Some sample reports can be seen [here](https://www.kirs.or.kr/research/ai_report.html). The system includes data ingestion pipeline for RAG and report generation pipeline built with FastAPI and Langchain(Langgraph) by utilizing multiple LLM providers(Google's Gemini and Anthropic's Claude). The system is deployed on Google Cloud. Pipelines are running on Cloud Run Jobs with triggers coming from EventArc with file upload to a specific bucket in Cloud storage. FastAPI serves resource API, trigger API for generation pipeline. Backend runs on Cloud Run service. Tech stack includes FastAPI, SQLAlchemy, Postgresql/PGVector, Langchain/Langgraph, Terraform(infra management, CI/CD pipeline).

**Secturity Token Offering Platform:**

I developed STO contract systems and blockchain backend for one of the prestigious banks in Korea(as our primary funding client which starts with Shin). Also I individually attended integration tests with Korea Securities Depository(한국예탁결제원) for our STO contract system on our permissioned blockchain (Hyperledger Besu customized for high transaction throughput). STO token contract system has been built by utilizing ERC1400 token standard together with UUPS and Beacon Proxy for upgradeability. The backend system manages system transactions which includes nonce ordering for sequential transaction broadcasting, transaction tracking and transaction retrial. Tech stack includes Spring Boot with Kotlin, MySQL, Redis, Kafka and Solidity for smart contracts.

**Token Bridging-Swapping System:**

For our funding client, I'm developing token swap platform which is currently in PoC stage. The system bridges public networks to our permissioned blockchain for stable coins (USDC for the time being) which enables crypto holder clients exchange stocks with their cryptocurrencies. USDC deposits to our swap/bridge contract on public chain trigger automatic token issue/mint with equal amount on our permissioned blockchain. Also the bridging system watches and automatically balances liquidities on both side of the system(public and permissioned chains). Contract system is utilizing UUPS for upgradeability. The bridging system consists of two standalone applications and an API server. Tech stack includes NestJS, Prisma with Postgresql and Solidity for smart contracts.

**NFT Minting Platfrom:**

I developed NFT minting system for our stock exchange client. The system automatically mints community NFTs according to user's level in the community system like reaching to certain amount of trade volume, number of transactions, writting contents, dropping comments, getting likes etc. The backend system gets updates from the community system and mints NFT and also manages blockchain transactions. Tech stack includes NestJS, Prisma with Postgresql and Solidity for smart contracts.

#### _AI Service Development_

- Agentic-RAG GenAI application development utilizing Langchain
- Data ingestion pipeline
- Vector search with PostgreSQL + PGVector backend
- PDF parsing and content chunking by section-aware recursive sentence chunking
- MCP server development (local and remote) to serve RAG system directly to business clients

#### _Smart Contract Development_

- Multi-standard token development (ERC-20, ERC-721, ERC-1400)
- Advanced proxy patterns (UUPS, Diamond proxies)
- Token swap mechanisms and Central Securities Depository system development
- Smart contract auditing and security assessment

#### _Enterprise Infrastructure and Blockchain Services_

- Hyperledger Besu private blockchain deployment and maintenance
- Custom blockchain explorer development
- Transaction lifecycle management systems
- Nonce management system development

#### _Cloud & DevOps_

- Kubernetes application orchestration
- Infrastructure as Code with Terraform and Helm
- Google Cloud and Oracle Cloud platform services
- CI/CD with ArgoCD, Github Actions and Google Cloud Build

---

### Co-founder | PandaLabs

**Jan 2022 - Feb 2024**

Co-founded blockchain technology company providing end-to-end consulting services and developing secure financial infrastructure solutions for digital asset management.

#### _Blockchain Consulting & Strategy_

- Technology consulting for blockchain implementation
- Architecture design for enterprise blockchain solutions
- Technical advisory for digital asset integration

#### _Financial Infrastructure Development_

- Blockchain deposit/withdrawal system architecture
- Secure wallet development and implementation
- Multi-chain asset management solutions

#### _Smart Contract Engineering_

- Custom smart contract development and deployment
- Contract optimization and gas efficiency improvements
- Cross-chain compatibility solutions

#### _Operations & Monitoring_

- Production monitoring system deployment
- System performance tracking and optimization
- Infrastructure reliability and uptime management

---

### Senior Blockchain Developer | [Bithumb Cryptocurrency Exchange](https://www.bithumb.com)

**May 2019 - Jan 2021**

Senior blockchain developer at cryptocurrency exchange platform, architecting secure blockchain infrastructure and custody solutions for high-volume digital asset trading operations.

#### _Blockchain Research & Development_

- Emerging blockchain technology research and evaluation
- Protocol analysis and integration feasibility assessment for new asset integrations

#### _Exchange Infrastructure_

- Blockchain deposit/withdrawal system architecture
- Multi-chain wallet development and maintenance
- Real-time transaction processing optimization

#### _Data & Indexing Systems_

- Blockchain indexing system development
- Transaction data aggregation and analysis
- Performance monitoring and optimization

#### _Security & Custody_

- HSM-backed custody system implementation
- Hardware security module integration

---

### Blockchain Developer | [SPIN Protocol](https://www.womanstalk.co.kr/)

**Nov 2018 - May 2019**

Developed comprehensive Dapp ecosystem for e-commerce and influencer marketing, including Ethereum wallet integration, smart contract development, and AWS cloud architecture design.

---

### Blockchain Developer | [SovereignWallet Network](https://sovereignwallet.network)

**May 2018 - Nov 2018**

Built Ethereum wallet mobile application with integrated smart contract functionality for decentralized financial services platform

---

### Senior Software Developer | [AJU-QMS](http://www.ajuqms.co.kr/main)

**Sep 2017 - May 2018**

Developed mobile game testing solutions and comprehensive mobile application development for gaming industry quality assurance.

---

### Senior Software Developer | [AVL (Turkey)](https://www.avl.com/en)

**April 2013 - August 2015**

Created automotive functional testing systems, EV smart navigation solutions, and mobile applications for automotive industry innovation.

---

### Electrical & Electronics Engineer | [ASELSAN (Turkey)](https://www.aselsan.com/en)

**Sep 2010 - August 2012**

Developed embedded software solutions and conducted infrared camera system testing for defense industry applications and military-grade equipment.

---

## EDUCATION

- 2017 - 2016: (M.Sc.) Baduk Studies – Myongji University, Korea
- 2010 - 2005: (B.Sc.) Electrical and Electronics Engineering - Middle East Technical University, Turkey with CGPA: 3.01/4.00

---

## SKILLS

### Languages

- English - **Fluent** _TOEIC: 890 (2018), TOEFL - IBT: 88 (2010)_
- Korean - **Fluent** _TOPIK Level 4 (2022), KIIP Level 5(2022)_
- Turkish - **Native**

### Programming Languages

- Javascript (+8 years)
- TypeScript (+6 years)
- Solidity (+7 years)
- Python (+2 years)
- JVM languages (+6 years): Java, Kotlin
- Go (+2 years)
- Shell Scripting
- C/C++

### AI/LLM Technologies

- LLM pipeline development in Langchain(Langgraph), Huggingface
- MCP server development with FastMCP
- RAG system with PGVector(Postgresql), ChromaDB, VertexAI Search
- Document chunking strategies: Recursive, Semantic, Custom LLM based
- PDF, Excel, table parsing with Unstructed, PyMuPDF and Panda dataframes
- LLM tooling
- Prompt engineering
- Short-time and long-time memory
- Multi-agent application development with custom agent pipeline and Re-act agents of Langgraph

### Blockchain Technologies

- Smart Contract development with Openzeppelin libraries on Truffle, Hardhat, Foundry
- Blockchain service/application development with Viem, Web3js, Ethers.js, Web3j(java), Bitcoin.js, Bitcoinj(java)
- Hyperledger-Besu private network deployment and maintenance
- BIP32 wallets, transaction lifecycle management, cryptography

### DevOps Technologies

- Kubernetes Cluster Administration (Certified Kubernetes Administrator, certificate id: LF-njce76if0h) with Kops
- Kubernetes Application Development with Helm
- CI/CD with Github Actions / Gitlab CI/CD
- Containerization with Docker
- IaC with Terraform and CloudFormation

### Cloud Providers

- Google Cloud
- AWS
- Oracle Cloud

### Backend & Frontend & AI Technologies/Frameworks

- Backend development on Spring Boot with JPA, Hibernate, Apache Kafka
- Backend development with Nest.js
- Fullstack development with Next.js
- Cloud Service (multi-stack, single-stack) design with Serverless Application Model in AWS
- Mobile app/plugin development on Android Studio and React-Native
- Full-stack development on MERN stack
- Desktop app development on Electron with React.js
- RESTful API development
- SQL(PostgreSQL, MySQL) and NoSQL(MongoDB, Google Firestore, AWS Dynamodb)

### Architectures and Development Principles

- Agile Development Cycle
- Test Driven Development
- Behavior Driven Development
- Layered Architecture
- Hexagonal Architecture
- Domain Driven Design
- Event-Sourcing
- CQS and CQRS
- Dependency Inversion Principle
- SOLID design principles

---

## PROJECTS

- [NonceQ](https://github.com/psychoplasma/nonceq)
  - **Description:** Nonce management system for Ethereum transactions to ensure sequential transaction broadcasting from high-frequency trading systems
  - **Tech:** Kotlin and Redis for caching
- [Agentic-RAG GenAI Application](https://github.com/psychoplasma/agentic-rag-app/tree/main/agent)
  - **Description**: GenAI for code suggestion based on specific code ingested in Vector store
  - **Tech:** Langchain, Langgraph, Google VertexAI, PGVector, FastAPI, Python
- [Blockchain address/transaction tracking application](https://github.com/psychoplasma/crypto-balance-bot)
  - **Description:** Balance tracking and notification system for Ethereum and Bitcoin
  - **Tech:** Frontend with Next.js, Backend with Go and Nest.js, datastore as MongoDB, Domain-driven-design applied
- HSM-backed custody solution for Bitcoin and Ethereum (in Bithumb - private project)
  - **Description:** Air-gapped transaction signing and broadcasting system for custodial wallet management
  - **Tech:** Spring Boot with Java, Kafka for messaging, MySQL for datastore
- [Smart contracts for SpinProtocol](https://github.com/spinprotocol/spin-contracts)
  - **Description:** Smart contract system for E-commerce system
  - **Tech:** Openzeppelin, Solidity, Truffle for Smart Contract development
- [Smart contracts for Sovereign Wallet Network](https://github.com/SovereignWallet-Network/MUI-Smart-Contract)
  - **Description:** Smart contract system for token ICO and airdrop
  - **Tech:** Openzeppelin, Solidity, Truffle for Smart Contract development
- [Car sharing app – Greendrive](https://play.google.com/store/apps/details?id=net.gutschi.greendrive)
  - **Description:** Car sharing application
  - **Tech:** Android application with Java and MVVM, Dagger(for DI)
- [Throwing knife game (mobile game)](https://github.com/psychoplasma/take_this_sucker)
  - **Description:** Fun project to learn game development with Unity
  - **Tech:** Unity with C#
- [Simple auto-trading desktop app](https://github.com/psychoplasma/EasyCoinTransfer)
  - **Description:** Fun project for auto-crypto-trading application
  - **Tech:** Electron with Javascript, AJAX, JQuery (out-dated tech stack in my early carreer)

---

## HOBBIES AND INTERESTS

- Contribution to Open-source projects;
  - [Web3j](https://github.com/LFDT-web3j/web3j/pull/2173)
  - [Blockscout](https://github.com/blockscout/helm-charts/pull/67)
- Domain Driven Design
- Blockchain and AI techs
- Cardio trio: Swimming, Running, Cycling
- Playing electric guitar
- Playing Baduk(Game of Go)

---

## ADDITIONAL INFORMATION

Korean Government Scholarship Program Attendee (as a Master Student) 2015-2017
