---
title: "Week #1"
---

# Week #1

## **Team Formation and Project Proposal**

### **Team Members**

| Team Member              | Telegram ID                       | Email Address                       |
|--------------------------|-----------------------------------|-------------------------------------|
| Georgii Butakov (Lead)   | [@mazzz3r](https://t.me/mazzz3r)  | g.butakov@innopolis.university      |
| Artyom Shaposhnikov      | [@ortieom](https://t.me/ortieom)  | a.shaposhnikov@innopolis.university |
| Nikita Ruchkin           | [@reterman](https://t.me/reterman)| n.ruchkin@innopolis.university      |
| Ivan Platonov            | [@dpttk](https://t.me/dpttk)      | i.platonov@innopolis.university     |
| Mikhail Dudinov          | [@ez4gotit](https://t.me/ez4gotit)| m.dudinov@innopolis.university      |

### **Value Proposition**

- Identify the Problem:
Cryptocurrency traders often struggle with inefficient trading mechanisms, high latency, vulnerability to attacks such as MEV, and poor liquidity management, which can lead to substantial financial losses.

- Solution Description:
Our platform provides a robust solution by offering automated tools for sniping new liquidity pools, managing risks through stop loss and take profit features, and detailed analysis of token metrics and smart contracts. This ensures traders can make informed, swift decisions in a volatile market.

- Benefits to Users:
Users benefit from real-time, low-latency trading, enhanced security against common blockchain attacks, and comprehensive token analysis, which altogether enhance trading efficiency and safety.

- Differentiation:
Our platform stands out by integrating direct blockchain interactions, which reduces dependency on third-party APIs and minimizes latency. Additionally, our advanced features like liquidity filtering and customizable buy slippage options provide users with unparalleled control over their trading strategies.
Here is a table of competitor analysis:
| Bot Name          | Interface Design         | Usability | Performance Monitoring      | Security Features              | Supported Platforms | User Experience Highlights                                                                   | Functionality                           | Key Features                                                             | Cost                       | Supported Networks                      |
|-------------------|--------------------------|-----------|-----------------------------|--------------------------------|---------------------|----------------------------------------------------------------------------------------------|-----------------------------------------|--------------------------------------------------------------------------|----------------------------|-----------------------------------------|
| **Mizar**         | Clean, modern            | High      | Real-time analytics         | Two-factor authentication      | Web, Mobile         | User-friendly with clear navigation, suitable for both beginners and advanced traders        | Hybrid sniping, copy trading            | Multi-strategy, Telegram integration, TradingView signals                | $0, $15, $30 per month     | Uniswap, Binance, MEXC, Gate.io, KuCoin |
| **Unibot**        | Simplified, Telegram     | Very High | Fast market updates         | Privacy-focused                | Telegram            | Simplified access via Telegram, privacy-focused with seamless trading experience             | Multi-network support, Telegram scanner | Copy trading, bridge aggregator, market scanner                          | Not specified              | Ethereum, Base, Solana, Arbitrum        |
| **Maestro**       | Detailed, Telegram       | High      | Detailed ICO                | Anti-rug pull                  | Telegram            | Convenient for ICO investments and whale tracking, highly customizable for advanced users    | Whale tracking                          | Anti-rug pull, DEX sniping, customizable settings                        | Not specified              | Ethereum, BNB Chain, Arbitrum           |
| **Launch Sniper** | Professional, plan-based | High      | High-speed operations       | Full node security             | Web                 | High-speed operations with user-focused support, tailored plans for different user needs     | AI-driven picks                         | Full private node, fastest server, unlimited AI picks, 24/7 support      | $395 - $995 lifetime       | Not specified                           |
| **Banana Gun**    | Competitive, detailed    | High      | Transaction status tracking | Anti-rug, private transactions | Web                 | Easy transaction management with anti-rug and private transaction features                   | Auto and manual sniping                 | Anti-rug, private transactions, sandwich protection, adjustable slippage | 0.5% fee on buys and sells | Ethereum                                |
| **Photon**        | Specific, Solana-focused | Medium    | Performance filters         | Rug pull protection            | Web                 | Detailed filters and settings for precise sniping, suitable for Solana ecosystem users       | Solana-specific sniping                 | Liquidity filters, minimum holders, customizable parameters              | Not specified              | Solana                                  |
| **Trojan**        | Simple, Telegram         | Medium    | Basic tracking via Telegram | Simple security                | Telegram            | Simple and easy to use, ideal for Telegram users focused on Solana trading                   | DCA tools                               | Accessible via Telegram, easy to use                                     | Not specified              | Solana                                  |
| **DexBot**        | Advanced, versatile      | High      | Real-time status monitor    | Anti-blacklisting              | Web                 | Comprehensive trading tools with detailed analytics, suitable for diverse trading strategies | Advanced trading tasks                  | Contract security scan, anti-blacklisting, batch buy/sell                | Not specified              | Multiple main-nets                      |
| **BullX.io**      | Intuitive, multi-chain   | High      | Real-time data              | Contract security              | Web, Mobile         | Versatile and intuitive with real-time data and customizable options for various networks    | Multi-chain trading                     | Real-time charts, customizable gas fees, contract security, copy-trading | Not specified              | Ethereum, BNB, Polygon                  |


- User Impact:
Traders will experience a more streamlined and secure trading environment, leading to better management of their investments and potentially higher profits due to timely and informed decision-making.

- Accessibility for Newcomers:
Our platform is designed to be extremely user-friendly, especially for newcomers to cryptocurrency trading. It provides simplified tools and interfaces that make it easier for beginners to understand how trading works, thus reducing the likelihood of costly mistakes and enhancing their overall trading experience.

## **Lean Questionnaire**

1. What problem or need does your software project address? 
   - The project addresses the need for a reliable, secure, and efficient trading platform on the TON Blockchain, focusing on issues such as high latency and vulnerability to MEV attacks.

2. Who are your target users or customers?
   - The target users are cryptocurrency traders and investors active on the TON blockchain, including both novice and experienced traders.

3. How will you validate and test your assumptions about the project?
   - Initial assumptions will be tested through user interviews, surveys, prototype testing, A/B testing, and analytics post-launch to measure user engagement and satisfaction.

4. What metrics will you use to measure the success of your project?
   - Key performance indicators include user acquisition rates, active users, transaction volume, user retention rates, and feedback scores. System performance will also be monitored.

5. How do you plan to iterate and pivot if necessary based on user feedback?
   - The development cycle will be agile, allowing for iterative releases based on user feedback, with regular updates and feature additions based on user demand and market trends.

## **Defining the Vision for Your Project**

- Overview:
Our project aims to revolutionize cryptocurrency trading on the TON blockchain by providing a comprehensive suite of tools that enhance trading efficiency and security.

- Schematic Drawings:

<div style="text-align: center;">
  <img src="/2024/Gopher-Marksman/UserFlow.png" alt="User Flow">
</div>

- Tech Stack:
  - Backend: Python (FastAPI), PostgreSQL
  - Frontend: React.js
  - Blockchain Interaction: Pythoniq (TON Blockchain SDK with native ADNL protocols implementations)
