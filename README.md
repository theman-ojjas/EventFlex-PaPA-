# EventFlex - PaPA(Pay Per Attendance Protocol)
## Problem Statement

In the realm of decentralized autonomous organizations (DAOs), event organization faces a pivotal challenge: outdated payment systems. Enter our solution – a groundbreaking Decentralized Event Payment System. DAO events on platforms like Discord attract diverse participants, but current NFT-based access and fixed fees don't cater to modern needs. Our system offers flexible payment based on attendance duration, leveraging blockchain tech like Chainlink and IPFS for seamless, secure transactions. It fosters community engagement and loyalty through features like SuperFluid-powered streams and NFT integration.

## Solution

We have developed a Decentralized Event Payment System that allows attendees to pay based on the duration of their attendance, rather than a fixed package, improving flexibility and value. This system integrates blockchain technology for secure and a payment model based on the duration of attendance, with features such as real-time price data retrieval and decentralized file storage. To achieve this payment stream generation, we have utilized the Superfluid protocol.

## TechStack

**Web App:**

- React.js
- Ant Design (UI Library)
- Tableland (decentralized SQL like Relational Database)
- Chainlink (used as a datafeed to fetch the current price of Dai token in USD)
- IPFS & Moralis (For storing and pinning files on IPFS Distributed File System)
- SuperFluid (To establish payment stream)
- Polygon (To deploy smart contracts)

**Discord Bot:**

- Node.js
- Discord.js
- Tableland
- Superfluid

## How does it work?

- Create a metamask account and add Polygon Mumbai network from <https://chainlist.org/>
- Make a `.env` file and add the following items:
  
| What to set in .env               | Where to make the account                      |
|-----------------------------------|------------------------------------------------|
| `REACT_APP_PRIVATE_KEY`           | [Your MetaMask Private Key]<https://metamask.io/> |
| `ETHERSCAN_KEY`                   | [EtherScan API Key](https://etherscan.io/login) |
| `EPNS_PK`                         | [Push Protocol API Key](https://push.org/)     |
| `REACT_APP_ALCHEMY_API_KEY`       | [Alchemy API Key](https://www.alchemy.com/)    |
| `REACT_APP_QUICK_NODE_URL`        | [QuickNode API Key](https://www.quicknode.com/)|
| `REACT_APP_MORALIS_APP_ID`        | [Moralis APP ID](https://moralis.io/)|
| `REACT_APP_COVALENT_API`        | [Covalent API Key](https://www.covalenthq.com/docs/api/)|
| `DISCORDJS_BOT_TOKEN`        | [Discord Bot Token](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token)|

- Run the following commands:
  - `npm i`
  - `npm start`


## Use Cases

- It will be used for organizing and managing event funds and user token streams to event organizer.
- Stream gated event access (powered by discord bot) will ensure only registered + active stream attendees to attend the event.
- EventFlex enables pay per join model where user will only be paying for the amount of time he/she is the part of the DAO events organized in discord vc.
- Time for which the stream is active could be utilized while issuing POAP tokens to the users.




## Team:

- Darshan Birhade
- Himanshu Raheja
- Ishaan Jain
- Ojjas Madare
- Pulkit Jain
- Rubaan Hasan
- Sudharma Teredesai

