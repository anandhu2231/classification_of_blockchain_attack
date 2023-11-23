<h1 align="left">Classify Attacks Based on Blockchain Components</h1>

###

<p align="left"></p>

###

<h2 align="left">Overview</h2>

###

* This project aims to categorize attacks within blockchain networks, focusing on individual blockchain components and providing a comprehensive framework for identifying and analyzing these attacks.
* Wallet, Consensus Mechanism, Mining pool, Peer-to-Peer network, and Smart Contracts are the blockchain components.
* The primary purpose is to give a precise taxonomy that categorizes various attack paths, allowing for a better understanding of risks and vulnerabilities in the context of blockchain components.

###

<div align="left">
</div>

###

<h2 align="left">Problem Statement</h2>

###


* Blockchain technology is intended to be safe and resistant to unauthorized changes, however it is not immune to certain sorts of attacks.
* Attacks on blockchain, such as 51% attacks and smart contract vulnerabilities, can erode trust in cryptocurrencies and financial products, potentially reducing their adoption. 
* This review paper will investigate blockchain component attacks, examining weaknesses and security challenges in important areas like as consensus procedures, smart contracts, cryptography, and network protocols.
* Among the main components that will be focused on are consensus mechanisms, mining, mining pools, peer-to-peer networks, ledgers, wallets, networks and smart contracts.

###

<h2 align="left"></h2>

###

<h2 align="left">Novelty</h2>

###


* Attack categorization is important because it offers a formal framework for understanding and solving cybersecurity threats. 
* The previous papers are classified attack based on Core or Client Oriented,  Physical Attacks,Network Attacks, Software Attacks and Industrial Internet of Things.
* Previous research publications have addressed blockchain attacks, but they have often categorised just a small fraction of these attacks.
* Attack classification based on blockchain components enables businesses to more precisely allocate resources and deploy security measures, thereby improving the protection of specific digital assets.

###

<h2 align="left">Literature Review</h2>

###

* Title: Attacks on blockchain 
  * Year: 2019 
  * Author: Shubhani Aggarwal and Neeraj Kumar
  * Classification: Based on Blockchain Components 
  * Classes: Consensus and ledger-Based Attacks, Peer-to-Peer Network, Smart Contract, Wallet-based Attacks

* Title: Review of Blockchain Technology Vulnerabilities and Blockchain-System Attacks  
  * Year: 2019 
  * Author:  A. Averin and O. Averina 
  * Classification: No Classification
  * Classes: No Classes

* Title : 6G technology and taxonomy of attacks on blockchain technology
  * Year : 2022 
  * Author :  Firdous Kausar  et. al
  * Classification : Approaches within the blockchain ecosystem
  * Classes : Core-oriented and Client-oriented
  
* Title : A Survey on Consensus Protocols and Attacks on Blockchain Technology
  * Year : 2023
  * Author : Dr. Abhishek Guru et. al
  * Classification : No Classification
  * Classes : No Classes
 
* Title : A Comprehensive Survey on Attacks, Security Issues and Blockchain Solutions for IoT and IIoT.
  * Year : 2020
  * Author :  Jayasree Sengupta et. al
  * Classification : Target and Method of Attack
  * Classes : Physical Attacks,Network Attacks, Software Attacks, Industrial Internet of Things (IIoT)

###

<h2 align="left">Attacks on Blockchain</h2>

###

<h3 align="left">Peer-to-Peer Network-based Attacks</h3>

###

 1.  Transaction malleability Attack
 2.  Liveness Attack
 3.  Spatial partitioning attack
 4.  BGP hijacking attack
 5.  Stress testing attack
 6.  Memory pool flooding
 7.  Block withholding attack
 8.  DNS attack
 9.  Eclipse attack
 10.  Sybil attack
 11.  Time-jacking
 12.  Eclipse attack
 13.  Distributed denial of service (DDoS) attack
 14.  Memory pool flooding attack
 15.  Routing attack
 16.  Bribery attack

###

<h3 align="left">Smart Contract-based Attacks</h3>

###


 1. DAO Attack - Decentralized Autonomous Organization Attack
 2.  Race Attack
 3.  Code Injection

###

<h3 align="left">Wallets-based Attacks</h3>

###

 1.  Parity multi-sig wallet Attack 
 2.  Wallet Thief Attack
 3.  Brute Force attack
 4.  Social Engineering Attack
 5.  Phishing Attack
 6.  XSS Attack

###

<h3 align="left">Mining Pool Attacks</h3>

###

 1. Block WIthholding Attack
 2. Selfish Mining Attack
 3. Fork After Withholding Attack
 4. Bribery Attack

###

<h3 align="left">Consensus Mechanism and ledger-based Attacks</h3>

###

 1.  Finney Attack
 2.  51% Attack
 3.  Consensus delay Attack 
 4.  Time-jacking Attack
 5.  Selfish Mining Attack
 6.  Block Withholding Attack
 7.  Attack by accumulating the coin age
 8.  Race Attack
 9.  Block Discarding Attack
 10.  Ballot Stuffing Attack</p>

###

<h3 align="left">Transaction Verification Attacks</h3>

###

 1.  Double spending Attack
 2.  Time delay Attack
 3.  Dust Attack
 4.  Hacking Hash Functions
 5.  Message Spoofing Attack

###

<h1 align="left">Plan for Future Experiments</h1>

###

<h2 align="left">Security testing on Blockchain Technology</h2>

###

<h3 align="left">Step 1: Setup a Blockchain with multiple nodes(3-4).</h3>

###

1.  Download and Install Multichain from https://www.multichain.com/download-community/
2.  Create a new blockchain called <chain-name> based on MultiChain. 
<pre id="code-to-copy">$ multichain-util create</pre>
3.  Start the blockchain.
<pre id="code-to-copy">$ multichaind <chain-name> -daemon</pre>
4.  Add new nodes using the command.
<pre id="code-to-copy">$ multichaind chain_name@ip_node1:port -daemon</pre>

###

<h3 align="left">Step 2: Setting the Attack vectors for testing</h3>

###

<h4 align="left">1. Code Review for smart contacts.</h4>

###

<p align="left">In the context of smart contracts, an overflow attack happens when arithmetic operations go beyond the variable type's maximum size, resulting in the value wrapping around to an unexpected value. Overflow attacks can lead to unauthorized actions, such as transferring out more tokens than intended in a cryptocurrency contract.</p>

###

<h4 align="left">2. Test Network Security for Peer to Peer Network</h4>

###

Security testing in Networks helps in identifying potential network vulnerabilities, such as loopholes in data transfer protocols or peer discovery mechanisms, that an attacker might exploit.  By identifying and mitigating security vulnerabilities, the risk of financial loss due to fraud, theft, or other malicious activities is significantly reduced. 
 * Stress Testing - evaluating the network's capacity to manage heavy traffic or loads.
 * Node Security Assessments - testing each network node's security separately.

###

<h4 align="left">3. Web Attacks on Blockchain Wallets</h4>

###

<p align="left">Individually testing network node security attacks on blockchain wallets pose a significant security risk because these wallets frequently store valuable digital assets such as cryptocurrencies. Understanding the nature of these attacks and the mitigation strategies is critical for both users and developers.</p>

###

* Phishing Attacks
* Man-in-the-Middle (MitM) Attacks
* Cross-Site Scripting (XSS) Attacks
* SQL Injection
* Cross-Site Request Forgery (CSRF)
* Session Hijacking

###
