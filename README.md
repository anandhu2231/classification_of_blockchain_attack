<h1 align="left">Classify Attacks Based on Blockchain Components</h1>

###

<p align="left"></p>

###

<h2 align="left">Overview</h2>

###

<p align="left">- This project aims to categorize attacks within blockchain networks, focusing on individual blockchain components and providing a comprehensive framework for identifying and analyzing these attacks.<br><br>- Wallet, Consensus Mechanism, Mining pool, Peer-to-Peer network, and Smart Contracts are the blockchain components.<br><br>- The primary purpose is to give a precise taxonomy that categorizes various attack paths, allowing for a better understanding of risks and vulnerabilities in the context of blockchain components.</p>

###

<div align="left">
</div>

###

<h2 align="left">Problem Statement</h2>

###

<p align="left">- 
* Blockchain technology is intended to be safe and resistant to unauthorized changes, however it is not immune to certain sorts of attacks.
* Attacks on blockchain, such as 51% attacks and smart contract vulnerabilities, can erode trust in cryptocurrencies and financial products, potentially reducing their adoption. 
* This review paper will investigate blockchain component attacks, examining weaknesses and security challenges in important areas like as consensus procedures, smart contracts, cryptography, and network protocols.
* Among the main components that will be focused on are consensus mechanisms, mining, mining pools, peer-to-peer networks, ledgers, wallets, networks and smart contracts.</p>

###

<h2 align="left"></h2>

###

<h2 align="left">Novelty</h2>

###

<p align="left">
* Attack categorization is important because it offers a formal framework for understanding and solving cybersecurity threats. 
* The previous papers are classified attack based on Core or Client Oriented,  Physical Attacks,Network Attacks, Software Attacks and Industrial Internet of Things.
* Previous research publications have addressed blockchain attacks, but they have often categorised just a small fraction of these attacks.
* Attack classification based on blockchain components enables businesses to more precisely allocate resources and deploy security measures, thereby improving the protection of specific digital assets.</p>

###

<h2 align="left">Literature Review</h2>

###

<p align="left">Title: Attacks on blockchain <br>Year: 2019 <br>Author: Shubhani Aggarwal and Neeraj Kumar <br>Classification: Based on Blockchain Components <br>Classes: Consensus and ledger-Based Attacks, Peer-to-Peer Network, Smart Contract, Wallet-based Attacks <br><br>Title: Review of Blockchain Technology Vulnerabilities and Blockchain-System Attacks  <br>Year: 2019 <br>Author:  A. Averin and O. Averina <br>Classification: No Classification <br>Classes: No Classes <br><br>Title : 6G technology and taxonomy of attacks on blockchain technology<br>Year : 2022 <br>Author :  Firdous Kausar  et. al<br>Classification : Approaches within the blockchain ecosystem<br>Classes : Core-oriented and Client-oriented<br><br>Title : A Survey on Consensus Protocols and Attacks on Blockchain Technology<br>Year : 2023<br>Author : Dr. Abhishek Guru et. al<br>Classification : No Classification<br>Classes : No Classes<br><br>Title : A Comprehensive Survey on Attacks, Security Issues and Blockchain Solutions for IoT and IIoT.<br>Year : 2020<br>Author :  Jayasree Sengupta et. al<br>Classification : Target and Method of Attack<br>Classes : Physical Attacks,Network Attacks, Software Attacks, Industrial Internet of Things (IIoT)</p>

###

<h2 align="left">Attacks on Blockchain</h2>

###

<h3 align="left">Peer-to-Peer Network-based Attacks</h3>

###

<p align="left">1.  Transaction malleability Attack<br>2.  Liveness Attack<br>3.  Spatial partitioning attack<br>4.  BGP hijacking attack<br>5.  Stress testing attack<br>6.  Memory pool flooding<br>7.  Block withholding attack<br>8.  DNS attack <br>9.  Eclipse attack<br>10.  Sybil attack <br>11.  Time-jacking<br>12.  Eclipse attack<br>13.  Distributed denial of service (DDoS) attack<br>14.  Memory pool flooding attack<br>15.  Routing attack<br>16.  Bribery attack</p>

###

<h3 align="left">Smart Contract-based Attacks</h3>

###

<p align="left">1.  DAO attack - Decentralized Autonomous Organization Attack<br>2.  Race attack<br>3.  Code injection</p>

###

<h3 align="left">Wallets-based Attacks</h3>

###

<p align="left">1.  Parity multi-sig wallet Attack <br>2.  Wallet Thief Attack<br>3.  Brute Force attack<br>4.  Social Engineering Attack<br>5.  Phishing Attack<br>6.  XSS Attack</p>

###

<h3 align="left">Mining Pool Attacks</h3>

###

<p align="left">1. Block WIthholding Attack<br>2. Selfish Mining Attack<br>3. Fork After Withholding Attack<br>4. Bribery Attack</p>

###

<h3 align="left">Consensus Mechanism and ledger-based Attacks</h3>

###

<p align="left">1.  Finney Attack<br>2.  51% Attack<br>3.  Consensus delay Attack <br>4.  Time-jacking Attack<br>5.  Selfish Mining Attack<br>6.  Block Withholding Attack<br>7.  Attack by accumulating the coin age<br>8.  Race Attack<br>9.  Block Discarding Attack <br>10.  Ballot Stuffing Attack</p>

###

<h3 align="left">Transaction Verification Attacks</h3>

###

<p align="left">1.  Double spending Attack<br>2.  Time delay Attack<br>3.  Dust Attack<br>4.  Hacking Hash Functions<br>5.  Message Spoofing Attack</p>

###

<h1 align="left">Plan for Future Experiments</h1>

###

<h2 align="left">Security testing on Blockchain Technology</h2>

###

<h3 align="left">Step 1: Setup a Blockchain with multiple nodes(3-4).</h3>

###

<p align="left">1.  Download and Install Multichain from - https://www.multichain.com/download-community/ .<br>2.  Create a new blockchain called <chain-name> based on MultiChain. - $ multichain-util create <chain-name>.<br>3.   Start the blockchain - $ multichaind <chain-name> -daemon<br>4.   Add new nodes using the command - $ multichaind chain_name@ip_node1:port -daemon</p>

###

<h3 align="left">Step 2: Setting the Attack vectors for testing</h3>

###

<h4 align="left">1. Code Review for smart contacts.</h4>

###

<p align="left">In the context of smart contracts, an overflow attack happens when arithmetic operations go beyond the variable type's maximum size, resulting in the value wrapping around to an unexpected value. Overflow attacks can lead to unauthorized actions, such as transferring out more tokens than intended in a cryptocurrency contract.</p>

###

<h4 align="left">2. Test Network Security for Peer to Peer Network</h4>

###

<p align="left">Security testing in Networks helps in identifying potential network vulnerabilities, such as loopholes in data transfer protocols or peer discovery mechanisms, that an attacker might exploit.  By identifying and mitigating security vulnerabilities, the risk of financial loss due to fraud, theft, or other malicious activities is significantly reduced.<br><br>- Stress Testing - evaluating the network's capacity to manage heavy traffic or loads.<br><br>- Node Security Assessments - testing each network node's security separately.</p>

###

<h4 align="left">3. Web Attacks on Blockchain Wallets</h4>

###

<p align="left">Individually testing network node security attacks on blockchain wallets pose a significant security risk because these wallets frequently store valuable digital assets such as cryptocurrencies. Understanding the nature of these attacks and the mitigation strategies is critical for both users and developers.</p>

###

<p align="left">Phishing Attacks<br>Man-in-the-Middle (MitM) Attacks<br>Cross-Site Scripting (XSS) Attacks<br>SQL Injection<br>Cross-Site Request Forgery (CSRF)<br>Session Hijacking</p>

###
