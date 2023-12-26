# Blockchain Insights Hub


BlockchainInsightsHub is a comprehensive GitHub repository offering a wide array of resources in the blockchain realm, including the latest research, crypto crime reports, regulatory updates, and tools for blockchain development and analytics. It serves as a one-stop hub for enthusiasts, developers, researchers, and regulators, providing essential insights and tools for navigating and understanding the complex landscape of blockchain and cryptocurrencies. Simply click on a topic of interest to jump directly to that specific section.


| [Research](#research) | [Resources](#resources)    | [Repos](#repositories)     | [AI](#artificial-intelligence)| [Associations](#associations)|  [Reports](#reports)   |   [Regulation](#regulation)   |
|-----------------------|----------------------------|----------------------------|-------------------------------|------------------------------|------------|----------------|
| [Academic](#academic) | [General](#general)        | [Blockchain](#blockchain-1)| [Blockchain](#blockchain-1)   | [Blockchain](#blockchain-2)  |  [Private](#private-reports)   | [Cryptocurrency](#cryptocurrency-regulation) |
|                       | [Security](#security)      |                            |                               |                              | [Government](#government-reports) | [Cybersecurity](#cybersecurity-regulation)  |
|                       | [Recovery](#recovery)      |                            |                               |                              |            |    [Privacy](#privacy-regulation)     |
|                       | [Development](#development)|                            |                               |                      |            |                |
|                       | [OSINT](#osint)            |                            |                               |              |            |                |


## Research 

### Academic

This section contains a collection of academic research papers focused on blockchain technology, covering a wide range of topics including security measures, anomaly detection, and network vulnerabilities. The papers explore various aspects of blockchain networks, from advanced techniques for monitoring and detecting unusual activities to comprehensive surveys of existing models and methodologies. Each study contributes to the broader understanding of blockchain's capabilities, challenges, and future research directions.

- [Anomaly Detection based on Traffic Monitoring for Secure Blockchain Networking](https://cwssp.uccs.edu/sites/g/files/kjihxj2466/files/2021-09/2_Anomaly%20Detection%20Based%20on%20Traffic%20Monitoring%20for%20Secure%20Blockchain%20Networking.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This research explores advanced security measures for blockchain networks by focusing on vulnerabilities to threats like denial of service, Eclipse spoofing, and Sybil attacks. Instead of analyzing the blockchain ledger, it introduces a security approach based on monitoring blockchain network traffic statistics. The proposed system comprises a data collection engine for traffic monitoring and an anomaly detection engine employing semi-supervised learning to spot unusual patterns. Experimental results showcase its efficiency in real-time detection of malicious activities, achieving reduced time complexity through prioritized feature analysis.

- [Anomaly Detection in Blockchain Networks: A Comprehensive Survey](https://arxiv.org/pdf/2112.06089.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> The paper "Anomaly Detection in Blockchain Networks: A Comprehensive Survey" provides an in-depth analysis of integrating anomaly detection models in blockchain technology. It discusses the importance of identifying anomalous behavior within blockchain networks to ensure security and reliability. The paper covers various evaluation metrics and key requirements crucial for developing effective anomaly detection models for blockchain. Additionally, it presents a thorough survey of different anomaly detection models from the perspective of each layer of blockchain, concluding with an exploration of significant challenges and future research directions in this field​.

- [Cross-chain Transactions](https://www.cs.ucr.edu/~lesani/companion/icbc20/ICBC20.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper addresses the challenges in cross-chain transactions, where multiple parties exchange assets across various blockchains. It details how these transactions can be represented as a directed graph with vertices representing parties and edges representing asset transfers. The study introduces a novel uniform protocol for general cross-chain transactions, including those with sequenced and off-chain steps, ensuring that if all parties adhere to the protocol, assets are transferred without loss even if a party deviates from the protocol. Additionally, the paper introduces an end-to-end property guaranteeing that if the source parties pay, the sink parties are paid. A significant contribution is the development of the XCHAIN tool, which automatically generates smart contracts in Solidity based on high-level descriptions of cross-chain transactions.

- [Detecting malicious accounts in permissionless blockchains using temporal graph properties](https://appliednetsci.springeropen.com/articles/10.1007/s41109-020-00338-3) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper focuses on identifying malicious behavior in permissionless blockchain networks like Ethereum. It emphasizes the importance of understanding the temporal characteristics of blockchain interactions for security. The authors introduce temporal features such as burst and attractiveness, alongside traditional graph properties like node degree and clustering coefficient. Using these features, they train various machine learning models to detect malicious accounts effectively. The study also analyzes account behaviors over different temporal granularities before labeling them as malicious, leading to the identification of specific accounts that exhibit suspicious activities. This research contributes significantly to enhancing security measures in blockchain technology by providing a methodology for early detection of potential threats.

- [Efficient Fraud Detection in Ethereum Blockchain through Machine Learning and Deep Learning Approaches](https://ijritcc.org/index.php/ijritcc/article/view/8072/6509)<mark style="background-color: #FF7E24">**TLDR**</mark> This paper focuses on identifying fraudulent transactions in the Ethereum blockchain using various machine learning techniques. The study employs a public dataset of Ethereum transactions, preprocessing it to extract pivotal features and then applying predictive modeling. Several algorithms, including decision trees, logistic regression, gradient boosting, XGBoost, and a hybrid model combining random forests and deep neural networks (DNN), are evaluated for their effectiveness in distinguishing between fraudulent and legitimate transactions. The proposed model achieves a precision rate of 97.16%, significantly outperforming existing methods in detecting Ethereum fraud. The study contributes to enhancing blockchain security by demonstrating the effectiveness of sophisticated machine learning and deep learning strategies in fraud detection.

- [Evolve Path Tracer: Early Detection of Malicious Addresses in Cryptocurrency](https://arxiv.org/pdf/2301.05412.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper introduces an innovative approach to early detection of malicious addresses in the cryptocurrency domain. The Evolve Path Tracer model is central to their approach, consisting of the Evolve Path Encoder LSTM, Evolve Path Graph GCN, and Hierarchical Survival Predictor. These components work together to analyze asset transfer paths and corresponding path graphs, capturing early transaction patterns of potential fraud. The model's effectiveness is tested on three real-world illicit bitcoin datasets, showing superior performance compared to existing methods. This paper contributes significantly to the field of cryptocurrency security, offering a scalable and efficient solution for early fraud detection.

- [Identification of token contracts on Ethereum: standard compliance and beyond](https://repositum.tuwien.at/bitstream/20.500.12708/137799/5/Di%20Angelo-2021-International%20Journal%20of%20Data%20Science%20and%20Analytics-vor.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper discusses the challenge of detecting illegal activities in blockchain technology, which has seen a surge in adoption. The authors propose a novel approach that focuses on using Domain Names (DNs) associated with blockchain accounts to determine their malicious nature. They emphasize the importance of temporal aspects linked to these DNs in their methodology. Their technique achieves a balanced-accuracy of 89.53% in detecting malicious blockchain DNs. The study identifies 73,769 DNs exhibiting malicious behavior at least once, with 34,171 of these showing persistent malicious behavior. Interestingly, none of these identified malicious DNs were previously reported in newly officially tagged malicious blockchain DNs.

- [Identifying malicious accounts in blockchains using domain names and associated temporal properties](https://arxiv.org/pdf/2106.13420.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper focuses on combating illegal activities in blockchain technology. The study explores the use of machine learning algorithms trained on transaction behavior and vulnerabilities in the system, incorporating metadata like Domain Names (DNs) and their temporal aspects to detect malicious accounts. The research identifies 144930 DNs exhibiting malicious behavior, with 54114 showing persistent malicious actions over time. The approach includes both temporal and non-temporal features in machine learning pipelines, achieving high balanced-accuracy in detecting malicious blockchain DNs using both supervised and unsupervised learning methods.

- [Towards Safer Smart Contracts: A Sequence Learning Approach to Detecting Security Threats](https://arxiv.org/pdf/1811.06632.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper focuses on enhancing the security of smart contracts on blockchain platforms like Ethereum. It introduces a machine learning-based approach, specifically using Long Short-Term Memory (LSTM) models, to detect security vulnerabilities in smart contracts at the opcode level. This is the first instance of applying LSTM for smart contract exploit detection. The model outperforms traditional symbolic analysis tools in detecting vulnerabilities and maintains constant analysis time despite increasing contract complexity. The effectiveness of the LSTM model was validated through testing on over 620,000 smart contracts from the Ethereum blockchain dataset​.


- [Understanding Money Trails of Suspicious Activities in a cryptocurrency-based Blockchain](https://arxiv.org/pdf/2108.11818.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper presents a comprehensive approach to identifying fraudulent transactions within the Ethereum blockchain using advanced machine learning and deep learning techniques. The study utilizes a public dataset of 9841 Ethereum transactions and engages in two primary phases: data preprocessing and predictive modeling. The research explores various machine learning algorithms, including decision trees, logistic regression, gradient boosting, XGBoost, and a novel hybrid model that combines random forests with deep neural networks (DNN). The findings demonstrate that the proposed model achieves a precision rate of 97.16%, significantly improving fraudulent transaction detection on the Ethereum blockchain compared to existing methods. This research contributes to enhancing the security of blockchain transactions by implementing sophisticated analytical strategies.

- [Vulnerability and Transaction behavior based detection of Malicious Smart Contracts](https://arxiv.org/pdf/2106.13422.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper investigates the link between vulnerabilities in Smart Contracts (SCs) and malicious activities. The study utilizes a 'Turing-complete' programming language, Solidity, which, while enabling automation of tasks in SCs, also introduces vulnerabilities that malicious actors can exploit. The authors map various vulnerability vocabularies, showing how different vulnerabilities are referred to in SC code analysis tools. They found that not all SCs with vulnerabilities are exploited and that the severity of these vulnerabilities doesn't necessarily impact transaction behavior. However, a correlation exists between certain types of malicious activities and specific vulnerabilities. Utilizing unsupervised machine learning algorithms, the research identified 1094 benign SCs behaving similarly to malicious ones when including vulnerability severity scores in the feature set​.

- [Address clustering heuristics for Ethereum](https://www.ifca.ai/fc20/preproceedings/31.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper presents novel approaches to cluster Ethereum addresses, identifying entities likely controlling multiple addresses. It addresses a gap in existing heuristics that were largely focused on Bitcoin's UTXO model and not directly applicable to Ethereum's account model. The paper proposes three heuristics: exploiting patterns related to deposit addresses, multiple participation's in airdrops, and token authorization mechanisms. 

- [SourceP: Detecting Ponzi Schemes on Ethereum with Source Code](https://arxiv.org/pdf/2306.01665.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> The paper proposes SourceP, a novel method to detect smart Ponzi schemes on Ethereum. This method utilizes pre-training models and data flow, significantly simplifying data acquisition and enhancing interpretability compared to existing detection techniques that rely on bytecode, opcode, account features, and transaction behavior. SourceP converts smart contract source code into a data flow graph, then uses a pre-training model for code representation to classify Ponzi schemes. It outperforms current methods with 87.2% recall and 90.7% F-score, demonstrating strong performance and sustainability​​.


- [Detecting Ponzi Schemes on Ethereum: Towards Healthier Blockchain Technology](https://user.it.uu.se/~eding810/conferences/WWW18.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> The paper discusses the increasing popularity of blockchain technology and the concurrent rise of scams like Ponzi schemes on the Ethereum platform. It introduces a method to detect these schemes using data mining and machine learning techniques. This approach involves extracting features from user accounts and operation codes of Ethereum smart contracts to build a classification model. The model effectively identifies potential Ponzi schemes, even at the moment of their creation, with high accuracy. The study estimates over 400 active Ponzi schemes on Ethereum and suggests developing a uniform platform for evaluating and monitoring smart contracts to provide early warnings of scams.


## Resources 

### General

[CoinGecko](https://www.coingecko.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> CoinGecko is the world's largest independent cryptocurrency data aggregator, tracking over 11,000 cryptoassets across more than 900 exchanges globally. It functions as a website and mobile app, aggregating information on the performance of a vast array of cryptocurrencies and providing real-time data on prices, trading volumes, and price fluctuations. CoinGecko distinguishes itself by offering a comprehensive 360-degree overview of the crypto market, including features like market cap, contract addresses, and exchange support for a large number of tokens, along with additional customization options not found in similar platforms​.

[Glassnode](https://glassnode.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> Glassnode is a leading blockchain data and intelligence platform, offering a comprehensive library of on-chain and financial metrics to provide a holistic and contextualized view of the cryptocurrency markets. Founded in Germany in 2018 and headquartered in Zug, Switzerland, Glassnode specializes in cryptanalysis, utilizing on-chain indicators to generate intelligent data and insights, thereby bringing transparency to blockchain activities and enabling informed decisions in the crypto space.

[DefiLlama](https://defillama.com/)  <mark style="background-color: #FF7E24">**TLDR**</mark> DefiLlama is the largest Total Value Locked (TVL) aggregator for decentralized finance (DeFi), known for its commitment to providing accurate, ad-free, and transparent data. As a comprehensive DeFi analytics dashboard, it tracks TVL across various projects, decentralized exchanges, lending protocols, yield farming, and staking pools, covering over 1500 DeFi protocols from more than 80 different blockchains. DefiLlama's data is fully open-source, maintained by a dedicated team and contributors from numerous protocols, emphasizing a transparent and accurate data methodology.

[CryptoPanic](https://cryptopanic.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> CryptoPanic is a comprehensive news aggregator platform tailored for traders and cryptocurrency enthusiasts, providing critical insights on price and market impacts. It offers features like portfolio tracking, media feeds, and blogs, and allows users to vote on important news items, marking them as bullish or bearish signals. This platform is especially useful for understanding the reasons behind cryptocurrency price movements, making it a valuable tool for day traders and those seeking to stay informed about the dynamic crypto market.

[Blockchain Threat Intelligence ](https://newsletter.blockthreat.io/) <mark style="background-color: #FF7E24">**TLDR**</mark> The "Blockchain Threat Intelligence" newsletter, authored by Peter Kacherginsky, is a weekly, independent publication that provides comprehensive coverage of the latest security news, tools, events, vulnerabilities, and threats in the cryptocurrency landscape. It focuses on blockchain, DeFi, and exchange threat intelligence, offering valuable insights into hacks and security developments, and has garnered a substantial subscriber base interested in staying informed about the dynamic and rapidly evolving field of blockchain security.

[Rekt](https://www.rekt.news/) <mark style="background-color: #FF7E24">**TLDR**</mark> Rekt News is an anonymous platform where whistleblowers and DeFi detectives can present their findings to the community. It focuses on analyzing major hacks and exploits in the crypto and DeFi space, providing creative commentary aimed at both educating and entertaining its readers. The content on Rekt News delves into the darker side of DeFi journalism, offering detailed accounts and analysis of various cryptocurrency exploits and security breaches, making it a go-to source for those looking to understand the risks and vulnerabilities inherent in the DeFi sector

[ShapeShift](https://shapeshift.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> ShapeShift is a comprehensive, community-owned, and non-custodial multichain crypto platform that allows users to trade, track, buy, and earn cryptocurrencies across various blockchains. Transitioning from a centralized entity to a decentralized autonomous organization (DAO) in July 2021, ShapeShift has been pivotal in building a borderless, self-custodial, multi-chain financial system founded on open, decentralized protocols. The launch of the ShapeShift v2 platform signifies its commitment to being open-source, non-custodial, and blockchain agnostic, providing a gateway into decentralized finance (DeFi) for crypto enthusiasts, enabling them to manage their digital assets across multiple chains without compromising privacy or incurring additional fees.

[DappRadar](https://dappradar.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> DappRadar, known as the World's Dapp Store, serves as a comprehensive platform for discovering and analyzing decentralized applications (dapps) across various blockchains and product categories. It offers tracking and insightful performance analysis of dapps on networks like Ethereum, BNB Chain, Avalanche, Polygon, and Solana. As the largest Web3 dapp distribution platform, DappRadar attracts over a million users monthly who utilize it to explore new dapps, gain insights into DeFi and NFT collections, and learn about GameFi and play-to-earn gaming. Established in 2018, DappRadar has become a key destination for developers to submit their dapps, with over 8,255 dapps submitted in 2022 alone, reflecting its significant role in aggregating and organizing global blockchain data and providing reliable, data-driven insights to the community.

[Flipside](https://flipsidecrypto.xyz/) <mark style="background-color: #FF7E24">**TLDR**</mark> Flipside Crypto, founded in 2017, is a data analytics company providing blockchain analytics and business intelligence for crypto organizations. The company offers an array of services including cryptocurrency investment, stock market data, audience data, and updates on 17 blockchains, and has raised significant funding, underscoring its impact in the blockchain analytics space.

[Dune Analytics](https://dune.com/home) <mark style="background-color: #FF7E24">**TLDR**</mark> Dune Analytics is a community-first Web3 analytics platform that focuses on making crypto data accessible to a broad audience. Founded in Oslo, Norway in 2018 by Fredrik Haga and Mats Olsen, the platform provides tools for users to query, extract, and visualize data from various public blockchains, including Ethereum, Bitcoin, BNB Chain, Arbitrum, Solana, Gnosis Chain, Polygon, Avalanche, Fantom, Goerli, and Optimism. It allows users, including crypto-asset analysts and investors, to explore and share blockchain ecosystem analytics, research specific projects like NFTs and DeFi platforms, and create visualizations using the data.

[Nansen](https://app.nansen.ai/) <mark style="background-color: #FF7E24">**TLDR**</mark> Nansen is a blockchain analytics platform renowned for enriching on-chain data with millions of wallet labels, assisting crypto investors in discovering opportunities, conducting due diligence, and protecting their portfolios through real-time dashboards and alerts. 

[Ultimate DeFi & Blockchain Research Base](https://github.com/OffcierCia/ultimate-defi-research-base?tab=readme-ov-file) 
<mark style="background-color: #FF7E24">**TLDR**</mark> The Ultimate DeFi Research Database is a comprehensive resource compiling information and analysis on various decentralized finance (DeFi) projects, protocols, and technologies. It serves as a valuable tool for investors, developers, and enthusiasts to stay informed and conduct in-depth research on the rapidly evolving DeFi landscape, including trends, risks, and opportunities.


### Security 

[OpenZeppelin](https://www.openzeppelin.com/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> OpenZeppelin is a leading library for smart contract development on the Ethereum blockchain, offering secure, audited, and reusable code modules like ERC20 and ERC721 tokens, access control, and security features. It's widely used by developers to build decentralized applications, ensuring best practices and reducing the risk of vulnerabilities in smart contract code.

[Forta](https://forta.org/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> Forta is a real-time monitoring and security platform designed for the decentralized finance (DeFi) ecosystem, providing tools to detect and prevent threats in smart contracts and blockchain protocols. It leverages a decentralized network of independent node operators and a suite of detection bots to ensure the security and integrity of on-chain activities, enhancing the resilience of DeFi applications against attacks and vulnerabilities.

[BLOCKSEC Phalcon Explorer](https://phalcon.xyz/explorer)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Phalcon Explorer is a sophisticated tool designed to aid developers, traders, and researchers in intuitively understanding and dissecting complex transactions on blockchain platforms. It is known for its ability to handle complicated transactions with thousands of internal transactions, providing reliable results and analyzing over 500K transactions per month. 

[Immunefi](https://immunefi.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Immunefi is a cybersecurity platform specializing in blockchain and smart contract security, primarily known for hosting bug bounty programs to identify and resolve vulnerabilities in crypto projects. It acts as a bridge between whitehat hackers and blockchain projects, incentivizing the discovery of security flaws to enhance the overall safety and integrity of the DeFi and crypto ecosystem.

[Spearbit](https://spearbit.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Spearbit is a technology company founded in 2021, specializing in Web3 security services. It operates as a decentralized network of security experts, providing consulting services focused on scoping, information gathering, platform security, fix recommendations, and security review updates. Spearbit's unique approach involves sourcing top talent from across the Web3 ecosystem and investing in the mentorship of new security researchers, facilitating their collaboration with industry leaders.

[Code4rena](https://code4rena.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Code4rena is a competitive audit platform founded in 2021, known for efficiently identifying high-severity vulnerabilities in smart contracts faster than other auditing methods. It operates as a decentralized, open organization comprising security researchers, auditors, developers, and individuals with smart contract expertise, focusing on a community-driven approach to competitive smart contract audits.

[Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Damn Vulnerable DeFi" is an educational platform offering a series of challenges designed to teach the offensive security of decentralized finance (DeFi) smart contracts on Ethereum. It serves as an interactive learning resource for the community, focusing on how to exploit vulnerabilities in smart contracts. The challenges encompass a wide range of DeFi-related topics, including flash loans, price oracles, governance, NFTs, decentralized exchanges (DEXs), lending pools, smart contract wallets, and timelocks, and require the creation of attacker contracts and execution of JavaScript code.

[Capture the Ether](https://capturetheether.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Capture the Ether" is a game designed to teach the security aspects of Ethereum smart contracts through a series of engaging and educational challenges. Players hack into various Ethereum contracts, earning points for each successfully completed challenge. Aimed at both fun and education, it provides an opportunity for participants to enhance their hacking skills and gain deeper insights into Ethereum smart contract security. The game, which has been active for over two years, also features a leaderboard, adding a competitive element to the learning experience.

[CryptoZombies](https://cryptozombies.io/)
<mark style="background-color: #FF7E24">**TLDR**</mark> CryptoZombies is renowned as the largest and most interactive education platform for blockchain development, particularly focused on Ethereum and Solidity. It offers a unique learning experience where users can learn to write smart contracts by building their own crypto-collectibles game. Having been operational for over four years, CryptoZombies has amassed over 400,000 registered users who have completed multiple courses, making it a pioneering tutorial for NFTs on the internet. The platform is not only popular among those new to web3 development but also continues to be relevant to experienced developers, with over 1 million classes completed. Additionally, CryptoZombies is exploring content expansion to cover other blockchain networks like Binance, TRON, and Chainlink, further broadening its educational scope.

[openchain.xyz](https://openchain.xyz/)
<mark style="background-color: #FF7E24">**TLDR**</mark> OpenChain.xyz is a versatile tool offering a signature database for identifying unknown function selectors or event topics, and a transaction tracer for in-depth analysis of EVM-compatible transactions. It also includes ABI tools for encoding and decoding ABI data. OpenChain itself is an open-source distributed ledger technology designed for organizations to issue and manage digital assets securely, efficiently, and scalably. It features instant transaction confirmation, no mining fees, and high scalability, making it well-suited for a variety of applications in digital asset management​.

[etherface.io](https://www.etherface.io/hash)
<mark style="background-color: #FF7E24">**TLDR**</mark> Etherface is a comprehensive platform that meticulously documents the signatures of Ethereum transactions conducted through smart contracts, leveraging hashes to enable easy searching for specific smart contracts, accessing their corresponding hashes, and gaining insights into transaction history and associated signatures. With an extensive collection of over 7.5 million signatures gathered from various sources including Etherscan, GitHub, and custom Solidity DApps, Etherface serves as a valuable resource for developers, facilitating seamless access to project repositories associated with smart contracts.

[4byte.directory](https://www.4byte.directory/)
<mark style="background-color: #FF7E24">**TLDR**</mark> 4byte.directory is a comprehensive database that contains over 1.3 million Ethereum function call signatures, essential for mapping byte signatures of Ethereum transactions to their human-readable versions. It primarily assists in identifying the first four bytes of data sent with a transaction in the Ethereum Virtual Machine, defined as the Keccak hash (SHA3) of the canonical representation of the function signature, and also includes mappings for event signatures. This valuable resource for developers processes close to 8.6 million daily requests and offers an API for retrieving and filtering signatures, enhancing the understanding and tracking of Ethereum blockchain transactions​. 

[ZIION](https://www.ziion.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> ZIION 23.2, the latest version of the world's first operating system dedicated to blockchain development and security auditing, marks a significant advancement in tools for Web3 developers and auditors. This release includes enhanced capabilities for Cloud, Web, and IoT auditing, reinforcing ZIION's position as a comprehensive VM for the Web3 domain and beyond. By integrating a wide range of resources for auditing across multiple platforms, ZIION 23.2 offers over 100 pre-installed tools, catering to the diverse needs of blockchain developers and security auditors in a rapidly evolving digital landscape.

[secureum](https://www.secureum.xyz/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Secureum Bootcamp is a flagship community event specifically focused on Ethereum security. It serves as a significant educational and collaborative platform in the Ethereum security ecosystem, often in collaboration with entities like EFDevconnect. The event represents a vital initiative for enhancing security awareness and practices within the Ethereum community, playing a critical role in the ongoing development and stabilization of Ethereum's security infrastructure.

### Recovery

[Web3 Antivirus (W3A)](https://web3antivirus.io/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Web3 Antivirus (W3A) is a security browser extension that provides robust protection against malicious smart contracts and phishing websites in the Web3 ecosystem. It is designed to give users full confidence while exploring Web3 by proactively alerting them to potential scams and dangerous actions. The extension includes features such as smart contract analysis, where it audits smart contracts to identify dangerous logic, critical vulnerabilities, and permissions that could compromise user assets.

[Revoke.cash](https://revoke.cash/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Revoke.cash is a platform designed to enhance the security of your digital assets on decentralized applications (dApps) like Uniswap or OpenSea by allowing you to revoke previously granted token approvals. This feature is crucial because without revoking these permissions, the dApps retain the ability to spend your tokens indefinitely.

[cointool.app](https://cointool.app/dashboard)

[app.unrekt.net](https://app.unrekt.net/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The website app.unrekt.net features a Smart Contract Allowance Checker that is compatible with multiple blockchain networks including ETH, BSC, ARB, AVAX, FTM, MATIC, KAVA, BASE, HECO, CRONOS, MOONBEAM, ASTAR, DOGECHAIN, and CANTO. Its primary function is to help users find and revoke permissions granted to various addresses, allowing them to spend the user's tokens on these networks.

[HackedWalletRecovery](https://hackedwalletrecovery.com/)

### Development

[ZettaBlock](https://www.zettablock.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> ZettaBlock is an enterprise-grade, full-stack Web3 infrastructure platform that specializes in indexing and analytics, effectively merging on-chain and off-chain data. Designed to support real-time, public-facing applications, it allows developers to build reliable GraphQL APIs using SQL in a matter of minutes, without the need to focus on data processing at the frontend or backend. Positioned as an institutional-grade platform, ZettaBlock offers infinite scalability and the ability to unify private and on-chain data, apply custom logic, and instantly generate APIs. This infrastructure-as-code tool significantly reduces the time and resources needed for customers to orchestrate modern data platforms, making it a vital asset in the Web3 development space.

[Tenderly](https://tenderly.co/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Tenderly is an all-in-one Web3 development platform designed to streamline the entire lifecycle of smart contract development, from initial creation to widespread adoption. It provides an integrated environment for building, testing, monitoring, and operating smart contracts, significantly enhancing the development process. The platform includes an open-source Command Line Interface (CLI) tool, which allows developers to see stack traces of their local smart contract execution, quickly identifying the exact line of code where any issues occur, thereby accelerating development efforts. Tenderly's comprehensive set of tools and features make it an essential resource for Web3 developers seeking to optimize smart contract development and deployment​.

[BuidlGuidl](https://app.buidlguidl.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark>  BuidlGuidl is a collaborative group focused on building tools with Scaffold-ETH, aiming to empower builders in creating resources and prototypes for the Ethereum ecosystem. The group focuses on developing forkable components with Scaffold-ETH, offering builders the flexibility to work on various projects, including new voting system components and challenges for SpeedRunEthereum. Members can join BuidlGuidl after completing the first four challenges on SpeedRunEthereum.

### OSINT

- [MALTEGO](https://www.maltego.com/) <mark style="background-color: #FF7E24">**TLDR**</mark> 
Maltego is a highly efficient tool for cybercrime investigation, known for seamlessly integrating data from multiple sources, including OSINT databases, commercial vendors, and internal platforms. Its unique "Transforms" feature automates data retrieval, presenting results visually, thereby enhancing the capabilities of researchers and investigators in fields like internet infrastructure mapping and cryptocurrency transaction analysis.

- [SpiderFoot](https://github.com/smicallef/spiderfoot)<mark style="background-color: #FF7E24">**TLDR**</mark> SpiderFoot is an open-source intelligence (OSINT) automation tool designed to integrate with nearly every data source available, facilitating a range of data analysis methods. It provides an intuitive web-based interface and command-line usage, making data navigation efficient and user-friendly. SpiderFoot is developed in Python 3 and is MIT-licensed, ensuring broad accessibility and adaptability for various OSINT purposes​​.

- [Recon-ng](https://github.com/lanmaster53/recon-ng)<mark style="background-color: #FF7E24">**TLDR**</mark> Recon-ng is a open-source intelligence gathering tool designed to optimize the process of harvesting information from various open sources. It is a full-featured reconnaissance framework, offering a powerful environment for conducting web-based open-source reconnaissance efficiently and comprehensively. 

- [theHarvester](https://github.com/laramies/theHarvester) <mark style="background-color: #FF7E24">**TLDR**</mark> TheHarvester, hosted on GitHub, is a straightforward yet effective open-source intelligence (OSINT) tool used primarily in the reconnaissance phase of red team assessments and penetration tests. It is designed to assist in evaluating a domain's external threat landscape by gathering data such as names, emails, IPs, subdomains, and URLs. This tool incorporates various passive modules like Anubis-DB, CloudSEK's BeVigil for mobile application OSINT, Baidu's search engine, and BinaryEdge's subdomain listings, each contributing uniquely to the intelligence gathering process​.

- [FOCA (Fingerprinting Organizations with Collected Archives)](https://github.com/ElevenPaths/FOCA)<mark style="background-color: #FF7E24">**TLDR**</mark> FOCA is a specialized tool primarily used for extracting metadata and hidden information from various documents found on web pages. It supports a wide range of document formats, including Microsoft Office, Open Office, PDF, Adobe InDesign, and SVG files. FOCA leverages search engines like Google, Bing, and DuckDuckGo to find documents, and it also has the capability to analyze local files for EXIF information from graphic files. The tool conducts a thorough analysis of the information discovered through URLs before downloading the file, making it a comprehensive tool for uncovering hidden data in documents​​​​.

## Repositories

### Blockchain

<mark style="background-color: #FF7E24">GitHub</mark> [**Immunefi PoC Templates**](https://github.com/immunefi-team/forge-poc-templates) The GitHub repository "immunefi-team/forge-poc-templates" is a collaborative project designed to provide reusable and modifiable Proof of Concept (PoC) examples for various Ethereum Virtual Machine (EVM) based vulnerabilities. The goal of this repository is to enhance the quality of bug reports and facilitate a more efficient and straightforward process for white-hat hackers to create PoCs and validate their findings. These templates are specifically created for testing PoCs in local environments and then submitting them to bug bounty programs, with any other usage being explicitly prohibited​​.

## Artificial Intelligence

### Blockchain

[Bittensor](https://bittensor.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Bittensor aims to revolutionize the field of decentralized AI by providing an alternative to the dominant, top-down approach of current technology giants. It is a platform that facilitates the creation of various decentralized commodity markets, or 'subnets', under a unified token system, functioning through Bittensor's blockchain. This allows for the interconnection and integration of these markets into a single computing infrastructure.

[Autonolas](https://www.autonolas.network/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Autonolas offers an open-source software stack designed to decentralize off-chain processes, particularly useful for DAO operations. This platform aims to unify off-chain code and consolidate existing data, computation, and transaction automation processes, thereby enhancing control and reducing dependency on individual humans and bots.


## Associations

### Blockchain

[Blockchain Research Institute](https://www.blockchainresearchinstitute.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Blockchain Research Institute (BRI) is a global independent think tank dedicated to exploring and disseminating knowledge about the strategic implications of blockchain technology for business, government, and society. Co-founded by Don and Alex Tapscott, BRI is supported by a consortium of international corporations and government agencies, making it a prominent and collaborative center for blockchain research and knowledge-sharing​​.

[Blockchain Association](https://theblockchainassociation.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Blockchain Association serves as the collective voice of the cryptocurrency industry, with a mission to advance the future of crypto in the United States. It focuses on promoting the potential of blockchain technology and shaping policies to ensure its success. The association, comprised of nearly 100 members including sector-leading investors, companies, and projects, collaborates to support a pro-innovation national policy and regulatory framework for the crypto economy. Established in 2018 under the leadership of CEO Kristin Smith, the Blockchain Association annually reviews the challenges and accomplishments in the cryptocurrency industry, emphasizing its commitment to fostering a progressive and innovation-friendly national policy framework for the crypto economy​.

[Global Blockchain Business Council (GBBC)](https://gbbcouncil.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Global Blockchain Business Council (GBBC) is the world's largest and leading industry association for the blockchain technology and digital assets community. Established in 2017 in Davos as a Swiss-based non-profit, GBBC comprises over 500 institutional members and 231 ambassadors from 109 jurisdictions and disciplines. The council is committed to advocating for the advancement and implementation of blockchain technology across various industries and sectors​.

[The American Blockchain and Cryptocurrency Association](https://abcaonline.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The American Blockchain and Cryptocurrency Association (ABCA) is a non-profit trade association dedicated to the educational and advocacy needs of the blockchain and cryptocurrency community. Representing a diverse group that includes crypto miners, investors, innovators, and entrepreneurs, ABCA focuses on shaping and advancing the interests of this rapidly evolving sector. The organization's initiatives and efforts are geared towards fostering a deeper understanding and more robust development within the blockchain and cryptocurrency fields​​​​.

## Reports

### Private Reports

- **TRM Labs** [Tackling Crypto Crime](https://uploads-ssl.webflow.com/6082dc5b67056233213587a4/6583048f70ed88922723499d_TRM_LE-Survey-Report_2023_V4.pdf)

- **ELLIPTIC** [How to Defend Your Business Against Crypto Crime](https://www.elliptic.co/hubfs/Elliptic_Guide_How_to_Defend_Your_Business_Against_Crypto_Crime.pdf?utm_campaign=Typologies%202023&utm_medium=email&_hsmi=265863773&_hsenc=p2ANqtz--p_2DJz-Rfhr1jtDNMY29u-jGfF-waFRugC8TaFVwMWFzitZQYV04UHbPAVD-3JHR4uk7BT6dAK_mppe2g3udD83DaqgyCUk0qQFdbPyLvMC79A2k&utm_content=265863773&utm_source=hs_automation)

- **ciphertrace** [Your go-to guide to the FATF’s crypto Travel Rule](https://ciphertrace.com/wp-content/uploads/2022/10/CipherTrace_Travel-Rule-Guide_FINAL.pdf)

- **ciphertrace** [Crypto Crimes & Anti-Money Laundering (AML) Report March 2023](https://ciphertrace.com/wp-content/uploads/2023/03/Ciphertrace-CAML-Report-Q3_FINAL.pdf)

- **Chainalysis** [The 2023 Crypto Crime Report](https://hkibfa.io/wp-content/uploads/2023/02/Crypto_Crime_Report_2023.pdf)

- **Chainalysis** [The 2022 Crypto Crime Report](https://blockbr.com.br/wp-content/uploads/2022/06/2022-crypto-crime-report.pdf)

- **ciphertrace** [Crime and Anti-Money Laundering Report October 2022](https://ciphertrace.com/wp-content/uploads/2023/03/Ciphertrace-CAML-Report-Q3_FINAL.pdf)

### Government Reports 

- **Federal Bureau of Investigation (FBI)** [Crime Data Explorer](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home) <mark style="background-color: #FF7E24">**TLDR**</mark> This website aims to provide transparency, create easier access, and expand awareness of criminal, and noncriminal, law enforcement data sharing; improve accountability for law enforcement; and provide a foundation to help shape public policy with the result of a safer nation. Use the CDE to discover available data through visualizations, download data in .csv format, and other large data files.

- **Federal Bureau of Investigation (FBI)** [2022 INTERNET CRIME REPORT](https://www.ic3.gov/Media/PDF/AnnualReport/2022_IC3Report.pdf)

- **Federal Bureau of Investigation (FBI)** [2021 INTERNET CRIME REPORT](https://www.ic3.gov/Media/PDF/AnnualReport/2021_IC3Report.pdf)
  
- **Federal Trade Commission (FTC)** [Consumer Sentinel Network](https://www.ftc.gov/enforcement/consumer-sentinel-network/reports)<mark style="background-color: #FF7E24">**TLDR**</mark> Consumer Sentinel is a unique investigative cyber tool that gives members of the Consumer Sentinel Network access to millions of reports.

- **Federal Trade Commission (FTC)** [Consumer Sentinel Network Data Book 2022](https://www.ftc.gov/system/files/ftc_gov/pdf/CSN-Data-Book-2022.pdf)



## Regulation

### Cryptocurrency Regulation

- [Atlantic Council](https://www.atlanticcouncil.org/programs/geoeconomics-center/cryptoregulationtracker/) <mark style="background-color: #FF7E24">**TLDR**</mark> The Atlantic Council's Cryptocurrency Regulation Tracker is a comprehensive research project examining how 60 countries, including G20 members and those with high rates of cryptocurrency adoption, regulate cryptocurrencies. The research categorizes regulations based on legal status, tax policy, anti-money laundering and terrorist financing requirements, consumer protection rules, and licensing obligations. It provides insights into the legal status of cryptocurrencies across these countries, revealing varying degrees of regulation, ranging from full legality to partial or general bans, and highlights the rapid evolution and experimentation in cryptocurrency regulations worldwide.

- [Non-EU countries' regulations on crypto-assets and their potential implications for the EU](https://www.europarl.europa.eu/RegData/etudes/BRIE/2023/753930/EPRS_BRI(2023)753930_EN.pdf)

- [(EU) 2023/1114 on Markets in Crypto-Assets (“MiCAR” or “Act”)](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32023R1114) 

###  Cybersecurity Regulation

For ethical hackers and pen testers seeking to familiarize themselves with various legal requirements and regulations, the following resources can be highly beneficial:

- [**International Association of Privacy Professionals (IAPP)**]((https://iapp.org/)): IAPP offers resources on global privacy laws and regulations, which can be invaluable for understanding the legal landscape in different jurisdictions. Their website provides up-to-date information, training, and certifications in data protection.

- [**SANS Institute**](https://www.sans.org/) : SANS is a trusted source for cybersecurity training and certifications. They offer courses and materials specifically focused on legal issues in cybersecurity. Visit their website for more information.

- [**Cybersecurity and Infrastructure Security Agency (CISA)**]((https://www.cisa.gov/)): CISA provides guidelines and resources on cybersecurity best practices and compliance with U.S. laws. Their website is a valuable resource for staying informed about U.S. cybersecurity regulations.

- [**EFF's Electronic Frontier Foundation**](https://www.eff.org/): EFF offers insights into privacy laws, digital rights, and related legal matters. Visit their site for resources and updates on legal issues in the digital world.

- **Cyber Law Blogs and News Sites**: Websites like [**Cybersecurity Law Report**](https://www.cybersecuritylawreport.com/) and [**Lawfare**](https://www.lawfareblog.com/) provide articles, analysis, and updates on cybersecurity law and policy.

### Privacy Regulation

This section provides an overview of various global privacy regulations, highlighting key legislation from different regions and countries. It includes information on comprehensive data protection acts such as Brazil's LGPD, California's CCPA, China’s PIPL, the EU's GDPR, and Singapore's PDPA, among others. Each link directs to detailed resources about the specific acts, offering insights into the legal frameworks established to protect personal data and privacy across diverse jurisdictions worldwide.

- [Brazil's General Personal Data Protection Act - LGPD](https://lgpd-brazil.info/)

- [California Consumer Privacy Act - CCPA](https://theccpa.org/)

- [China’s Personal Information Protection Law - PIPL](https://personalinformationprotectionlaw.com/)

- [Colorado Privacy Act - CPA](https://coag.gov/resources/colorado-privacy-act/)

- [Connecticut Data Privacy Act - CTDPA](https://www.cga.ct.gov/2022/act/Pa/pdf/2022PA-00015-R00SB-00006-PA.PDF)

- [Delaware Personal Data Privacy Act](https://legis.delaware.gov/json/BillDetail/GenerateHtmlDocument?legislationId=140388&legislationTypeId=1&docTypeId=2&legislationName=HB154)

- [European Union's General Data Protection Regulation - GDPR](https://gdpr-info.eu/)

- [Hong Kong Personal Data Privacy Ordinance - PDPO](https://www.pcpd.org.hk/english/data_privacy_law/ordinance_at_a_Glance/ordinance.html)

- [Indiana Consumer Data Protection Act](https://iga.in.gov/legislative/2023/bills/senate/5/details)

- [Iowa Consumer Data Protection Act - ICDPA](https://www.legis.iowa.gov/docs/publications/LGE/90/SF262.pdf)

- [Montana’s Consumer Data Privacy Act](https://leg.mt.gov/bills/2023/billpdf/SB0384.pdf)

- [Oregon Consumer Privacy Act - OCPA](https://olis.oregonlegislature.gov/liz/2023R1/Measures/Overview/SB619)

- [Singapore's Personal Data Protection Act - PDPA](https://sso.agc.gov.sg/Act/PDPA2012)

- [South Africa's Protection of Personal Information Act - POPIA](https://popia.co.za/)

- [Tennessee Information Protection Act](https://wapp.capitol.tn.gov/apps/BillInfo/Default.aspx?BillNumber=SB0073)

- [Texas Data Privacy and Security Act - TDPSA](https://capitol.texas.gov/BillLookup/History.aspx?LegSess=88R&Bill=HB4)

- [Utah Consumer Privacy Act - UCPA](https://le.utah.gov/~2022/bills/static/SB0227.html)

- [Virginia Consumer Data Protection Act - VCDPA](https://law.lis.virginia.gov/vacodefull/title59.1/chapter53/)








