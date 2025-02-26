# Resources for Making Dapps on Celo 💫
Made to support hackers at Node's [Berkeley Blockchain Hackathon](https://thenode.fi/hackathon). Have a resource you want us to add? Make a PR.



## **🌐  Celo Blockchain**

**[Celo Dapp Starter Kit](https://github.com/celo-org/celo-progressive-dapp-starter)**



* [GitHub](https://github.com/celo-org/celo-progressive-dapp-starter)
* ➡️ [Tutorial](https://joenyzio.medium.com/build-celo-dapps-in-15-minutes-or-less-438ea954d0b1)

**[Documentation](https://docs.celo.org/)**   |   **[Developer Guide](https://docs.celo.org/developer-guide/overview)**   |   **[Code Examples](https://docs.celo.org/developer-guide/start)**   |   **[Celo CLI](https://docs.celo.org/command-line-interface/introduction)**


## **🌱  Impact**

**[impactMarket](http://impactmarket.com)**- the largest decentralized universal basic income (UBI) protocol that gives daily/weekly cUSD stipends to 60k users worldwide. Project idea: build a protocol that redirects Moola, Mobius, and/or Ubeswap yield to impactMarket beneficiaries.



* [GitHub](https://github.com/impactMarket)
* [Contracts](https://github.com/impactMarket/impact-market-smart-contracts/tree/main/contracts)
* Relevant function calls
    * Read: beneficiary status, unclaimed UBI, total claimed UBI
    * Write: donate, claim UBI


## **💰  Saving**

**[GoodGhosting](https://goodghosting.com/#/)** - a gamified savings protocol where savings pools reward regular savers with higher interest rates and extra rewards by taking some interest away from those who don’t. Powered by [Moola](moola.market) and [Mobius](mobius.money).



* [GitHub](https://github.com/Good-Ghosting/goodghosting-protocol-v0)
* [Contracts](https://dappradar.com/celo/defi/goodghosting) (then click “14 GoodGhosting Smart Contracts”)
* Relevant function calls
    * [joinGame, makeDeposit, earlyWithdraw, redeemFromExternalPool, withdraw](https://docs.goodghosting.com/docs/game-mechanics-and-technical)

**[PoolTogether](https://pooltogether.com/)** - a no-loss lottery that invests user deposits in lending markets then lotteries off the yield to a single entity. Powered by [Moola](moola.market).



* [GitHub](https://github.com/pooltogether)
* [Contracts](https://v3.docs.pooltogether.com/)


## **📡  Oracles**

**[Celo Reserve](https://docs.celo.org/celo-codebase/protocol/stability/oracles)** - a data feed on the price of Celo’s native asset (CELO) in terms of cUSD, cEUR, and cREAL. Also supports BTC and ETH.



* [GitHub](https://github.com/celo-org/celo-oracle)
* [Contract](https://github.com/celo-org/celo-monorepo/blob/master/packages/protocol/contracts/stability/SortedOracles.sol)

**[Redstone](http://app.redstone.finance.)** - source hundreds of token prices using the Arweave blockchain



* [GitHub](https://github.com/redstone-finance)
* [Docs](https://github.com/redstone-finance/redstone-node/blob/main/docs/COMPILED_ORACLE_DOCS.md)
* ➡️ [Example Integrations](https://github.com/redstone-finance/redstone-evm-connector-examples)

**[Band Protocol](https://bandprotocol.com/)**



* [GitHub](https://github.com/bandprotocol)
* [Docs](https://docs.bandchain.org/)
* ➡️ [Tutorial](https://docs.celo.org/celo-codebase/protocol/oracles/band-protocol-how-to)


## **💱  Exchanges**

**[Ubeswap](ubeswap.org)** - a token launchpad DEX that makes it easy for teams to set-up farming incentives for their liquidity pools. Ubeswap has a constant product AMM as well as an on-chain limit order book.



* [GitHub](https://github.com/Ubeswap)
* [Contracts](https://docs.ubeswap.org/code-and-contracts/overview)
* Relevant function calls
    * Read: price quotes, pool compositions, unclaimed rewards
    * Write: Limit order, swap, deposit and withdraw to LP/farm, claim rewards

**[Mobius](mobius.money)** - a cross-chain stableswap exchange primarily focused on stablecoins. Move money between Celo, Ethereum, Solana, Terra, Avalanche, and Polygon–or treat it as a high-interest savings for your USD stablecoins



* [GitHub](https://github.com/mobiusAMM)
* [Contracts](https://opencelo.gitbook.io/mobius/)
* Relevant function calls
    * Read: price quotes, pool compositions, unclaimed rewards
    * Write: Swap, deposit and withdraw to LP/gauge, claim rewards

**[Symmetric](symmetric.finance)** - a DEX that allows pools to be composed of multiple tokens, allowing the creation of crypto index funds and non 50/50 dual asset pools (e.g. 80% cUSD, 20% MOBI) which can help prevent impermanent loss.



* [GitHub](https://github.com/centfinance)
* [Contracts](https://docs.google.com/spreadsheets/d/12HS-AMMYqvqqxb9qL9LJsG2X9EQkR3gxH5J0GB3DM0I/edit#gid=324163664)


## **🏦  Lending Markets**

**[Moola](moola.market)**- a money market that allows users to lend cUSD, cEUR, and CELO to borrowers in return for a premium for forgoing their liquidity. Moola deposits receive mTokens which are currency denominated and accrue interest similar to dividend payments–they are essentially interest-bearing stablecoins.



* [GitHub](https://github.com/moolamarket)
* [Contracts](https://drive.google.com/file/d/1xGQl625ytbGB8Rt65xK5dnC1wUtfWPJ6/view?usp=sharing)
* Relevant function calls
    * Deposit/withdraw, get a loan, repay a loan, delegate credit, draw credit line, repay credit line, auto-collateralize loan

**[Pinnata](dahlia.finance)** - a money market for leveraged yield farming on Mobius and Sushiswap. Lend single-assets and earn interest, or lever up on your yield farming position. 



* [GitHub](https://github.com/Pinnata/pinnata-contracts-celo)
* [Contracts](https://github.com/Pinnata/pinnata-contracts-celo/tree/master/contracts)

**[Resource](resourcenetwork.co)** - a peer to peer mutual credit market that allows businesses to barter with each other using their own products and services. For example, if you run a massage shop you could offer “free” employee benefits by trading massage vouchers with a hotel for room vouchers. 



* [GitHub](https://github.com/ReSource-Network/)
* Relevant contracts
    * Social recovery multisig, gasless wallet multisig


## **🤑  Yield Chasers**

**[Beefy](https://beefy.finance/)** - an auto-compound protocol for yield farmers.



* [GitHub](https://github.com/beefyfinance)
* [Contracts](https://docs.beefy.com/additional-resources/code-repositories)

**[Revo Market](https://revo.market/#/)** - an auto-compound protocol for yield farmers.



* [GitHub](https://github.com/revo-market)
* [Contracts](https://docs.revo.market/dyor/contracts)


## **🆔  Identity**

**[Nomspace](nom.space)** - a cross-chain naming service that allows users to map human-readable names to their wallet address across Celo, Avalanche, and Polygon.



* [GitHub](https://github.com/Nomspace)
* [Contracts](https://github.com/nomspace/xnom-contracts)
* Relevant function calls
    * Reserve a name, fetch name for an address

**<span style="text-decoration:underline;">[Celo Identity](https://docs.celo.org/celo-codebase/protocol/identity)</span>** - map a wallet address to a phone number, which allows users to send money to people who haven’t signed up yet (hold in escrow contract until phone number has been verified by 3/3 Celo validators) 


## **🌉  Bridges**

**[Optics](optics.xyz)** - a 1-to-n optimistic bridge that is fully trustless. Cross-chain applications can be deployed to the bridge and tap into smart contracts across Celo, Ethereum, Polygon, and Avalanche.



* [GitHub](https://github.com/celo-org/optics-monorepo)
* [How does it work](https://docs.celo.org/celo-codebase/protocol/optics)

**[AllBridge](allbridge.io)** - a fast and cheap custodial bridge for moving funds between Celo and almost every other blockchain.



* [GitHub](https://github.com/allbridge-io)
* [Contracts](https://docs.allbridge.io/allbridge-overview/bridge-contracts)
* [How it works](https://docs.allbridge.io/allbridge-overview/under-the-hood-of-allbridge)
