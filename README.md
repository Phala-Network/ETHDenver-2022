# Phala Workshop for ETHDenver 2022

![](assets/banner.jpeg)

Welcome to Phala's Workshop for ETHDenver 2022!
This repo is meant to provide the useful resources for your workshop experience.

## Intro: The Web3 infrastructure beyond smart contract
**Subtitle: Web3 Infrastructure: Send HTTPS requests in Fat Contract**

The development of Web3 and Metaverse raises new requirements on the blockchain infrastructure. A trend of running heavy-weight applications like real-time rendering and game servers on decentralized computing services is emerging.

In this workshop, we show how Phala provides trustless computing service of over tens of thousands of nodes, and present the Fat Contract which intends to serve compute-intensive and low-latency applications which have never been executed on-chain. With its Internet access ability, you are free to utilize any existing Web2 services with tens of lines of contract code, making it a perfect choice to connect the Web2 and Web3 world.

## Resources for this workshop

- If you have any questions, visit [here](https://bit.ly/3GTDhhs) to post and get them answered
- [Event link](https://ethdenver.sched.com/event/vBYq/the-web3-infrastructure-beyond-smart-contract)
- [Rendering demo codebase](https://github.com/Phala-Network/blender-contract)
- [Workshop codebase](https://github.com/Phala-Network/fat-contract-workshop/tree/ethdenver-2022)
  - To interact with our Demo Fat Contract and get POAP
    - Frontend: https://phala-js-sdk-example.netlify.app/
    - Contract ID: `0x6cad353bad2232931ae7878b2013439bfca2576cd0c0d2c72093dc4c63c68568`
    - Contract's `metadata.json`: https://bit.ly/3uMUvdZ
  - Use our Testnet to deploy your own contract
    - Substate endpoints: `wss://poc5.phala.network/ws` / `wss://poc5-2.phala.network/ws`
    - Secure Worker endpoints: https://poc5.phala.network/tee-api-{n} / https://poc5-2.phala.network/tee-api-{n} with (n = 1 to 5)

## 🎉 After-workshop Hackathon

### 📅 Dates

- Launch Event: February 15th 1:00 pm MST, right after our ETHDenver Workshop
- Duration: Two weeks
- End: March 1st 1:00 pm MST
- Prize distribution period: up to one week after the end, on March 15th

### ✍️ Registration

There is no need to register, just come to play!

### 💰 Prize

| Prize ($ in PHA)                                                    | Winners |
| ------------------------------------------------------------------- | ------- |
| $100 + [Phala World](https://www.phalaworld.com/) NFT               | 1       |
| $100 + Whitelist for [Phala World](https://www.phalaworld.com/) NFT | 4       |
| $100                                                                | 5       |


### 🏁 Challenge

The submission is not limited, just use your best imagination to find the most interesting application scenarios of Fat Contract.

While we really have some ideas for reference:
- One important features of Fat Contract is its low-latency and the scale underlying computing power, making it a good replacement as Metaverse/game backend and other compute-intensive tasks which now can only be executed on centralized cloud services;
- Another feature is the HTTP request ability. Compared with existing Oracle which can only introduce Web2 data to Web3 world, Fat Contract is able to affect the Web2 with their HTTP APIs. This facilitates applications like decentralized [IFTTT](https://ifttt.com/explore/new_to_ifttt) that connects multiple Web2 and Web3 services.

Also, you can refer to the [Advanced Submissions](https://github.com/Phala-Network/Encode-Hackathon-2021/issues/21) in our previous hackathon.

### 📌 Submission requirements

1. Submit a brief introduction to the usage of your DApp
2. Take a screenshot of your frontend to show your unique feature
3. Send the screenshots and share your feeling on Twitter
4. Join our [Discord server](https://discord.gg/zQKNGv4) and submit the link to your tweet in the **#hackathon** chat room.

You can submit through creating a new issue in this repo following our [template](https://github.com/Phala-Network/ETHDenver-2022/issues/1).

### 💬 Chat and Support

Meet friends and the Phala team at our [Official Discord Server](https://discord.gg/nJaehCD98Y)!

If you have any questions about the hackathon, Phala development, or you want to report a bug, we have a **#hackathon** group dedicated to that.

## About Phala Network

[Phala Network](https://phala.network/) is a Web3.0 computing cloud that supports data privacy while remaining trustless. Unlike centralized cloud service, Phala doesn’t own any server or data center. Anyone can provide permissionless servers into Phala Network, and because of a clever combination of blockchain and secure enclave, we can make sure the servers can’t be evil even when they are in an edge network situation. Together, this creates the infrastructure for a powerful, secure, and scalable trustless computing cloud.

Some useful resources include:
- [Main page](https://phala.network/)
- [Phala Wiki](https://wiki.phala.network/en-us/general/phala-network/01-phala-network/) about Phala applications, mining and Fat Contract development
- [Discord channel](https://discord.gg/myBmQu5) and [Forum](https://forum.phala.network/) to discuss with us and our community members directly
- [Medium](https://medium.com/phala-network) and [Twitter](https://twitter.com/PhalaNetwork) to learn about our latest progress
