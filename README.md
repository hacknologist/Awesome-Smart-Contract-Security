# Awesome-Smart-Contract-Security ![awesome](https://awesome.re/badge.svg)
![Screenshot](img/SmartContract.png)

 


# Table of Contents
- [Blog](#blog)
- [Paper](#paper)
- [Books](#books)
- [Course](#course)
- [Tools](#tools)
  * [Visualization](#Visualization)
  * [Verification](#Verification)
  * [Linters](#Linters)
  * [BugHunting](#BugHunting)

- [Labs](#labs)
- [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
- [Talks](#talks)
- [Misc](#misc)
- [Bug Bounty & Writeups](#Bug-Bounty-&-Writeup)
- [Podcasts](#Podcasts)
- [Cheat Sheet](#Cheat-Sheet)
- [Checklist](#Checklist)
- [Bug Bounty Report](#Bug-Bounty-Report)

# Blog

* [Solidity Security: Comprehensive list of known attack vectors](https://blog.sigmaprime.io/solidity-security.html)
* [Use cryptography in mobile apps the right way](https://blog.oversecured.com/Use-cryptography-in-mobile-apps-the-right-way/)
* [Subzero is an HSM-backed method for cold storage of Bitcoin developed by Square](https://medium.com/square-corner-blog/open-sourcing-subzero-ee9e3e071827) 

# Paper
* [AndrODet: An adaptive Android obfuscation detector](https://arxiv.org/pdf/1910.06192.pdf)
* [GEOST BOTNET - the discovery story of a new Android banking trojan](http://public.avast.com/research/VB2019-Garcia-etal.pdf)
* [Dual-Level Android Malware Detection](https://www.mdpi.com/2073-8994/12/7/1128)
* [An Investigation of the Android Kernel Patch Ecosystem](https://www.usenix.org/conference/usenixsecurity21/presentation/zhang)
   
# Books

 * [SEI CERT Android Secure Coding Standard](https://www.securecoding.cert.org/confluence/display/android/Android+Secure+Coding+Standard)
 * [Android Security Internals](https://www.oreilly.com/library/view/android-security-internals/9781457185496/)

# Course

* [SEC575: Mobile Device Security and Ethical Hacking](https://www.sans.org/cyber-security-courses/mobile-device-security-ethical-hacking/)
# Tools
### Visualization

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - A graphical EVM debugger. Displays the entire program control flow graph.
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print the inheritance graph of a smart contract
* [Solgraph](https://github.com/raineorshine/solgraph) - Generates DOT graphs with function control flow of a solidity contract
* [Surya](https://github.com/ConsenSys/surya) - Generates various visual outputs of function call graphs
* [sol-function-profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler

### Verification 

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Linters

* [Remix](https://remix.ethereum.org/) - Browser-based Solidity IDE with linting features
* [SmarrtCheck](https://tool.smartdec.net/) - A linter for Solidity and Vyper that checks code for security issues and bad practices.
* [Solhint](https://github.com/protofire/solhint) - Linter for both security and style-guide validations. It strictly adheres to the [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html).
* [Solium](https://github.com/duaraghav8/Solium) - Linter for both security and style-guide validations. Does not strictly adhere to the Solidity Style Guide.
### BugHunting

* [Echidna](https://github.com/trailofbits/echidna) - Fuzzer for Ethereum smart contracts. Uses property testing to generate malicious inputs that break smart contracts.
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for Ethereum smart contracts that includes detectors for common security flaws
* [Mythril OSS](https://github.com/ConsenSys/mythril/) - Open-source security analysis tool for Ethereum smart contracts built around detector modules
* [Securify](https://github.com/eth-sri/securify) - Static analysis tool from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework, written in Python, with detectors for many common Solidity issues

# Labs

* [Damn-Vulnerable-Bank](https://github.com/rewanth1997/Damn-Vulnerable-Bank)  
* [OVAA (Oversecured Vulnerable Android App)](https://github.com/oversecured/ovaa)

# Capture the Flag and Wargames

* [Capture the Ether](https://capturetheether.com/)  
* [The Ethernaut](https://ethernaut.openzeppelin.com/)  
* [Etherhack](https://etherhack.positive.com/)  
* [Security Innovation Blockchain CTF](https://blockchain-ctf.securityinnovation.com/)  
* [Ciphershastra CTF](https://ciphershastra.com/)  
* [Defi Hack](https://www.defihack.xyz/)  
* [Gacha Lab (BSC Testnet)](https://gachalab.inspex.co/)
# Talks
  

| Title | Conference | Year |
| --- | --- | --- |
|[Smart Contract Security: a Practitioners’ Perspective](https://conf.researchr.org/details/icse-2021/icse-2021-papers/12/Smart-Contract-Security-a-Practitioners-Perspective) | ICSE 2021 |2021|
| [Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf) | OWASP AppSec | 2018 |
| [Blockchain Autopsies - Analyzing Smart Contract Deaths](https://github.com/trailofbits/publications/tree/master/presentations/Blockchain%20Autopsies%20-%20Analyzing%20Smart%20Contract%20Deaths) | Blackhat USA | 2018 |
| [Rattle - an EVM binary analysis framework](https://www.trailofbits.com/presentations/rattle/) | reCON | 2018 |
| [Blackhat Ethereum](https://github.com/trailofbits/publications/blob/master/presentations/Blackhat%20Ethereum) | CanSecWest | 2018 |
| [Smashing Ethereum Smart Contracts for Fun and Profit](https://github.com/b-mueller/smashing-smart-contracts) | HITB Amsterdam | 2018 |
| [Automatic Bug Finding for the Blockchain](https://github.com/trailofbits/publications/blob/master/presentations/Automatic%20bugfinding%20for%20the%20blockchain) | EkoParty | 2017 |
# Misc

* [A guide to smart contract security best practices](https://github.com/ConsenSys/smart-contract-best-practices)    
* [Decentralized Application Security Project (or DASP) Top 10](https://www.dasp.co/)
* [Solidity Security Considerations](https://docs.soliditylang.org/en/latest/security-considerations.html)
* [A Collection of Vulnerabilities in ERC20 Smart Contracts](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
# Bug Bounty & Writeup

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - Writeup for a vulnerable ERC20 from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - Writeup for EtherHack CTF challenges.
* [PolySwarm Smart Contract Hacking Challenge Writeup](https://raz0r.name/writeups/polyswarm-smart-contract-hacking-challenge-writeup/) - Demonstrates advanced use of Manticore


# Podcasts

* [CoinSec Podcast](https://coinsecpodcast.com/)
* [The Smartest Contract](http://www.thesmartestcontract.com/)
* [Zero Knowledge](http://www.zeroknowledge.fm/)

# Cheat Sheet 
* [Solidity Cheat Sheet](https://intellipaat.com/blog/tutorial/blockchain-tutorial/solidity-cheat-sheet/)
* [Solidity Cheatsheet and Best practices](https://github.com/manojpramesh/solidity-cheatsheet)
* [Ethereum Cheat Sheet](https://intellipaat.com/blog/tutorial/blockchain-tutorial/ethereum-cheat-sheet/)
* [The Ultimate Blockchain Cheat Sheet](https://101blockchains.com/blockchain-cheat-sheet/)
# Checklist
* [Android Pentesting Checklist](https://mobexler.com/checklist.htm#android)
* [OWASP Mobile Security Testing Guide (MSTG)](https://github.com/OWASP/owasp-mstg/tree/master/Checklists)
* [OWASP Mobile Application Security Verification Standard (MASVS)](https://github.com/OWASP/owasp-masvs)

# Bug Bounty Report 
* [List of Android Hackerone disclosed reports](https://github.com/B3nac/Android-Reports-and-Resources)
* [How to report security issues](https://source.android.com/security/overview/updates-resources#report-issues)
