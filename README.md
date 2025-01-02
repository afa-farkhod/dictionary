# Dictionary
Dictionary - saves useful terminology

- `AVS` - stands for Actively Validated Service in blockchain. AVS is a new concept in crypto-economic security that allows developers to use Ethereum's economic security infrastructure to create new AVSs. EigenLayer is a protocol built on Ethereum that uses restaking to create AVSs.
- [Benchmarking](https://www.lucidchart.com/blog/8-steps-of-the-benchmarking-process) - the process of measuring and comparing the performance, quality, or efficiency of a product, service, or process against a standard or best practice, often within the same industry. The goal is to identify areas of improvement and set goals for achieving better performance.
- `Blob storage` is a type of cloud storage that stores large amounts of unstructured data in non-hierarchical storage areas. The term "blob" is short for "binary large object". 
- `CI/CD pipeline` - continuous integration and continuous delivery pipeline, is a series of steps that automate the process of building, testing, and releasing software
- `Canvas` is a course management system (LMS - Learning Management System) that helps teachers and students with online learning and teaching
- [cast](https://www.raycast.com/merklefruit/foundry-cast-cli) - is a command-line tool that is part of Foundry — development framework for Ethereum and other EVM-compatible blockchains. It provides a lightweight, efficient way to interact with smart contracts, send transactions and query on-chain data directly from your terminal.
   ```
   # cast is part of Foundry, so you’ll need to install Foundry first:
   curl -L https://foundry.paradigm.xyz | bash
   foundryup
   
   # check installation
   cast --version
   ```
- [CEX vs DEX](https://www.bitpay.com/blog/cex-vs-dex) -  `CEX`(Centralized Exchange) involves trusting a third-party custodian with your funds and typically provides a user-friendly experience with higher liquidity and trading features. A `DEX`(Decentralized Exchange) allows you to remain in full control of your private keys and funds, emphasizing decentralization and security, though it may involve a steeper learning curve and, in some cases, less liquidity
- [Digital Nomad](https://en.wikipedia.org/wiki/Digital_nomad) -  people who travel freely while working remotely using technology and the internet.[1] Such people generally have minimal material possessions and work remotely in temporary housing, hotels, cafes, public libraries, co-working spaces or recreational vehicles, using Wi-Fi, smartphones or mobile hotspots to access the Internet
- `EVM` - The Ethereum Virtual Machine (EVM) is a decentralized computation engine that executes smart contracts on the Ethereum network. It is a crucial component of Ethereum's infrastructure, enabling the execution of code exactly as intended.
- [Fail2Ban](https://siddhivinayak-sk.medium.com/prevent-your-website-from-brute-force-attacks-use-fail2ban-to-block-malicious-clients-92b15b5ae4ec) - a tool for scanning log files, detecting suspicious activity such as too many failed authentication attempts, and blocking potentially malicious IP addresses. This free service helps protect Linux machines from brute forcing and other automated attacks.
- [Gemini](https://blog.google/technology/ai/google-gemini-ai/#sundar-note) is Google's AI model that uses natural language processing (NLP) to understand and respond to user inputs.
- [Gamma](https://gamma.app/) - AI is an artificial intelligence-powered tool that allows users to quickly generate visually appealing presentations, documents, and webpages by simply inputting text, essentially eliminating the need for extensive design knowledge and significantly streamlining the content creation process.
- [Intel SGX](https://www.intel.com/content/www/us/en/products/docs/accelerator-engines/software-guard-extensions.html) - The Intel Software Guard Extensions (SGX) is a feature that uses hardware-level encryption to protect your sensitive data from security breaches.
- [IaC](https://aws.amazon.com/what-is/iac/) - Infrastructure as Code is a DevOps practice that uses code to provision and manage an organization's IT infrastructure. IaC allows developers to automate tasks like setting up, updating, and maintaining infrastructure, so they can focus on building applications.  
- `IP address`:
  - `Private` - private IP address is only used within a local network and is not visible to the wider internet
      ```
      # output of following command, look for inet and except public ip address, is the private ip address
      ifconfig
      ```
  - `Public` - public IP address is unique to the entire internet and allows your device to be identified and accessed globally
      ```
      # result of following command is the public ip address
      curl -4 ifconfig.me
      ```
  - `127.0.0.1` - is the loop back ip adress, used by the system to communicate with itself
- [Jenkins](https://www.jenkins.io/) is an open-source automation server used for continuous integration (CI) and continuous delivery (CD) in software development. It allows developers to automate the building, testing and deployment of applications, making the development process more efficient and reliable.
- [Keyless Wallet](https://selfchain.xyz/keyless-wallets) - The main idea is the splitting of a random seed phrases into multiple parts. The initial setup uses a 2-of-3 shares: Personal Share, Remote Share and Recovery Share.
- [Light Node vs Full Node](https://www.ledger.com/academy/glossary/light-node) - `Light Node` is typically smaller in size and contain only partial information about the network. `Full Node` contains a complete copy of the network.
- [MPC](https://en.wikipedia.org/wiki/Secure_multi-party_computation) - Multi-party computation is a cryptographic technique that allows multiple parties to collaboratively compute a result on their private data without revealing the details of their individual inputs to each other, essentially enabling secure joint calculations while maintaining data privacy among participants involved. 
- `Object Storage` -  is a data storage architecture that stores data in units called objects, which are bundled with metadata and a unique identifier. Object storage is often used to store large amounts of unstructured data, such as photos, videos, email and sensor data. Object storage is commonly used for backups, archiving, cloud-native applications, big data and more.
- [Omnichain](https://medium.com/@orderlynetwork/what-is-omnichain-in-crypto-a-beginners-guide-4d81c89afb11) - refers to a comprehensive approach that aims to unite various blockchain networks into a cohesive and interoperable ecosystem.
- [PSS](https://forum.cosmos.network/t/chips-discussion-phase-partial-set-security-updated/11775) - Partial Set Security refers to a security model within blockchain networks, particularly in the Cosmos ecosystem, where only a subset of validators from a "provider chain" (like the Cosmos Hub) are required to secure a "consumer chain", allowing for more flexible security allocation and scalability compared to the traditional model where all validators must secure every chain.
- [Pinpoint](https://pinpoint-apm.gitbook.io/pinpoint) - is an APM (Application Performance Management) tool for large-scale distributed systems written in Java / PHP. Inspired by Dapper, `Pinpoint` provides a solution to help analyze the overall structure of the system and how components within them are interconnected by tracing transactions across distributed applications.
- `Synchronous vs Asynchronous` -  Synchronous means happening at the same time, while asynchronous means not happening at the same time. Synchronous operations are performed one at a time, while asynchronous operations can run independently and at the same time. 
- `Software Engineer` -  generally has a broader scope, focusing on the overall system design, architecture, and technical considerations of a software project.
- `Software Developer` - primarily focuses on building specific features and applications using code, typically working within a defined design framework created by engineers
- [Sora](https://www.usatoday.com/story/tech/2024/12/10/sora-openai-chatgpt-video-generator-price-how-works/76887223007/) - a text-to-video generator created by OpenAI, the company that developed ChatGPT. Sora uses artificial intelligence to create short videos from written prompts or existing images. It can generate complex scenes with multiple characters and specific details.
- `web3signer` - is an open-source remote signing service that allows validators to securely sign blocks and attestations on multiple platforms. Web3Signer can sign on Ethereum-1 and 2 and Filecoin. Web3Signer allows a  Validator Client (VC) to outsource the signing of messages to a remote server.
- [Zabbix](https://www.zabbix.com/) - is an open-source monitoring tool that monitors IT infrastructure components, including: Networks, Servers, Virtual machines (VMs), and Cloud services.
