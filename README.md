# awesome-solana

## User
### Bridge
- `Allbridge`: backed by `APYSwap` Foundation: https://allbridge.io/
- `Wormhole`: just release v2, (liquidity still not stable `BSC`↔︎`ETH`↔︎`SOL`): https://wormholebridge.com/#/transfer

### Farms
- `Raydium` (DEX on `Serum`): https://raydium.io/
- `APYSwap`: Stake(`ABR` APR 522.37%): https://stake.apyswap.com/
- `Orca`: Pools(`ABR-USDC` APR 218%): https://www.orca.so/pools
- `Saber`: cross-chain stablecoin exchange, low and unable to sort APY: https://saber.so/

### Yield Aggregator
- `SolFarm` Aggregates yield farms from `Raydium` and `Saber` (`ORCA-USDC` APY 350.97%): https://solfarm.io/
- `Sunny` Aggregator (Solana's composable DeFi yield aggregator), low apy bad ui:  https://app.sunny.ag/

### Fundraising Protocol
- `Solanium`: https://solanium.io/

- - -

## Developer
### Basic examples
- `Figment` Learn: https://learn.figment.io/
- [Hello World](https://github.com/solana-labs/example-helloworld)
- [Hello Chainlink Price Feeds on Solana](https://blog.chain.link/how-to-build-and-deploy-a-solana-smart-contract/)
- [Break Solana](https://github.com/solana-labs/break)

### Advance examples
- [Programming on Solana - An Introduction](https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/): Building the escrow program
- [Voting App](https://medium.com/@smith_10562/a-simple-solana-dapp-tutorial-6dedbdf65444)
- [Solana File Upload](https://github.com/mcf-rocks/solana-upload)
- [SPL Token UI Repo](https://github.com/paul-schaaf/spl-token-ui)
- [Messaging App](https://github.com/kemargrant/soltalk) - Proof of Concept

### Libraries & Frameworks
- Solana Program Library (SPL) is a collection of on-chain programs targeting the [Sealevel parallel runtime](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192): https://github.com/solana-labs/solana-program-library/blob/master/examples/rust/README.md
- [StreamingFast Solana library for Go](https://github.com/streamingfast/solana-go)
- Anchor Framework: https://project-serum.github.io/anchor/getting-started/introduction.html

### RPC servers
- Project Serum: [https://solana-api.projectserum.com](https://solana-api.projectserum.com) (**recommended**)
- Figment-Solana: https://docs.figment.io/network-documentation/solana/rpc-and-rest-api
- Solana: [https://api.mainnet-beta.solana.com](https://api.mainnet-beta.solana.com) (**can be unstable**)

### Data/API
- DataHub: https://figment.io/datahub/
- Pyth provides real-time on-chain market data: https://pyth.network/
- Flux Protocol (cross-chain oracle aggregator): https://www.fluxprotocol.org/
- [Serum Vial](https://github.com/tardis-dev/serum-vial) - real-time WebSocket market data API for Serum
- Bonfida: https://docs.bonfida.com/#exchanges

### Messaging
- Wormhole is a protocol for communication between different blockchains: https://wormholenetwork.com/

### Storage
- `Arweave` and Solana partnered to provide a decentralised permanent data storage solution of ledger data: https://www.arweave.org/
- `Ceramic` (Streaming `IPFS`): https://ceramic.network/

### Tools
- [SPL Token UI](https://spl-token-ui.com) for general token management on all clusters
- [Sollet.io](https://sollet.io) allows you to request airdops and mint test tokens where allowed
- [SPL Token Creator UI](https://www.spl-token-ui.com/)
- [Bonfida Token Minter](https://bonfida.com/mint)
- [SPL Manager](http://splmanager.com/)

### Serum (FTX DEX backend): https://projectserum.com/
- [DEX source code](https://github.com/project-serum/serum-dex)
- [Serum.JS](https://github.com/project-serum/serum-js), client-side javascript resources to connect to the DEX
- [Serum DEX UI](https://github.com/project-serum/serum-dex-ui), an implementation of a UI for the Serum DEX
- Testnet deployment of prototype DEX
  - [DEX Program](https://explorer.solana.com/address/9JipvuvjcirpYf8mzYQtozXeYtQLWY67LaZCiANSMNgs)
  - [DEX Market](https://explorer.solana.com/address/2tJ2LVReFCZF81Ej4MAQHEr1kRSmk6QQ5XSnzjC9KJNj)
- Mainnet examples:
  - [DEX Program](https://explorer.solana.com/address/4ckmDgGdxQoPDLUkDT3vHgSAkzA3QRdNq5ywwY4sUSJn)
  - [DEX Market](https://explorer.solana.com/address/8AcVjMG2LTbpkjNoyq8RwysokqZunkjy3d5JDzxC6BJa)
- [PySerum](https://github.com/serum-community/pyserum): Python client library for interacting with the Project Serum DEX.
- Swap based on Serum DEX orderbook:
  - [Swap UI](https://github.com/project-serum/swap-ui)
  - [Swap code](https://github.com/project-serum/swap)
