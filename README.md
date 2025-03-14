# 🏗 Scaffold-ETH x Buildbear

🧪 Quickly experiment with Solidity using a forked private testnet, from the mainnet, and swapping tokens from Uniswap

**Scaffold-Eth x Buildbear** lets you create your own private testnet, (optional) forked from the mainnet, with your own native token and ERC20 Token faucet and blockchain explorer

# 🐻 Features of [Buildbear](https://buildbear.io)


## Creating your private testnet

![image](./Your%20Private%20Testnet.png)

## Using your personal native token faucet

![image](./Native%20Token%20Faucet.png)

## Using your personal ERC20 faucet

![image](./USDC%20Faucet.png)

## Swap your tokens on Forked Uniswap

![image](./Swap%20Tokens%20Using%20Forked%20Uniswap.png)

# 🏄‍♂️ Quick Start

Prerequisites: [Node (v18 LTS)](https://nodejs.org/en/download/) plus [Yarn (v1.x)](https://classic.yarnpkg.com/en/docs/install/) and [Git](https://git-scm.com/downloads)

🚨 If you are using a version < v18 you will need to remove `openssl-legacy-provider` from the `start` script in `package.json`

> 1️⃣ clone/fork 🏗 scaffold-eth x buildbear:

```bash
git clone https://github.com/BuildBearLabs/scaffold-eth.git
```

> 2️⃣ install and create your private testnet (forked from the mainnet):

```bash
cd scaffold-eth
yarn install
yarn fork-bb
```

> 3️⃣ 🛰 deploy your SwapOnUniswap Contract:

```bash
cd scaffold-eth
yarn deploy
```

> 4️⃣ start your 📱 frontend:

🚨 if you have not created your private testnet please follow the the steps in point 2 above:

```bash
cd scaffold-eth
yarn start
```


> 5️⃣ you can use your 🚰 faucet directly from the terminal after creating your private tesnet:

```bash
# for native tokens
yarn faucet-bb native <Insert Amount (optional)> <Insert Your Wallet Address>

# for erc20 tokens
yarn faucet-bb USDC <Insert Amount (optional)> <Insert Your Wallet Address>

# Please note the supported ERC20 tokens below

# by default faucet mints 100 native / erc20 tokens
```

### Supported ERC20 tokens that can be used :

1. USDC
2. USDT
3. DAI
4. BNB
5. BUSD
6. MATIC
7. WBTC
8. UNI
9. AAVE
10.Cake
```bash

# Please note the address for each ERC20 Tokens is automatically updated / changed based on the network that you have forked from

```

🔏 Edit your smart contracts in `packages/hardhat/contracts`

📝 Edit your frontend `App.jsx` in `packages/react-app/src`

💼 Edit your deployment scripts in `packages/hardhat/deploy`

📱 Open http://localhost:3000 to see the app

<!-- 🚨📡 To deploy to a public domain, use `yarn surge`. You will need to have a surge account and have the surge CLI installed. There is also the option to deploy to IPFS using `yarn ipfs` and `yarn s3` to deploy to an AWS bucket 🪣 There are scripts in the `packages/react-app/src/scripts` folder to help with this.` -->

# 📚 Documentation

Documentation, tutorials, challenges, and many more resources, visit: [docs.scaffoldeth.io](https://docs.scaffoldeth.io)

# 🔭 Learning Solidity

📕 Read the docs: https://docs.soliditylang.org

📚 Go through each topic from [solidity by example](https://solidity-by-example.org) editing `YourContract.sol` in **🏗 scaffold-eth**

- [Primitive Data Types](https://solidity-by-example.org/primitives/)
- [Mappings](https://solidity-by-example.org/mapping/)
- [Structs](https://solidity-by-example.org/structs/)
- [Modifiers](https://solidity-by-example.org/function-modifier/)
- [Events](https://solidity-by-example.org/events/)
- [Inheritance](https://solidity-by-example.org/inheritance/)
- [Payable](https://solidity-by-example.org/payable/)
- [Fallback](https://solidity-by-example.org/fallback/)

📧 Learn the [Solidity globals and units](https://docs.soliditylang.org/en/latest/units-and-global-variables.html)

# 🛠 Buidl

Check out all the [active branches](https://github.com/scaffold-eth/scaffold-eth/branches/active), [open issues](https://github.com/scaffold-eth/scaffold-eth/issues), and join/fund the 🏰 [BuidlGuidl](https://BuidlGuidl.com)!

- 🚤 [Follow the full Ethereum Speed Run](https://medium.com/@austin_48503/%EF%B8%8Fethereum-dev-speed-run-bd72bcba6a4c)

- 🎟 [Create your first NFT](https://github.com/scaffold-eth/scaffold-eth/tree/simple-nft-example)
- 🥩 [Build a staking smart contract](https://github.com/scaffold-eth/scaffold-eth/tree/challenge-1-decentralized-staking)
- 🏵 [Deploy a token and vendor](https://github.com/scaffold-eth/scaffold-eth/tree/challenge-2-token-vendor)
- 🎫 [Extend the NFT example to make a "buyer mints" marketplace](https://github.com/scaffold-eth/scaffold-eth/tree/buyer-mints-nft)
- 🎲 [Learn about commit/reveal](https://github.com/scaffold-eth/scaffold-eth-examples/tree/commit-reveal-with-frontend)
- ✍️ [Learn how ecrecover works](https://github.com/scaffold-eth/scaffold-eth-examples/tree/signature-recover)
- 👩‍👩‍👧‍👧 [Build a multi-sig that uses off-chain signatures](https://github.com/scaffold-eth/scaffold-eth/tree/meta-multi-sig)
- ⏳ [Extend the multi-sig to stream ETH](https://github.com/scaffold-eth/scaffold-eth/tree/streaming-meta-multi-sig)
- ⚖️ [Learn how a simple DEX works](https://medium.com/@austin_48503/%EF%B8%8F-minimum-viable-exchange-d84f30bd0c90)
- 🦍 [Ape into learning!](https://github.com/scaffold-eth/scaffold-eth/tree/aave-ape)

# 🏃💨 Speedrun Ethereum

Register as a builder [here](https://speedrunethereum.com) and start on some of the challenges and build a portfolio.

# 💬 Support Chat

Join the telegram [support chat 💬](https://t.me/Web3_dApp_Developers) or buidlguidl [discord](https://discord.gg/pRsr6rwG) to ask questions and find others building with 🏗 scaffold-eth!
