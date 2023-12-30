# Blockchain Insights Hub

Discover a world of blockchain and cybersecurity insights with the Blockchain Insights Hub on GitHub. This expansive repository offers a rich collection of resources, including the latest in blockchain research, thorough analyses of crypto crimes, updates on cybersecurity regulations, and an extensive suite of tools for blockchain development and cyber threat analysis. Ideal for blockchain enthusiasts, cybersecurity professionals, academic researchers, and regulatory bodies, this hub provides direct access to crucial information and tools, empowering you to stay ahead in the dynamic realms of blockchain technology and cybersecurity. Simply click on a topic of interest to jump directly to that specific section.

# Table of Contents

## [1. Research](#research)

- [Blockchain](#blockchain)
- [Cybercrime](#cybercrime)

## [2. Resources](#resources)

- [General](#general)
- [Security](#security)
- [Recovery](#recovery)
- [Development](#development)
- [OSINT](#osint)
- [Cybersecurity](#cybersecurity)

## [3. Repositories](#repositories)

- [Blockchain](#blockchain-1)

## [4. Artificial Intelligence](#artificial-intelligence)

- [Blockchain](#blockchain-1)

## [5. Nonprofits](#nonprofits)

- [Blockchain](#blockchain-2)
- [Cybersecurity](#cybersecurity-1)

## [6. Reports](#reports)

- [Private](#private-reports)
- [Government](#government-reports)

## [7. Regulation](#regulatio)

- [Cryptocurrency](#cryptocurrency-regulation)
- [Cybersecurity](#cybersecurity-regulation)
- [Privacy](#privacy-regulation)

![Overview of DeFi Protocol Security Measures and Services](https://github.com/nemo-nesciam/Blockchain-Insights-Hub/blob/main/assets/DeFi%20Protocol%20Security%20Landscape.png "DeFi Protocol Security Landscape")
Image citation: BlockSec. (n.d.). DeFi Protocol Security Landscape. Introduction - BlockSec Documents. <https://docs.blocksec.com/about-blocksec/introduction>

## Personal Resource Usage Key

- 🔴 ---> Resource I use occasionally
- 🟡 ---> Resource I use frequently
- 🟢 ---> Resource I use all the time

## Research

### Blockchain

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

- [Tracing Transactions Across Cryptocurrency Ledgers](https://www.usenix.org/system/files/sec19-yousaf_0.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> The paper titled presented at the USENIX Security Symposium focuses on the interconnection between different cryptocurrencies. It introduces techniques to trace transaction flows across multiple cryptocurrencies, primarily Bitcoin and Ethereum, which are otherwise considered separate and disconnected. The research demonstrates how cross-currency trades on non-custodial cryptocurrency exchanges can be tracked. By leveraging unique transactional patterns and behaviors, the study reveals insights into user activities and cryptocurrency flows across different blockchain ecosystems. The findings have significant implications for understanding the broader landscape of cryptocurrency movements and can be used to enhance security and anti-money laundering measures in the digital currency domain.

- [An Overview on Smart Contracts: Challenges, Advances and Platforms](https://arxiv.org/pdf/1912.10370.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> The paper discusses the transformative impact of smart contract technology on traditional industries and business processes. Smart contracts, embedded in blockchains, automate the enforcement of contractual terms without needing a trusted third party. This automation reduces administrative costs, enhances business process efficiency, and lowers risks. However, the paper also highlights several challenges that need addressing to fully harness the potential of smart contracts. It includes a survey on smart contracts, detailing their challenges, technical advances, a comparison of smart contract platforms, and a categorization of smart contract applications with examples​​.

- [Modelling, Analysis, and Performance Evaluation of Cross-Chain Transactions](https://www.techrxiv.org/doi/full/10.36227/techrxiv.20718058.v3) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper focuses on the development of a cross-chain model generator called Hephaestus to mitigate risks in blockchain interoperability (BI) and cross-chain transactions. It addresses the vulnerability of cross-chain bridges to attacks, which have led to significant financial losses. Hephaestus captures local transactions and generates cross-chain models, assisting in monitoring and identifying potential malicious activities or deviations from expected behavior. The system has shown promising results in processing cross-chain transactions efficiently and provides a framework for evaluating the state and security of cross-chain applications​​​​.

- [An overview on cross-chain: Mechanism, platforms, challenges and advances](https://pdf.sciencedirectassets.com/271990/1-s2.0-S1389128622X00157/1-s2.0-S1389128622004121/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBAaCXVzLWVhc3QtMSJHMEUCIEFW1t84vXC4EwJvcLMAOAwhJLFtSzQWlogbbMRaRRltAiEAzN8Lek3nGA%2BfPfDF2fvSTHe4oRxUGL4bLks9SE0LYkgqvAUImf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDKUa1Laqvn0ddL8SsiqQBfQKu%2BOUHGiVuVGRzPkDpF4NIjbUs9bpiusoXbAUuCMCoPfBNKKeivXDv4Qj2BhtEdjUKhe9gnKgcIPa%2F2uZAUiwYcqPdlqyWl91ejahAjmtOqx1gf%2BFINHPGQMpF%2FyZ0xBGEdVkY52oygIH3dnJlYancRvNbeNSEIhj0Be8ImGdYljk1ktvMPU2V6cDkkjB8otLcK3JTJoju6ce8lkg34zB70bPR0aqdidTzMhnRzPpmxe125kk7xoLreCxSwuB5GOsp0YKbqh0BSe7FWo%2Bh03Wxwr6hLsHAmBJXEUX7KbTrMy%2FSzplt3Y5PnatAamA1PryKUAjFMa%2FnhjTwThcllzJSorcSCvVoiGqn6b0H8MBy5ARenxqlqk0UtEtS3NT%2BSqJ%2F0DyBIB5fSImuTVknadUof99%2BKcyrr0Squytonq03Y%2BJdfA9qZuSUWua7XqKNyK6dz2ID3st%2FPonzJ30s4Z1UHARYRfAp1%2BV0JfPa%2FdxCmdr7vhtIa9R8301jti5w9XT58J66DAd68hB4nkvy4gBW7oG3yy0DYTUugru%2Bt6Qbsf%2BW2ONxZR13dr%2Bkx8nthfn9coCevV%2F6Hbw%2FVO5CZ28ASZvksA9xdwFq6Iz%2B21f5W%2F59dE5Em7eagc2Mm5vojVCyqtnwUCzmPveEDabmVwoOOiAVHDbb2yrhVUEzMtFo3WsoGCA4uhPxud%2BsR6%2FAHGQDAOvzoCMsrnasRCxBilgZqZft66HOYV6sRMSdyv68F%2B0k89p1iZIwn35eHPDkAYHwoqkXZ0cKlTrJCHK4hnZsx6CFuIotGYSqeiXHq3KCXRn8IShHvZQbMQYkHumY1HKnmMX033cH7RJi763JGJGpsoSwiDZvr3xDmXapiNoMLPRrawGOrEBGzedA49PeVyUtISXZqegbPn8r1J5MWfVe%2F3ZCl%2F0Wxaa4zsXFI4Yk3CQMQCGU%2FeSx2Ow8DBxzx6JSZOe1ZkCI1FGSDZx5ZhieU%2Fcvpt7hyD4QQ5NCZ6nQ%2Fin%2B3ajX6g3467hadGUKEXtjhHlXSrYBjml16%2F75zG8qfNaPf2MqmigJH%2FqON8j8jhPoOufd37C0s1JB6OhFWafMfbd3X8tncn3IH47zThd7mDdNlk4Kawh&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20231227T003344Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYROA2IBJH%2F20231227%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=6e1a6d57f75924f37e2d8db50fdc8c2b8adbbc93558d7364afb6a95a526f1be3&hash=b54e1dcdaebe10df28abdc2cd11d57df9eb48b724b6a3ee94dcad0a6203ecd1e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1389128622004121&tid=spdf-a30a252e-1907-48ab-90cd-05b6a039b1a7&sid=2c8f34d368ecf04aaa4bc81599263007ebf3gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=15165e520d065556&rr=83bd794cef73746b&cc=us) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper explores the development and application of blockchain cross-chain technology, emphasizing the importance of cross-chain technology in enhancing blockchain interoperability and scalability. It presents a comprehensive examination of current cross-chain technologies and projects, including detailed analyses and comparisons. The paper also discusses the challenges faced by current cross-chain technologies and offers potential solutions, contributing to the ongoing development of cross-chain technology​​.

- [A review of blockchain cross-chain technology](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/blc2.12032) <mark style="background-color: #FF7E24">**TLDR**</mark> This article examines the development, significance, and current research status of blockchain cross-chain technology, focusing on methods for data interaction and value transfer between different blockchains. It proposes an interoperability architecture to address security, privacy, and effectiveness issues, categorizing various cross-chain technologies and techniques. The paper highlights the importance of cross-chain technology in improving blockchain interconnectivity, interoperability, and scalability, offering a systematic overview of mainstream technologies and projects in this field.

- [SoK: Security of Cross-chain Bridges: Attack Surfaces, Defenses, and Open Problems](https://arxiv.org/pdf/2312.12573.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This research paper focuses on the security aspects of cross-chain bridges, which are critical for token and data exchanges across different blockchains. The authors categorize cross-chain attacks from the past two years into 10 distinct types, each accompanied by explanations and Solidity code examples. The paper also explores existing and potential defenses against these security vulnerabilities and discusses open questions and future research directions in the realm of cross-chain bridge security​​​​​​.







### Cybercrime

- [Understanding cybercrime in ‘real world’ policing and law enforcement](https://journals.sagepub.com/doi/10.1177/0032258X221107584) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper provides an in-depth exploration of cybercrime, highlighting its growing prevalence and the challenges faced by law enforcement in addressing these crimes. It delves into the technological, individual, social, and situational aspects that foster cybercrime, offering insights into how this knowledge can inform more effective policing strategies. The study emphasizes the complexity and evolving nature of cybercrime, underscoring the need for specialized knowledge and approaches in both investigation and prevention.

- [Cybercrimes: A Proposed Taxonomy and Challenges](https://www.semanticscholar.org/reader/9931106635614064e4cdb0fd0dff7b9cca2fad10) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper presents an extensive survey on cybersecurity, proposing a new taxonomy for cybercrime that encompasses various types of cyberattacks. It categorizes recent incidents based on fundamental cybersecurity principles like confidentiality, integrity, and availability, and analyzes these incidents to identify challenges in the field. The study also discusses the evolution and increasing complexity of cybercrimes, highlighting the need for updated security strategies and future research directions in cybersecurity.

- [Conceptualizing Cybercrime: Definitions, Typologies and Taxonomies](https://www.mdpi.com/2673-6756/2/2/28) <mark style="background-color: #FF7E24">**TLDR**</mark>
This paper addresses the complexities and inconsistencies in defining and understanding cybercrime across different jurisdictions, highlighting the impact on legal, policy, and academic spheres. Through a structured literature review, it identifies key definitions, typologies, and taxonomies of cybercrime from both academic and non-academic sources, culminating in a new classification framework to better understand cybercrime and cyberdeviance. The review acknowledges ongoing challenges in conceptualizing cybercrime but offers recommendations for future work towards a universal understanding and a comprehensive classification system.

- [A taxonomy of cyber-harms: Defining the impacts of cyber-attacks and understanding how they propagate](https://watermark.silverchair.com/tyy006.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA2MwggNfBgkqhkiG9w0BBwagggNQMIIDTAIBADCCA0UGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMmwBtWEXUtcEmn0sWAgEQgIIDFp7Hva3KZlQliSfiarBTGqvBfa4JxcxskltCBEzMNS47Rbs4LSE2o-rTPSXyf7Z3uFW7JIp82-KOoFy2xkr3Tk4YLZwRKcKtWkxPwiLz3hgzAcKnYNWtCEKMgUefvefjkR60HCD2-xi293V631F2RNk-RIox8u3JR7OHAgja2SvKPHxEU7MslzYckjeFtVLlmv1ulJIQIqFphwYRAZ1KnWZOK57vNspIYdc3l3541-L4lL61GTbuPHHSpofwMlGHk0PebKmVtWAXap_cYiSjO76S9UO_FjISHmct6_01EdJwxyMEpEuiWi54UMgVFTBl9OjRoAcYU4IzxdoUNB1ZckokaNXtBZCJ6-iPbJ8JVV-Wv9ZyfVT9zaAQkRD64eWiNX8OBb7iVLjb8Hi0PUJdwST6NmMhzaqiLzSK7ju2PZQ5qpiJvgLAAya2XqzCj_dXQR7BNJtgcTURw-Fwh8CpXrEnLQnkUONSTetpNgITThX0rrdq7D0adh1489zmG3NJXgWMMhhIT5U2ruM_qwJpswu1w7Uf1dLovMY8wur-QsnbYqULAdp_nupK1bcyH4mAvR4O-Z9890dRYTFUEXzy-YcyVlSwv9g6xFhtvAp7Qi5aJcIxAYM50YeR1GlxXoDrVhLlxTFzsRKSwIRQqrxmzxXrxqjeWDO5Z3XGJ2lRRdz_Cgz3aHjnlDhJ6qvlVu4UJpemhZ8Zf3ORoBma7uc7bhU-HGdbtuwFpm59YdE4kJIB6sugKNvwzwwwk6tWZ-u8Co5U_d8uJFt4rL1x2yM0Cf3pYdmGrAHJnmmLt9l3bBhLF6UFIL67ofoYF12nhxR0HfBCi_EOKS_dyAIxh-YDV2fhoA7-ANb6bRW6LE6Q4LNf7DH_i0jAnrCrI89LKn0G7MqHYxYClQkMJbzEazhBXJV1GcOcEm6mLPhVm6mT3S2xNTxSD_jsvmjBaWKa9togYGfmy3F4VzMYDY5Dlw8m2ye6AOaZRhTE7GgXJc7dwae5w3Z9kFheka1d_ckpvw5XDOH55WiBM0EWpHi8gIMwVJi2p_BPAWs) <mark style="background-color: #FF7E24">**TLDR**</mark> This article examines the rapidly evolving threat landscape of cyberattacks and the challenges organizations face in measuring and understanding the harm caused by such incidents. It presents a taxonomy of cyber-harms based on extensive literature review and case studies, categorizing them into physical/digital, economic, psychological, reputational, and social/societal harms. The article also analyzes real-world cases, including incidents at Sony, JPMorgan, and Ashley Madison, to illustrate how different types of cyber-harm interconnect and propagate, ultimately advocating for analytical tools to help organizations assess and manage these harms effectively.

- [Analyzing the Performance of the Inter-Blockchain Communication Protocol](https://arxiv.org/pdf/2303.10844.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper introduces a novel framework for empirically evaluating cross-chain communication protocols, with a focus on the Cosmos Network's Inter-Blockchain Communication Protocol (IBC). It aims to identify and analyze the limitations of these protocols, addressing the growing demand for effective blockchain interconnectivity. The comprehensive evaluation of the Cosmos Network's IBC exemplifies the paper's approach towards enhancing the performance and understanding of cross-chain communication in the blockchain sector.

## Resources

### General

[CoinGecko](https://www.coingecko.com/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> CoinGecko is the world's largest independent cryptocurrency data aggregator, tracking over 11,000 cryptoassets across more than 900 exchanges globally. It functions as a website and mobile app, aggregating information on the performance of a vast array of cryptocurrencies and providing real-time data on prices, trading volumes, and price fluctuations. CoinGecko distinguishes itself by offering a comprehensive 360-degree overview of the crypto market, including features like market cap, contract addresses, and exchange support for a large number of tokens, along with additional customization options not found in similar platforms​.

[Glassnode](https://glassnode.com/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Glassnode is a leading blockchain data and intelligence platform, offering a comprehensive library of on-chain and financial metrics to provide a holistic and contextualized view of the cryptocurrency markets. Founded in Germany in 2018 and headquartered in Zug, Switzerland, Glassnode specializes in cryptanalysis, utilizing on-chain indicators to generate intelligent data and insights, thereby bringing transparency to blockchain activities and enabling informed decisions in the crypto space.

[DefiLlama](https://defillama.com/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> DefiLlama is the largest Total Value Locked (TVL) aggregator for decentralized finance (DeFi), known for its commitment to providing accurate, ad-free, and transparent data. As a comprehensive DeFi analytics dashboard, it tracks TVL across various projects, decentralized exchanges, lending protocols, yield farming, and staking pools, covering over 1500 DeFi protocols from more than 80 different blockchains. DefiLlama's data is fully open-source, maintained by a dedicated team and contributors from numerous protocols, emphasizing a transparent and accurate data methodology.

[CryptoPanic](https://cryptopanic.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> CryptoPanic is a comprehensive news aggregator platform tailored for traders and cryptocurrency enthusiasts, providing critical insights on price and market impacts. It offers features like portfolio tracking, media feeds, and blogs, and allows users to vote on important news items, marking them as bullish or bearish signals. This platform is especially useful for understanding the reasons behind cryptocurrency price movements, making it a valuable tool for day traders and those seeking to stay informed about the dynamic crypto market.

[Blockchain Threat Intelligence](https://newsletter.blockthreat.io/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> The "Blockchain Threat Intelligence" newsletter, authored by Peter Kacherginsky, is a weekly, independent publication that provides comprehensive coverage of the latest security news, tools, events, vulnerabilities, and threats in the cryptocurrency landscape. It focuses on blockchain, DeFi, and exchange threat intelligence, offering valuable insights into hacks and security developments, and has garnered a substantial subscriber base interested in staying informed about the dynamic and rapidly evolving field of blockchain security.

[Rekt](https://www.rekt.news/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Rekt News is an anonymous platform where whistleblowers and DeFi detectives can present their findings to the community. It focuses on analyzing major hacks and exploits in the crypto and DeFi space, providing creative commentary aimed at both educating and entertaining its readers. The content on Rekt News delves into the darker side of DeFi journalism, offering detailed accounts and analysis of various cryptocurrency exploits and security breaches, making it a go-to source for those looking to understand the risks and vulnerabilities inherent in the DeFi sector.

[Web3Sec](https://www.web3sec.news/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Web3Sec is a community-driven platform aimed at keeping users informed about the latest in web3 security, blockchain technology, and audits. It's designed as a resource for professionals to stay ahead of breaches and hacks, offering news and insights conveniently. The platform also provides a means to join a like-minded community to learn and contribute to a secure web3 future, with features like an all-in-one security resource center that includes a search and date filter for tracking web3 hacks and trends.

[Week in Ethereum News](https://weekinethereumnews.com/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> Week in Ethereum News is an online newsletter providing weekly updates and insights on Ethereum-related developments. It covers a wide range of topics including Ethereum network upgrades, decentralized finance (DeFi), layer 1 and layer 2 developments, security issues, ecosystem news, and updates for developers. The site is a valuable resource for anyone interested in staying informed about the latest trends, technological advancements, and changes in the Ethereum blockchain and its growing ecosystem.

[HashingBits](https://quillaudits.substack.com/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> HashingBits, provided by QuillAudits on Substack, is a weekly newsletter focused on Web3.0 cybersecurity. It shares the latest information on hacks, research, tools, and career opportunities related to the Web3.0 space. The newsletter aims to keep its subscribers informed and ahead in the rapidly evolving field of Web3.0 security and related technologies​​.

[ShapeShift](https://shapeshift.com/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> ShapeShift is a comprehensive, community-owned, and non-custodial multichain crypto platform that allows users to trade, track, buy, and earn cryptocurrencies across various blockchains. Transitioning from a centralized entity to a decentralized autonomous organization (DAO) in July 2021, ShapeShift has been pivotal in building a borderless, self-custodial, multi-chain financial system founded on open, decentralized protocols. The launch of the ShapeShift v2 platform signifies its commitment to being open-source, non-custodial, and blockchain agnostic, providing a gateway into decentralized finance (DeFi) for crypto enthusiasts, enabling them to manage their digital assets across multiple chains without compromising privacy or incurring additional fees.

[DappRadar](https://dappradar.com/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> DappRadar, known as the World's Dapp Store, serves as a comprehensive platform for discovering and analyzing decentralized applications (dapps) across various blockchains and product categories. It offers tracking and insightful performance analysis of dapps on networks like Ethereum, BNB Chain, Avalanche, Polygon, and Solana. As the largest Web3 dapp distribution platform, DappRadar attracts over a million users monthly who utilize it to explore new dapps, gain insights into DeFi and NFT collections, and learn about GameFi and play-to-earn gaming. Established in 2018, DappRadar has become a key destination for developers to submit their dapps, with over 8,255 dapps submitted in 2022 alone, reflecting its significant role in aggregating and organizing global blockchain data and providing reliable, data-driven insights to the community.

[Flipside](https://flipsidecrypto.xyz/) 
<mark style="background-color: #FF7E24">**TLDR**</mark> Flipside Crypto, founded in 2017, is a data analytics company providing blockchain analytics and business intelligence for crypto organizations. The company offers an array of services including cryptocurrency investment, stock market data, audience data, and updates on 17 blockchains, and has raised significant funding, underscoring its impact in the blockchain analytics space.

[Dune Analytics](https://dune.com/home) 
<mark style="background-color: #FF7E24">**TLDR**</mark> Dune Analytics is a community-first Web3 analytics platform that focuses on making crypto data accessible to a broad audience. Founded in Oslo, Norway in 2018 by Fredrik Haga and Mats Olsen, the platform provides tools for users to query, extract, and visualize data from various public blockchains, including Ethereum, Bitcoin, BNB Chain, Arbitrum, Solana, Gnosis Chain, Polygon, Avalanche, Fantom, Goerli, and Optimism. It allows users, including crypto-asset analysts and investors, to explore and share blockchain ecosystem analytics, research specific projects like NFTs and DeFi platforms, and create visualizations using the data.

[Nansen](https://app.nansen.ai/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Nansen is a blockchain analytics platform renowned for enriching on-chain data with millions of wallet labels, assisting crypto investors in discovering opportunities, conducting due diligence, and protecting their portfolios through real-time dashboards and alerts.

[Ultimate DeFi & Blockchain Research Base](https://github.com/OffcierCia/ultimate-defi-research-base?tab=readme-ov-file) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> The Ultimate DeFi Research Database is a comprehensive resource compiling information and analysis on various decentralized finance (DeFi) projects, protocols, and technologies. It serves as a valuable tool for investors, developers, and enthusiasts to stay informed and conduct in-depth research on the rapidly evolving DeFi landscape, including trends, risks, and opportunities.

### Security

[OpenZeppelin](https://www.openzeppelin.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> OpenZeppelin is a leading library for smart contract development on the Ethereum blockchain, offering secure, audited, and reusable code modules like ERC20 and ERC721 tokens, access control, and security features. It's widely used by developers to build decentralized applications, ensuring best practices and reducing the risk of vulnerabilities in smart contract code.

[Audit Wizard](https://www.auditwizard.io/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Audit Wizard is a unique platform designed for the auditing of smart contracts. It integrates all essential tools required for this purpose, facilitating seamless code security. The platform addresses the complexities of the web3 security landscape by offering an all-in-one solution that includes static code analysis, proof-of-concept (PoC) testing, AI threat modeling, and automatic audit report generation, all accessible through a user-friendly interface without the need for downloads. Additionally, Audit Wizard provides comprehensive web3 security tools, such as vulnerability scanning, AI-driven vulnerability detection, and PoC testing, enhancing the overall security and reliability of smart contracts​​​​​​.


[Forta](https://forta.org/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Forta is a real-time monitoring and security platform designed for the decentralized finance (DeFi) ecosystem, providing tools to detect and prevent threats in smart contracts and blockchain protocols. It leverages a decentralized network of independent node operators and a suite of detection bots to ensure the security and integrity of on-chain activities, enhancing the resilience of DeFi applications against attacks and vulnerabilities.

[BLOCKSEC Phalcon Explorer](https://phalcon.xyz/explorer) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> The Phalcon Explorer is a sophisticated tool designed to aid developers, traders, and researchers in intuitively understanding and dissecting complex transactions on blockchain platforms. It is known for its ability to handle complicated transactions with thousands of internal transactions, providing reliable results and analyzing over 500K transactions per month.

[BLOCKSEC MetaSleuth](https://metasleuth.io/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> MetaSleuth is a crypto tracking and investigation platform. It provides a visual flow of funds map to help users analyze and track fund transfers, which can be particularly useful for compliance services by exchanges, wallets, and Virtual Asset Service Providers (VASPs). It's designed to allow users to investigate and share findings about fund transfers, which could be a valuable tool for addressing and understanding blockchain transactions and potential security incidents.

[BLOCKSEC MetaDock](https://blocksec.com/metadock) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark>
MetaDock is a browser extension offered by BlockSec designed to enhance the experience of crypto users navigating the blockchain. It offers features such as viewing fund flows with one click, gaining insights from high-value correlated addresses, and understanding risks associated with NFT collections via a comprehensive radar chart. Additionally, MetaDock provides enhanced labels, compliance scores, and security alerts for addresses and transactions, interacts with popular blockchain tools, and aims for a more user-friendly blockchain exploration experience. It emphasizes user privacy, not collecting or uploading user information, and allows users to opt-out of features at any time.

[Slither](https://github.com/crytic/slither) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Slither is a static analysis tool for Solidity, the primary programming language used for Ethereum smart contracts. Developed by Trail of Bits, it's designed to help developers identify vulnerabilities and code issues in smart contracts before they are deployed on the Ethereum network. Slither analyzes the contract's source code, detecting a wide range of security issues, code optimizations, and best practice violations. It's widely used in the Ethereum development community for enhancing the security and quality of smart contract code. Slither is an important tool for any developer looking to ensure the safety and efficiency of their Ethereum-based applications.

[EthTx Transaction Decoder](https://ethtx.info/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> EthTx.info is a platform that provides detailed information about Ethereum transactions. It allows users to explore and analyze Ethereum blockchain transactions, offering insights into the specifics of each transaction, such as the sender, receiver, amount, gas used, and other relevant data. If you need information about a particular transaction, you can use EthTx.info by entering the transaction hash in their search bar.

[Immunefi](https://immunefi.com/) :red_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Immunefi is a cybersecurity platform specializing in blockchain and smart contract security, primarily known for hosting bug bounty programs to identify and resolve vulnerabilities in crypto projects. It acts as a bridge between whitehat hackers and blockchain projects, incentivizing the discovery of security flaws to enhance the overall safety and integrity of the DeFi and crypto ecosystem.

[Spearbit](https://spearbit.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Spearbit is a technology company founded in 2021, specializing in Web3 security services. It operates as a decentralized network of security experts, providing consulting services focused on scoping, information gathering, platform security, fix recommendations, and security review updates. Spearbit's unique approach involves sourcing top talent from across the Web3 ecosystem and investing in the mentorship of new security researchers, facilitating their collaboration with industry leaders.

[Sherlock](https://www.sherlock.xyz/) :red_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> 
Sherlock.xyz offers comprehensive security auditing services for blockchain protocols, specializing in smart contracts. They boast a combination of legacy audit techniques and audit contests to create robust security audits in Web3. Their services include thorough security audits, allowing participants to find bugs and earn rewards, and the opportunity to stake USDC for yields, backed by secure protocols. Sherlock differentiates itself with a deep expertise in auditing, being recognized as an effective underwriter in Web3. They provide up to $5 million in reimbursement in the event of a hack and a $500,000 bug bounty for covered exploits, with a trustless claims process ensuring payouts are executed entirely through smart contracts without the possibility of claim blocking​​​​.

[Code4rena](https://code4rena.com/) :red_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Code4rena is a competitive audit platform founded in 2021, known for efficiently identifying high-severity vulnerabilities in smart contracts faster than other auditing methods. It operates as a decentralized, open organization comprising security researchers, auditors, developers, and individuals with smart contract expertise, focusing on a community-driven approach to competitive smart contract audits.

[CodeHawks](https://www.codehawks.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> 
CodeHawks is a platform specializing in smart contract auditing. It allows individuals to register as auditors, enabling them to participate in security contests and challenges. These contests include both competitive and private audits. In competitive audits, auditors attempt to find vulnerabilities within a set time, with their identities hidden until rewards are distributed. A final audit report is produced after evaluating all findings. Private audits function like UpWork for auditors, where auditors bid on projects or are invited by protocols. The platform serves as a bridge connecting protocol developers, who submit codebases for auditing, with security-focused researchers​​​​.

[Hats.finance](https://hats.finance/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Hats.finance is a platform aiming to become the decentralized infrastructure of choice for Web3 security. It builds self-sufficient and autonomous security infrastructure, integrating with major DeFi protocols to enhance security. The platform offers various proactive distributed security mechanisms including a decentralized bug bounty ecosystem, skin-in-the-game audits, and audit competitions. Audit competitions are time-based events where high-quality auditors compete to secure smart contracts quickly. Skin-in-the-game audits require auditors to deposit a portion of their fee into a project's bug bounty, aligning incentives for ongoing project security. Additionally, the bug bounty ecosystem operates fully on-chain, supporting liquidity contributions to vaults, with a decentralized arbitration mechanism to resolve disputes​​.

[Ethernaut](https://ethernaut.openzeppelin.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Ethernaut is a Web3/Solidity-based war game inspired by overthewire.org, primarily used for educational purposes. It's designed to help developers learn Ethereum coding and smart contract security through interactive problem-solving. The game consists of various levels, each presenting a smart contract with a vulnerability. The player's goal is to exploit these vulnerabilities to progress.

[Damn Vulnerable DeFi](https://www.damnvulnerabledefi.xyz/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Damn Vulnerable DeFi" is an educational platform offering a series of challenges designed to teach the offensive security of decentralized finance (DeFi) smart contracts on Ethereum. It serves as an interactive learning resource for the community, focusing on how to exploit vulnerabilities in smart contracts. The challenges encompass a wide range of DeFi-related topics, including flash loans, price oracles, governance, NFTs, decentralized exchanges (DEXs), lending pools, smart contract wallets, and timelocks, and require the creation of attacker contracts and execution of JavaScript code.

[Capture the Ether](https://capturetheether.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Capture the Ether" is a game designed to teach the security aspects of Ethereum smart contracts through a series of engaging and educational challenges. Players hack into various Ethereum contracts, earning points for each successfully completed challenge. Aimed at both fun and education, it provides an opportunity for participants to enhance their hacking skills and gain deeper insights into Ethereum smart contract security. The game, which has been active for over two years, also features a leaderboard, adding a competitive element to the learning experience.

[CryptoZombies](https://cryptozombies.io/)
<mark style="background-color: #FF7E24">**TLDR**</mark> CryptoZombies is renowned as the largest and most interactive education platform for blockchain development, particularly focused on Ethereum and Solidity. It offers a unique learning experience where users can learn to write smart contracts by building their own crypto-collectibles game. Having been operational for over four years, CryptoZombies has amassed over 400,000 registered users who have completed multiple courses, making it a pioneering tutorial for NFTs on the internet. The platform is not only popular among those new to web3 development but also continues to be relevant to experienced developers, with over 1 million classes completed. Additionally, CryptoZombies is exploring content expansion to cover other blockchain networks like Binance, TRON, and Chainlink, further broadening its educational scope.

[openchain.xyz](https://openchain.xyz/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> OpenChain.xyz is a versatile tool offering a signature database for identifying unknown function selectors or event topics, and a transaction tracer for in-depth analysis of EVM-compatible transactions. It also includes ABI tools for encoding and decoding ABI data. OpenChain itself is an open-source distributed ledger technology designed for organizations to issue and manage digital assets securely, efficiently, and scalably. It features instant transaction confirmation, no mining fees, and high scalability, making it well-suited for a variety of applications in digital asset management​.

[etherface.io](https://www.etherface.io/hash)
<mark style="background-color: #FF7E24">**TLDR**</mark> Etherface is a comprehensive platform that meticulously documents the signatures of Ethereum transactions conducted through smart contracts, leveraging hashes to enable easy searching for specific smart contracts, accessing their corresponding hashes, and gaining insights into transaction history and associated signatures. With an extensive collection of over 7.5 million signatures gathered from various sources including Etherscan, GitHub, and custom Solidity DApps, Etherface serves as a valuable resource for developers, facilitating seamless access to project repositories associated with smart contracts.

[4byte.directory](https://www.4byte.directory/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> 4byte.directory is a comprehensive database that contains over 1.3 million Ethereum function call signatures, essential for mapping byte signatures of Ethereum transactions to their human-readable versions. It primarily assists in identifying the first four bytes of data sent with a transaction in the Ethereum Virtual Machine, defined as the Keccak hash (SHA3) of the canonical representation of the function signature, and also includes mappings for event signatures. This valuable resource for developers processes close to 8.6 million daily requests and offers an API for retrieving and filtering signatures, enhancing the understanding and tracking of Ethereum blockchain transactions​.

[ZIION](https://www.ziion.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> ZIION 23.2, the latest version of the world's first operating system dedicated to blockchain development and security auditing, marks a significant advancement in tools for Web3 developers and auditors. This release includes enhanced capabilities for Cloud, Web, and IoT auditing, reinforcing ZIION's position as a comprehensive VM for the Web3 domain and beyond. By integrating a wide range of resources for auditing across multiple platforms, ZIION 23.2 offers over 100 pre-installed tools, catering to the diverse needs of blockchain developers and security auditors in a rapidly evolving digital landscape.

[secureum](https://www.secureum.xyz/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Secureum Bootcamp is a flagship community event specifically focused on Ethereum security. It serves as a significant educational and collaborative platform in the Ethereum security ecosystem, often in collaboration with entities like EFDevconnect. The event represents a vital initiative for enhancing security awareness and practices within the Ethereum community, playing a critical role in the ongoing development and stabilization of Ethereum's security infrastructure.

[Foundry Fuzz](https://book.getfoundry.sh/forge/fuzz-testing)
<mark style="background-color: #FF7E24">**TLDR**</mark> Foundry Fuzz is a tool that is used for testing applications (in this case, smart contracts) by inputting large amounts of random data ("fuzz") to the contract and observing for any crashes, vulnerabilities, or unexpected behavior. Fuzzing is a common technique in software testing to find security vulnerabilities, and it's particularly useful in the context of smart contracts due to their immutable nature and the high financial stakes often involved in blockchain and cryptocurrency applications.

[Echidna](https://github.com/crytic/echidna) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Echidna is a sophisticated tool used for fuzzing Ethereum smart contracts to identify vulnerabilities and bugs. It employs property-based testing where developers define the properties that a contract should always satisfy, and Echidna generates various inputs to test these properties. This tool is essential in the Ethereum development ecosystem for ensuring smart contract security and reliability, as it helps detect potential exploits like reentrancy and integer overflows before deployment on the blockchain.

[SlowMist Hacked](https://hacked.slowmist.io/en/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> SlowMist Hacked is a website that tracks and reports on various hacking incidents in the blockchain and cryptocurrency domains. The site details different types of security breaches and attacks on blockchain platforms and digital wallets, providing insights into the methods used by hackers and the impact of these incidents on the blockchain ecosystem. It serves as a resource for understanding the vulnerabilities and security challenges in the rapidly evolving world of blockchain technology.

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

[Alchemy](https://www.alchemy.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark>  Alchemy is a blockchain development platform that provides tools for developers to build, scale, and operate decentralized applications (dApps) on the Ethereum network. It offers enhanced APIs, real-time data, powerful analytics, and other features to facilitate the development process.

[Infura](https://www.infura.io/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Infura is a service that provides Ethereum and IPFS infrastructure and developer tools. It offers an easy-to-use API that allows developers to connect to Ethereum nodes without having to set up and maintain their own blockchain infrastructure. Infura is widely used for its reliability and scalability in handling Ethereum network requests.

[Moralis](https://moralis.io/)
<mark style="background-color: #FF7E24">**TLDR**</mark>
Moralis is a platform that provides tools and services to simplify the development of decentralized applications (dApps) on various blockchain networks, including Ethereum. It offers a suite of features such as a fully managed, infinitely scalable backend infrastructure, real-time database synchronization, user authentication, and easy-to-use SDKs.

[ZettaBlock](https://www.zettablock.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> ZettaBlock is an enterprise-grade, full-stack Web3 infrastructure platform that specializes in indexing and analytics, effectively merging on-chain and off-chain data. Designed to support real-time, public-facing applications, it allows developers to build reliable GraphQL APIs using SQL in a matter of minutes, without the need to focus on data processing at the frontend or backend. Positioned as an institutional-grade platform, ZettaBlock offers infinite scalability and the ability to unify private and on-chain data, apply custom logic, and instantly generate APIs. This infrastructure-as-code tool significantly reduces the time and resources needed for customers to orchestrate modern data platforms, making it a vital asset in the Web3 development space.

[Tenderly](https://tenderly.co/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Tenderly is an all-in-one Web3 development platform designed to streamline the entire lifecycle of smart contract development, from initial creation to widespread adoption. It provides an integrated environment for building, testing, monitoring, and operating smart contracts, significantly enhancing the development process. The platform includes an open-source Command Line Interface (CLI) tool, which allows developers to see stack traces of their local smart contract execution, quickly identifying the exact line of code where any issues occur, thereby accelerating development efforts. Tenderly's comprehensive set of tools and features make it an essential resource for Web3 developers seeking to optimize smart contract development and deployment​.

[BuidlGuidl](https://app.buidlguidl.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark>  BuidlGuidl is a collaborative group focused on building tools with Scaffold-ETH, aiming to empower builders in creating resources and prototypes for the Ethereum ecosystem. The group focuses on developing forkable components with Scaffold-ETH, offering builders the flexibility to work on various projects, including new voting system components and challenges for SpeedRunEthereum. Members can join BuidlGuidl after completing the first four challenges on SpeedRunEthereum.

[REMIX](https://remix.ethereum.org/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Remix is an open-source web and desktop application used for writing, deploying, and testing smart contracts for Ethereum. It's commonly used by developers working with Ethereum's blockchain technology. Remix provides a user-friendly interface and a suite of tools that make it easier to write and debug Solidity code (Ethereum's smart contract language), interact with smart contracts, and manage Ethereum transactions.

[Foundry](https://github.com/foundry-rs/foundry)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Foundry framework is a fast, portable, and modular toolkit for Ethereum application development, written in Rust. It includes Forge for testing smart contracts, written in Solidity or Vyper, and Cast for interacting with Ethereum nodes. Designed for efficiency and reliability, Foundry aims to provide developers with robust tools for building, testing, and deploying Ethereum-based applications effectively.

[Hardhat](https://hardhat.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Hardhat is an Ethereum development environment and framework designed for professionals. It provides developers with a comprehensive set of tools to easily set up, test, debug, and deploy smart contracts on the Ethereum network. Key features include a built-in Ethereum Virtual Machine (EVM), smart contract debugging capabilities, and network management for deploying to both public and private networks, enhancing the overall Ethereum development proces.

[Brownie](https://eth-brownie.readthedocs.io/en/stable/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Brownie is a Python-based development and testing framework for smart contracts on the Ethereum network. It integrates seamlessly with the Python programming environment, offering features like automated contract testing, interactive console, and built-in debugging tools. Brownie aims to simplify the development process for Ethereum developers by providing a straightforward and Pythonic interface, making it particularly suitable for those already familiar with Python programming.

[ApeWorX](https://pypi.org/project/eth-ape/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Ape Framework as a user-friendly Web3 development tool for compiling, testing, and interacting with smart contracts through a single command-line interface. It supports a variety of contract languages and blockchain networks, thanks to its modular plugin system. The framework, compatible with Linux, macOS, and Windows via WSL, can be installed using methods like pipx, pip, or Docker, and offers both a CLI tool and a Python SDK for comprehensive smart contract development and interaction.

[Vyper](https://docs.vyperlang.org/en/stable/index.html)
<mark style="background-color: #FF7E24">**TLDR**</mark> Vyper is a contract-oriented, pythonic programming language designed for the Ethereum Virtual Machine (EVM). Its primary principles include security, aiming to make building secure smart-contracts both possible and natural; simplicity in language and compiler design; and high auditability, ensuring the code is human-readable and challenging to write misleadingly. Unlike Solidity, Vyper deliberately avoids features like modifiers, class inheritance, inline assembly, function and operator overloading, recursive calling, and infinite-length loops to enhance security and readability. Vyper doesn't seek to replace Solidity entirely but focuses on security, sometimes at the expense of functionality​​​​.

[Truffle](https://trufflesuite.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Truffle is a popular development framework for Ethereum, designed to make life easier for blockchain developers. It provides a suite of tools for writing, testing, and deploying smart contracts, with built-in support for custom migrations and network management. Truffle also integrates seamlessly with other blockchain development tools and has a user-friendly interface, making it a go-to choice for developers building on Ethereum.

[Forefy Smart Contract Auditors Space](https://smart.forefy.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Forefy Smart Contract Auditors Space is a gamified platform designed to train and promote expert Smart Contract Security Auditors. It aims to address the limitations of traditional leaderboards in evaluating auditor skills by considering factors overlooked in these rankings, such as private audits, unique findings, customer satisfaction, and time efficiency. The platform features a structured level system where participants engage in various tasks, each with a storyline and specific goals. Their unique scoring system combines automated calculations with human oversight to evaluate solutions based on criteria like professional writing, originality, efficiency, and rarity of findings​​​​.


### OSINT

[MALTEGO](https://www.maltego.com/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark>
Maltego is a highly efficient tool for cybercrime investigation, known for seamlessly integrating data from multiple sources, including OSINT databases, commercial vendors, and internal platforms. Its unique "Transforms" feature automates data retrieval, presenting results visually, thereby enhancing the capabilities of researchers and investigators in fields like internet infrastructure mapping and cryptocurrency transaction analysis.

[SpiderFoot](https://github.com/smicallef/spiderfoot) :red_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> SpiderFoot is an open-source intelligence (OSINT) automation tool designed to integrate with nearly every data source available, facilitating a range of data analysis methods. It provides an intuitive web-based interface and command-line usage, making data navigation efficient and user-friendly. SpiderFoot is developed in Python 3 and is MIT-licensed, ensuring broad accessibility and adaptability for various OSINT purposes​​.

[Recon-ng](https://github.com/lanmaster53/recon-ng) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Recon-ng is a open-source intelligence gathering tool designed to optimize the process of harvesting information from various open sources. It is a full-featured reconnaissance framework, offering a powerful environment for conducting web-based open-source reconnaissance efficiently and comprehensively.

[theHarvester](https://github.com/laramies/theHarvester) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> TheHarvester, hosted on GitHub, is a straightforward yet effective open-source intelligence (OSINT) tool used primarily in the reconnaissance phase of red team assessments and penetration tests. It is designed to assist in evaluating a domain's external threat landscape by gathering data such as names, emails, IPs, subdomains, and URLs. This tool incorporates various passive modules like Anubis-DB, CloudSEK's BeVigil for mobile application OSINT, Baidu's search engine, and BinaryEdge's subdomain listings, each contributing uniquely to the intelligence gathering process​.

[FOCA (Fingerprinting Organizations with Collected Archives)](https://github.com/ElevenPaths/FOCA) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> FOCA is a specialized tool primarily used for extracting metadata and hidden information from various documents found on web pages. It supports a wide range of document formats, including Microsoft Office, Open Office, PDF, Adobe InDesign, and SVG files. FOCA leverages search engines like Google, Bing, and DuckDuckGo to find documents, and it also has the capability to analyze local files for EXIF information from graphic files. The tool conducts a thorough analysis of the information discovered through URLs before downloading the file, making it a comprehensive tool for uncovering hidden data in documents​​​​.

[Shodan](https://www.shodan.io/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Shodan is a specialized search engine for the Internet of Things (IoT), often referred to as a search engine for internet-connected devices. Unlike traditional search engines that index web content, Shodan scans for various types of devices connected to the Internet, including servers, webcams, printers, security systems, and more. It indexes the information these devices expose publicly, such as banners and metadata, which can reveal software versions, configurations, and other details.

[Metagoofil](https://github.com/opsdisk/metagoofil) :red_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Metagoofil is a tool used for information gathering and data mining. It's primarily used to extract metadata of public documents (such as PDFs, DOCs, PPTs) available on target websites. This metadata can include information like usernames, software versions, and system information, which might be useful for someone conducting a cybersecurity analysis or penetration testing. Metagoofil operates by searching for specific file types hosted on a given domain, downloading them, and then extracting and analyzing their metadata, which can often reveal sensitive or insightful information about the organization or infrastructure behind the website.

[grep.app](https://grep.app/) <mark style="background-color: #FF7E24">**TLDR**</mark> grep.app is a powerful code search tool that allows users to search across half a million Git repositories. It supports case-sensitive searches, regular expressions, and whole word searches, making it a comprehensive resource for developers and coders looking to find specific pieces of code across numerous projects and platforms​​.

[lampyre](https://lampyre.io/) <mark style="background-color: #FF7E24">**TLDR**</mark> Lampyre is a data analysis and OSINT (Open Source Intelligence) tool used for a variety of purposes including cyber security, law enforcement, financial analytics, and due diligence. It offers efficient solutions for obtaining, visualizing, and analyzing data in one place, enabling users to see connections and details that might otherwise be overlooked. Lampyre is particularly user-friendly for beginners in OSINT, as it simplifies the visualization of data and does not require extensive technical knowledge or API manipulation​​​​​​.

[Have I Been Pwned](https://haveibeenpwned.com/) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> Have I Been Pwned (HIBP) is a website and service that allows individuals to check if their personal data has been compromised in data breaches. Users can enter their email addresses or phone numbers, and HIBP checks against a database of known breached accounts. It provides information on which breaches the data was exposed in and what type of data was compromised.

[OWASP Amass](https://owasp.org/www-project-amass/) :green_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark> OWASP Amass is an advanced tool developed by the Open Web Application Security Project (OWASP) for network mapping and external asset discovery. OWASP Amass utilizes a variety of techniques such as DNS enumeration, scraping web pages, and querying data sources to gather information about a target's external assets and internet footprint. It's particularly useful in the field of cybersecurity for understanding the attack surface of an organization by identifying domains, subdomains, IP addresses, and associated services.

[Sherlock](https://sherlock-project.github.io/#:~:text=Sherlock%2C%20a%20powerful%20command%20line,on%20MacOS%2C%20Linux%20and%20Windows) :yellow_circle:
<mark style="background-color: #FF7E24">**TLDR**</mark>Sherlock is a powerful command line tool provided by the Sherlock Project, designed for use in OSINT (Open Source Intelligence) research. It functions by scouring the web to find profiles that match a subject's username across various social networks. Sherlock automates the process of checking whether a profile with a particular username exists on different websites, making it a useful tool for gathering information about a subject.

### Cybersecurity

For ethical hackers and pen testers seeking to familiarize themselves with various legal requirements and regulations, the following resources can be highly beneficial:

- [**International Association of Privacy Professionals (IAPP)**](https://iapp.org/): IAPP offers resources on global privacy laws and regulations, which can be invaluable for understanding the legal landscape in different jurisdictions. Their website provides up-to-date information, training, and certifications in data protection.

- [**SANS Institute**](https://www.sans.org/) : SANS is a trusted source for cybersecurity training and certifications. They offer courses and materials specifically focused on legal issues in cybersecurity. Visit their website for more information.

- [**Cybersecurity and Infrastructure Security Agency (CISA)**](https://www.cisa.gov/): CISA provides guidelines and resources on cybersecurity best practices and compliance with U.S. laws. Their website is a valuable resource for staying informed about U.S. cybersecurity regulations.

- [**EFF's Electronic Frontier Foundation**](https://www.eff.org/): EFF offers insights into privacy laws, digital rights, and related legal matters. Visit their site for resources and updates on legal issues in the digital world.

- **Cyber Law Blogs and News Sites**: Websites like [**Cybersecurity Law Report**](https://www.cybersecuritylawreport.com/) and [**Lawfare**](https://www.lawfareblog.com/) provide articles, analysis, and updates on cybersecurity law and policy.

- [**OWASP Threat Dragon**](https://owasp.org/www-project-threat-dragon/): OWASP Threat Dragon allows users to create diagrams of their software architecture and visually map out potential security threats. It also includes a rule engine to suggest common threats and mitigations based on the elements present in the diagrams. This tool is useful for security analysts, software developers, and system architects to understand and address security risks early in the software development lifecycle.

## Repositories

### Blockchain

<b style="background-color: #FF7E24">GitHub</b> [**Immunefi PoC Templates**](https://github.com/immunefi-team/forge-poc-templates) The GitHub repository "immunefi-team/forge-poc-templates" is a collaborative project designed to provide reusable and modifiable Proof of Concept (PoC) examples for various Ethereum Virtual Machine (EVM) based vulnerabilities. The goal of this repository is to enhance the quality of bug reports and facilitate a more efficient and straightforward process for white-hat hackers to create PoCs and validate their findings. These templates are specifically created for testing PoCs in local environments and then submitting them to bug bounty programs, with any other usage being explicitly prohibited​​.

<b style="background-color: #FF7E24">GitHub</b> [**Pickle Finance Contract Directory**](https://github.com/pickle-finance/contracts)
The GitHub repository for Pickle Finance's contracts includes a variety of Ethereum-based contracts related to the Pickle Finance ecosystem. These contracts encompass different functionalities, such as DILL contracts, main contracts, gauges, and various Pickle Jars (pJars) for different blockchain platforms like Ethereum, Polygon, OKEx, Arbitrum, Moonriver, Cronos, Aurora, Metis, Moonbeam, Optimism, Fantom, Gnosis, and Kava. The repository is a comprehensive collection of deployed contracts for Pickle Finance, detailing the architecture and tools essential for the platform's operation across multiple blockchains​​.

<b style="background-color: #FF7E24">GitHub</b> [**DIRP - DEFI Incident Response Playbooks**](https://github.com/0xKoda/DIRP/tree/main) :yellow_circle:
The GitHub repository 0xKoda/DIRP focuses on DeFi (Decentralized Finance) Incident Response Playbooks. It addresses the lack of incident response plans among DeFi protocols by providing adaptable playbooks for various scenarios. These resources include detailed flowcharts, step-by-step instructions, and additional references for effective incident management. The community is encouraged to contribute by reviewing existing content, identifying gaps, and submitting detailed, well-researched contributions to enhance the repository's effectiveness and coverage​​.

<b style="background-color: #FF7E24">Google Docs</b> [Crisis Handbook - Smart Contract Hack](https://substack.com/redirect/8f57520a-21f0-4be7-a6e8-2fa8935063c0?j=eyJ1IjoiMXJweGUxIn0.8u_jpyqvkXZfN0M0oLan_aRBB4qs2ezAXbhFuHcCtRs) :yellow_circle: The Crisis Handbook - Smart Contract Hack by SEAL Team is a comprehensive guide for managing smart contract security incidents. It includes a detailed actions checklist, covering immediate steps like notifying relevant parties, creating a 'War Room' for collaboration, and duplicating essential documents for shared access. The handbook emphasizes the importance of assigning key roles, conducting thorough analysis and investigations, implementing protocol and web actions, and maintaining effective communication throughout the incident. Post-incident actions focus on confirming resolution, preparing for future events, and conducting a post-mortem analysis. The guide also provides advice, suggested tools, and platforms for efficient incident management and recovery efforts.

## Artificial Intelligence

### Blockchain

[Bittensor](https://bittensor.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Bittensor aims to revolutionize the field of decentralized AI by providing an alternative to the dominant, top-down approach of current technology giants. It is a platform that facilitates the creation of various decentralized commodity markets, or 'subnets', under a unified token system, functioning through Bittensor's blockchain. This allows for the interconnection and integration of these markets into a single computing infrastructure.

[Autonolas](https://www.autonolas.network/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Autonolas offers an open-source software stack designed to decentralize off-chain processes, particularly useful for DAO operations. This platform aims to unify off-chain code and consolidate existing data, computation, and transaction automation processes, thereby enhancing control and reducing dependency on individual humans and bots.

## Nonprofits

### Blockchain

[Blockchain Research Institute](https://www.blockchainresearchinstitute.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Blockchain Research Institute (BRI) is a global independent think tank dedicated to exploring and disseminating knowledge about the strategic implications of blockchain technology for business, government, and society. Co-founded by Don and Alex Tapscott, BRI is supported by a consortium of international corporations and government agencies, making it a prominent and collaborative center for blockchain research and knowledge-sharing​​.

[Blockchain Association](https://theblockchainassociation.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Blockchain Association serves as the collective voice of the cryptocurrency industry, with a mission to advance the future of crypto in the United States. It focuses on promoting the potential of blockchain technology and shaping policies to ensure its success. The association, comprised of nearly 100 members including sector-leading investors, companies, and projects, collaborates to support a pro-innovation national policy and regulatory framework for the crypto economy. Established in 2018 under the leadership of CEO Kristin Smith, the Blockchain Association annually reviews the challenges and accomplishments in the cryptocurrency industry, emphasizing its commitment to fostering a progressive and innovation-friendly national policy framework for the crypto economy​.

[Global Blockchain Business Council (GBBC)](https://gbbcouncil.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The Global Blockchain Business Council (GBBC) is the world's largest and leading industry association for the blockchain technology and digital assets community. Established in 2017 in Davos as a Swiss-based non-profit, GBBC comprises over 500 institutional members and 231 ambassadors from 109 jurisdictions and disciplines. The council is committed to advocating for the advancement and implementation of blockchain technology across various industries and sectors​.

[The American Blockchain and Cryptocurrency Association](https://abcaonline.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The American Blockchain and Cryptocurrency Association (ABCA) is a non-profit trade association dedicated to the educational and advocacy needs of the blockchain and cryptocurrency community. Representing a diverse group that includes crypto miners, investors, innovators, and entrepreneurs, ABCA focuses on shaping and advancing the interests of this rapidly evolving sector. The organization's initiatives and efforts are geared towards fostering a deeper understanding and more robust development within the blockchain and cryptocurrency fields​​​​.

### Cybersecurity

[Open Web Application Security Project (OWASP)](https://owasp.org/www-community/Threat_Modeling_Process)
<mark style="background-color: #FF7E24">**TLDR**</mark>  OWASP is a nonprofit foundation that works to improve the security of software. It's known for its community-led open source software projects, extensive documentation, guidelines, tools, and forums. The OWASP Top 10, a standard awareness document for developers and web application security, is one of their most well-known publications, listing the most critical security risks to web applications.

[National Institute of Standards and Technology (NIST)](https://www.nist.gov/)
<mark style="background-color: #FF7E24">**TLDR**</mark>  NIST is a non-regulatory federal agency within the U.S. Department of Commerce. Its mission is to promote innovation and industrial competitiveness by advancing measurement science, standards, and technology in ways that enhance economic security and improve our quality of life. NIST is also known for developing cybersecurity guidelines, frameworks, and standards to help organizations manage cybersecurity risks.

[Common Vulnerabilities and Exposures (CVE)](https://cve.mitre.org/)
<mark style="background-color: #FF7E24">**TLDR**</mark> CVE is a list of entries—each containing an identification number, a description, and at least one public reference—for publicly known cybersecurity vulnerabilities. The purpose of the CVE program is to facilitate the sharing of data and to alert users about vulnerabilities that have been identified in various products and services. This system provides a standardized method for assessing and sharing information on vulnerabilities and exposures, and helps to coordinate the response to security threats across platforms and organizations.

[CVE Numbering Authority (CNA)](https://www.cve.org/ProgramOrganization/CNAs)
<mark style="background-color: #FF7E24">**TLDR**</mark> CNAs are organizations from around the world that are authorized to assign CVE IDs to vulnerabilities affecting products within their distinct, agreed-upon scope, and to publish information about those vulnerabilities. CNAs include software vendors, open-source projects, coordination centers, bug bounty service providers, and research groups. They play a crucial role in the CVE program by ensuring that each identified vulnerability receives a unique identifier, which is essential for tracking and managing cybersecurity issues across various platforms and systems.

[NATIONAL VULNERABILITY DATABASE (NVD)](https://nvd.nist.gov/)
<mark style="background-color: #FF7E24">**TLDR**</mark> The NVD is a U.S. government repository of standards-based vulnerability management data. It provides information on vulnerabilities and exposures, and integrates all of the publicly available U.S. Government vulnerability resources and provides references to industry resources. It is maintained by the National Institute of Standards and Technology (NIST) and is a comprehensive database that includes security checklist references, security-related software flaws, misconfigurations, product names, and impact metrics.

[Homeland Infrastructure Foundation-Level Data (HIFLD)](https://hifld-geoplatform.opendata.arcgis.com/search?collection=Dataset)
<mark style="background-color: #FF7E24">**TLDR**</mark> HIFLD provides national foundation-level geospatial data within the open public domain that can be used to support community preparedness, resiliency, research, and more. HIFLD data is used for a variety of purposes including emergency response, national security-related efforts, and other applications where infrastructure data is vital. This initiative involves collaboration among different U.S. government agencies to enhance the quality and accessibility of critical infrastructure data to support homeland security and emergency management.

[VIRUSTOTAL](https://www.virustotal.com/gui/home/search)
<mark style="background-color: #FF7E24">**TLDR**</mark> VIRUSTOTAL is a website that provides a free service for scanning suspicious files and URLs to detect types of malware and automatically shares them with the security community. It uses a variety of antivirus engines and website scanners to check for viruses and other types of malware and malicious activity. Users can submit files or links for analysis and receive reports detailing the results from many different antivirus scanners. It's a valuable tool for security professionals and the general public to assess the safety of files and websites.

[EXPLOIT DATABASE](https://www.exploit-db.com/)
<mark style="background-color: #FF7E24">**TLDR**</mark> Exploit Database is a non-profit project that is provided as a public service by Offensive Security. The Exploit Database is an archive of public exploits and corresponding vulnerable software, developed for use by penetration testers and vulnerability researchers. Its purpose is to provide information about vulnerabilities and their exploits to help security professionals test the security of their systems and to promote the responsible disclosure of security vulnerabilities. The database includes entries for various types of exploits, including remote exploits, web application exploits, and local & privilege escalation exploits, among others.

## Reports

### Private Reports

- **TRM Labs** [Tackling Crypto Crime](https://uploads-ssl.webflow.com/6082dc5b67056233213587a4/6583048f70ed88922723499d_TRM_LE-Survey-Report_2023_V4.pdf)

- **ELLIPTIC** [How to Defend Your Business Against Crypto Crime](https://www.elliptic.co/hubfs/Elliptic_Guide_How_to_Defend_Your_Business_Against_Crypto_Crime.pdf?utm_campaign=Typologies%202023&utm_medium=email&_hsmi=265863773&_hsenc=p2ANqtz--p_2DJz-Rfhr1jtDNMY29u-jGfF-waFRugC8TaFVwMWFzitZQYV04UHbPAVD-3JHR4uk7BT6dAK_mppe2g3udD83DaqgyCUk0qQFdbPyLvMC79A2k&utm_content=265863773&utm_source=hs_automation)

- **ciphertrace** [Your go-to guide to the FATF’s crypto Travel Rule](https://ciphertrace.com/wp-content/uploads/2022/10/CipherTrace_Travel-Rule-Guide_FINAL.pdf)

- **ciphertrace** [Crypto Crimes & Anti-Money Laundering (AML) Report March 2023](https://ciphertrace.com/wp-content/uploads/2023/03/Ciphertrace-CAML-Report-Q3_FINAL.pdf)

- **Chainalysis** [The Chainalysis 2023 Geography of Cryptocurrency Report](https://go.chainalysis.com/rs/503-FAP-074/images/The%202023%20Geography%20of%20Cryptocurrency%20Report.pdf?version=0)

- **Chainalysis** [The 2023 Crypto Crime Report](https://hkibfa.io/wp-content/uploads/2023/02/Crypto_Crime_Report_2023.pdf)

- **Chainalysis** [The 2022 Crypto Crime Report](https://blockbr.com.br/wp-content/uploads/2022/06/2022-crypto-crime-report.pdf)

- **ciphertrace** [Crime and Anti-Money Laundering Report October 2022](https://ciphertrace.com/wp-content/uploads/2023/03/Ciphertrace-CAML-Report-Q3_FINAL.pdf)

- **CYBERSECURITY VENTURES** [Cyberwarfare In The C-Suite](https://cybersecurityventures.com/wp-content/uploads/2021/01/Cyberwarfare-2021-Report.pdf)

- **Apple** [The Continued Threat to Personal Data: Key Factors Behind the 2023 Increase](https://www.apple.com/newsroom/pdfs/The-Continued-Threat-to-Personal-Data-Key-Factors-Behind-the-2023-Increase.pdf)

- **Apple** [2022 The Rising Threat to Consumer Data in the Cloud](https://www.apple.com/newsroom/pdfs/The-Rising-Threat-to-Consumer-Data-in-the-Cloud.pdf)

### Government Reports

- **Federal Bureau of Investigation (FBI)** [Crime Data Explorer](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/home) <mark style="background-color: #FF7E24">**TLDR**</mark> This website aims to provide transparency, create easier access, and expand awareness of criminal, and noncriminal, law enforcement data sharing; improve accountability for law enforcement; and provide a foundation to help shape public policy with the result of a safer nation. Use the CDE to discover available data through visualizations, download data in .csv format, and other large data files.

- **Federal Bureau of Investigation (FBI)** [2022 INTERNET CRIME REPORT](https://www.ic3.gov/Media/PDF/AnnualReport/2022_IC3Report.pdf)

- **Federal Bureau of Investigation (FBI)** [2021 INTERNET CRIME REPORT](https://www.ic3.gov/Media/PDF/AnnualReport/2021_IC3Report.pdf)
  
- **Federal Trade Commission (FTC)** [Consumer Sentinel Network](https://www.ftc.gov/enforcement/consumer-sentinel-network/reports)<mark style="background-color: #FF7E24">**TLDR**</mark> Consumer Sentinel is a unique investigative cyber tool that gives members of the Consumer Sentinel Network access to millions of reports.

- **Federal Trade Commission (FTC)** [Consumer Sentinel Network Data Book 2022](https://www.ftc.gov/system/files/ftc_gov/pdf/CSN-Data-Book-2022.pdf)

- **United States Government Accountability Office (GAO)** [Reporting Mechanisms Vary, and Agencies Face Challenges in Developing Metrics](https://www.gao.gov/assets/gao-23-106080.pdf)

- **Congressional Research Service** [NIBRS Participation Rates and Federal Crime Data Quality](https://crsreports.congress.gov/product/pdf/IN/IN11936)

- **Congressional Research Service** [The National Incident-Based Reporting System (NIBRS): Benefits and Issues](https://crsreports.congress.gov/product/pdf/R/R46668)

## Regulation

### Cryptocurrency Regulation

- [Atlantic Council](https://www.atlanticcouncil.org/programs/geoeconomics-center/cryptoregulationtracker/) <mark style="background-color: #FF7E24">**TLDR**</mark> The Atlantic Council's Cryptocurrency Regulation Tracker is a comprehensive research project examining how 60 countries, including G20 members and those with high rates of cryptocurrency adoption, regulate cryptocurrencies. The research categorizes regulations based on legal status, tax policy, anti-money laundering and terrorist financing requirements, consumer protection rules, and licensing obligations. It provides insights into the legal status of cryptocurrencies across these countries, revealing varying degrees of regulation, ranging from full legality to partial or general bans, and highlights the rapid evolution and experimentation in cryptocurrency regulations worldwide.

- [IMF - Elements of Effective Policies for Crypto Assets](https://www.imf.org/en/Publications/Policy-Papers/Issues/2023/02/23/Elements-of-Effective-Policies-for-Crypto-Assets-530092) <mark style="background-color: #FF7E24">**TLDR**</mark> This paper addresses inquiries from Fund members regarding the emergence of crypto assets and related risks, providing a detailed overview and classification of crypto assets based on their characteristics, along with their perceived advantages and potential dangers. It proposes a policy framework targeting essential goals like macroeconomic and financial stability, consumer safety, and maintaining market and financial integrity. While outlining crucial components for achieving these goals, the paper also notes that the framework cannot rectify inherent design issues in cryptocurrencies, such as the absence of a reliable nominal anchor or issues with payments finality and scalability.

- [GLI - Blockchain & Cryptocurrency Laws and Regulations 2024](https://www.globallegalinsights.com/practice-areas/blockchain-laws-and-regulations/usa) <mark style="background-color: #FF7E24">**TLDR**</mark> The "Blockchain & Cryptocurrency Laws and Regulations" page on Global Legal Insights provides a detailed overview of the legal and regulatory environment for blockchain and cryptocurrency in the United States. It covers federal and state-level regulatory approaches, including the roles of various agencies like the SEC and CFTC, and differing state strategies ranging from supportive to restrictive measures.

- [Non-EU countries' regulations on crypto-assets and their potential implications for the EU](https://www.europarl.europa.eu/RegData/etudes/BRIE/2023/753930/EPRS_BRI(2023)753930_EN.pdf)

- [(EU) 2023/1114 on Markets in Crypto-Assets (“MiCAR” or “Act”)](https://eur-lex.europa.eu/legal-content/EN/TXT/PDF/?uri=CELEX:32023R1114)

### Cybersecurity Regulation

- [BETTER CYBERCRIME METRICS ACT](https://www.congress.gov/117/plaws/publ116/PLAW-117publ116.pdf) <mark style="background-color: #FF7E24">**TLDR**</mark> This law aims to establish improved cybercrime reporting mechanisms and develop a comprehensive taxonomy for categorizing various types of cybercrime and cyber-enabled crime, enhancing the United States' capability to understand and address these growing threats.

- [Federal Trade Commission Act](https://www.ftc.gov/legal-library/browse/statutes/federal-trade-commission-act) <mark style="background-color: #FF7E24">**TLDR**</mark> This law prohibits deceptive acts and practices in business, including those related to data security.

- [Gramm-Leach-Bliley Act (GLB)](https://www.ftc.gov/business-guidance/privacy-security/gramm-leach-bliley-act) <mark style="background-color: #FF7E24">**TLDR**</mark> This law requires companies to protect the customer data they collect.

- [Cybersecurity Information Sharing Act (CISA)](https://www.congress.gov/event/117th-congress/house-event/114172/text?s=1&r=84) <mark style="background-color: #FF7E24">**TLDR**</mark> This law allows companies to monitor network traffic, including taking defensive measures on their own systems.  And, it encourages the sharing of cyber-threat information between companies and with the government.

- [Health Insurance Portability and Accountability Act (“HIPAA”)](https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html) <mark style="background-color: #FF7E24">**TLDR**</mark> This law includes cybersecurity requirements applicable to protected health information in the possession of certain “covered entities” and their “business associates”.

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


[**Top**](#research)


