Hack Boston Telos Challenge:

1.  How are you going to change the world?

        Increase knowledge and access to the promising technology of web3.

2.  How will you?

        Create dApp to run on Telos Blockchain that trains web3 developers to solve challenges as  presented by https://github.com/telosnetwork/HackBoston_Dapp_ideas

There are 2 challenges: DeFi and Real World. These will interpreted broadly, so feel free to get creative (ask the Telos team if in doubt)!

As a rough guide, best DeFi project will be judged by how it innovates in the traditional and/or decentrlised finance spaces.

On the other hand, best Real World project will be one that has an impact on people's every day lives (eg. providing new ways to earn money through social media and.or solving a critical real world problem).

This problem responds to both challenges presented. Users are introduced to Defi applications with software development. Use of the dApp is incentivized with a valuable yield earning token (sTlos) which enhances the user's finances. Deployment of created projects supported by the learning platform have real world impact on the user and the people of their community.
The creation of a community of educated creators has potential to solve critical real world problems.

‍Project Idea ::

A knowledge based dApp game that guides users through the DeFi Development journey combining video clips, resources and yield-farming/NFT quest type journey to get normies up to speed
The base curriculum is 33 challenges preseented by https://github.com/telosnetwork/HackBoston_Dapp_ideas

Learning is incentivized with tokens and accecorizing avatars that are NFTs by timing the logged in time and challenge completion. Avatars can be combined to create novel rare versions.

Users can work independantly or join teams to collaborate to complete the presented challenges. Coin and avatars can be used to get help / hints around obstacles. Upon building to advanced level users can stake their coin as prize or present their avatars for accesorizing.

Front End:
React

Back End:
express web3

---

Pages

---

Home Page
Fun UI
Description of Incentivization

Log in
Mint Base Avatar( NFT )
Connect Wallet with inital balance

Profile
Avatars are NFTs
Earn coin with active time logged in and goals achieved.
Avatars accesorize with accomplishments ( armor, bows, sparkle, powers)

Community Page
Collaborate with other students working on projects
Find alternate solutions
View Avatars of other users, combine avatars to create team NFTs

Program Overview
Modules to guide developer through the following projects : :

        ~ Make use of Coingecko API in Telos dapps: https://www.coingecko.com/en/api

                Referencing CoinGecko in your App
                1. Mention
                If you are integrating with our API. Please mention our brand and link back to us.

                For example, "Data provided by CoinGecko", "Data from CoinGecko" or "Powered by CoinGecko" (as long as it's true!).

                You may only use the official approved logos, available here.
                https://drive.google.com/drive/folders/1qXUuFJB-Gk2g91vyI-Qt58Z_49FLsjsZ

                For users with Pro API Key, please use this root URL to make API request: https://pro-api.coingecko.com/api/v3/

                Here’s an example of calling Bitcoin’s market data with Pro API Key:
                https://pro-api.coingecko.com/api/v3/coins/markets?vs_currency=usd&ids=bitcoin&x_cg_pro_api_key=YOUR_API_KEYS

        ~ Stableswap pool AMM

        ~ Yield Optimizer similiar to Beefy, Pickle, Yearn

        ~ Streaming Payments platform for subscriptions using NFTs to verify
        Central limit order book DEX similar to the only CLOB running on crypto ->Serum

        ~ Lending front end and primitive: Money market lending protocol EVM native (akin to Compound or Aave)

        ~ Cross-Chain Lending: A lending protocol that immediately provides liquidity for assets transferred cross-chain, utilizing the Wormhole bridge - such that users don't need to wait for the cross-chain assets to be fully confirmed on both chains - in return for a fee

        ~ Fixed-Rate Loans: Where users can take out a fixed-rate loan on an Ethereum Lending/Borrowing protocol that is enabled by an on-chain interest rate swap order book on OmniDex or Zappy Finance

        ~ Censorship resistant Wallstreetbets

        ~ Basis Trade Stablecoin

        ~ Liquidation bot for undercollateralized positions

        ~ Reinsurance markets: An expansion yInsure

        ~ On-chain subscriptions: A protocol that is a factory for any app to create on-chain payment streaming and subscriptions. Combine elements like NFTs to increase engagement and unlock features

        ~ Analytics: perhaps the aggregator above can also roll in key on-chain KPIs that tell you if you’re going to swap token A then what % of buy vs. sell orders and sentiment in the past [24] hrs, whale movements, project developments etc.

        ~ DeFi asset manager: A single interface consolidating all DeFi assets and liabilities across different platforms (and different chains) into one.

        ~ DEX Aggregator: A cross-chain DEX aggregator that allows users to choose the best price for execution across multiple DeFi platforms, including cross-chain platforms.

        ~ Build-your-own Liquidity Mining platform: Utilize yield farming to jumpstart your product

        ~ Prediction market minter with DIA Oracle integration

        ~ Fee Compare: A simple interface that tracks and compares cost to execute something given certain parameters across various DeFi platforms. Parameters include desired spread, transaction fees, trading pair set. Can also track total value saved in transaction fees/spread

        ~ Slashing Insurance: A simple insurance protocol where the community can provide insurance for validators against the risk of being slashed

        ~ Smart Contract Insurance: Something akin to Nexus Mutual

        ~ DeFi visualization dashboards: Plugging into and displaying data from Hyperion, teloscan.io, Telos RPC API.

        ~ Security audits of existing Telos infrastructure

        ~ Build a simple oracle that allows Telos Dapps to connect to an off-chain API or Websocket (e.g. a price feed)

        Swap, Borrow/lend, and Margin Implementation Ideas

        Ideas to extend existing source-code (token-swap, token-lending)

        ~ Add support for new token-swap curve that’s using DIA as oracle

        ~ Add support for cross-asset collateral to token-lending.

        ~ Single collateral token for all deposits can be used across loans

        ~ Add support for adding/removing collateral from token-lending obligation (top-up collateral)

        ~ Add support for liquidations using ordered heap: Liquidator will be only to liquidate positions with lowest health score first

        ~ Add support for token-swap LP as collateral to token-lending. Use-case: single token exposure in AMM

        ~ Add support to token-lending for stable borrowing rates

        ~ Margin trading using token-lending: User can initiate (short/long) margin trade with predefined max leverage

        ~ Token lending stores position in escrow
