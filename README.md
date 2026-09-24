<!--lint disable double-link-->
# ![Injective](https://avatars.githubusercontent.com/u/44571224?s=60&v=4) Awesome Injective [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated list of curated resources for learning, building, integrating,
operating, and exploring Injective.

## Contents
- [Start Here](#start-here)
- [Core Protocol](#core-protocol)
- [Developer Documentation](#developer-documentation)
- [SDKs and Libraries](#sdks-and-libraries)
- [EVM Development](#evm-development)
- [Wasm VM Development](#wasm-vm-development)
- [Native and DeFi Development](#native-and-defi-development)
- [AI and Agent Development](#ai-and-agent-development)
- [Starter Templates and Examples](#starter-templates-and-examples)
- [APIs, Data, and Indexing](#apis-data-and-indexing)
- [Trading and Market Making](#trading-and-market-making)
- [Infrastructure and Node Operations](#infrastructure-and-node-operations)
- [Security](#security)
- [Wallets and Custody](#wallets-and-custody)
- [Interoperability and Bridges](#interoperability-and-bridges)
- [Oracles](#oracles)
- [Analytics and Explorers](#analytics-and-explorers)
- [Ecosystem Applications](#ecosystem-applications)
- [Learning and Research](#learning-and-research)
- [Community and Programs](#community-and-programs)
- [Related Awesome Lists](#related-awesome-lists)


## Start Here

- [Injective](https://injective.com/) - Protocol website and entry point for users, developers, and institutions.
- [Developer Portal](https://injective.com/dev) - Curated builder landing page with starter templates, tutorials, infrastructure, and programs.
- [Developer Documentation](https://docs.injective.network/) - Canonical technical documentation for Injective.
- [Injective Hub](https://injhub.com/) - Wallet, staking, governance, ecosystem, and account portal.
- [Ecosystem Directory](https://injhub.com/ecosystem/) - Searchable directory of applications, infrastructure, wallets, validators, and integrations.
- [INJScan](https://injscan.com/) - Mainnet explorer for blocks, transactions, accounts, validators, and markets.
- [Injective Bridge](https://bridge.injective.network/) - Bridge for moving assets between Injective and supported networks.
- [Testnet Faucet](https://testnet.faucet.injective.network/) - Testnet INJ faucet for development.
- [Injective Labs on GitHub](https://github.com/InjectiveLabs) - Open source SDKs, services, tools, and reference projects.
- [Injective Foundation on GitHub](https://github.com/InjectiveFoundation) - Home of the core chain implementation.
- [Network Information](https://docs.injective.network/developers/network-information) - Chain IDs, endpoints, explorers, and network configuration.
- [Public Endpoints](https://docs.injective.network/infra/public-endpoints) - Public REST, gRPC, Tendermint RPC, and EVM JSON-RPC endpoints.

## Core Protocol

- [injective-core](https://github.com/InjectiveFoundation/injective-core) - Injective Core chain, native modules, node binary, and protocol implementation.
- [Injective Chain Releases](https://github.com/InjectiveLabs/injective-chain-releases) - Published chain binaries and release artifacts.
- [Injective Design](https://github.com/InjectiveLabs/design-md-injective) - Technical design notes for Injective.
- [Injective Docs Source](https://github.com/InjectiveLabs/injective-docs) - Source repository for the current documentation.
- [Injective Protobuf](https://github.com/InjectiveLabs/injective-proto) - Generated protobuf definitions for Injective modules and services.
- [Injective Lists](https://github.com/InjectiveLabs/injective-lists) - Canonical JSON lists used for assets and ecosystem metadata.
- [Injective Core SDK](https://github.com/InjectiveLabs/cosmos-sdk) - Injective Core SDK.
- [CometBFT](https://github.com/InjectiveLabs/cometbft) - Consensus engine used by Injective.
- [go-ethereum](https://github.com/InjectiveLabs/go-ethereum) - Go Ethereum implementation used by Injective EVM.
- [evm-gateway](https://github.com/InjectiveLabs/evm-gateway) - Standalone Ethereum JSON-RPC server for Injective EVM.
- [wasmd](https://github.com/InjectiveLabs/wasmd) - Injective Core SDK application with Wasm VM smart-contract support.
- [ibc-go](https://github.com/InjectiveLabs/ibc-go) - Go implementation of the Inter-Blockchain Communication protocol.
- [ibc-apps](https://github.com/InjectiveLabs/ibc-apps) - IBC applications and middleware.
- [Block SDK](https://github.com/InjectiveLabs/block-sdk) - Programmable block-building components for Injective Core.

## Developer Documentation

- [Developer Overview](https://docs.injective.network/developers) - Starting point for building applications on Injective.
- [Native Developers](https://docs.injective.network/developers-native) - Wallets, transactions, queries, indexer streams, and native modules.
- [DeFi Developers](https://docs.injective.network/developers-defi) - Tokens, markets, oracles, exchange integrations, and trading strategies.
- [DeFi Concepts](https://docs.injective.network/defi) - Wallets, trading, tokens, bridging, staking, governance, and fees.
- [Reference Index](https://docs.injective.network/references) - Protocol references and supporting technical material.
- [Documentation Index for Agents](https://docs.injective.network/llms.txt) - Machine readable index of all current documentation pages.

## SDKs and Libraries

### TypeScript

- [injective-ts](https://github.com/InjectiveLabs/injective-ts) - TypeScript packages for wallets, transactions, queries, indexer APIs, and native modules.
- [TypeScript SDK Documentation](https://github.com/InjectiveLabs/injective-ts) - SDK guides and API reference.
- [injective-ui](https://github.com/InjectiveLabs/injective-ui) - Reusable UI packages used across Injective applications.
- [injective-cli-ts](https://github.com/InjectiveLabs/injective-cli-ts) - TypeScript commandline client for Injective services.

### Python

- [sdk-python](https://github.com/InjectiveLabs/sdk-python) - Python client for the Injective Exchange API and chain interactions.
- [sdk-python-quants](https://github.com/InjectiveLabs/sdk-python-quants) - Python tooling and examples for quantitative trading workflows.
- [injective-trader](https://github.com/InjectiveLabs/injective-trader) - Agent based execution and strategy framework built on the Python SDK.

### Go

- [sdk-go](https://github.com/InjectiveLabs/sdk-go) - Go tools for Injective Chain, Injective EVM, and EIP-712 transactions.
- [injective-cache](https://github.com/InjectiveLabs/injective-cache) - Switchable in memory and Redis cache utility used by Injective services.
- [go-grpc-http1](https://github.com/InjectiveLabs/go-grpc-http1) - Go library for serving gRPC through HTTP/1.
- [stitch](https://github.com/InjectiveLabs/stitch) - Height aware multiprotocol gateway for Injective Core and Injective node fleets.

### Rust and Wasm VM

- [injective-rust](https://github.com/InjectiveLabs/injective-rust) - Rust libraries and bindings for Injective.
- [cw-injective](https://github.com/InjectiveLabs/cw-injective) - Injective messages, queries, and types for Wasm VM contracts.
- [cw20-adapter](https://github.com/InjectiveLabs/cw20-adapter) - Adapter for moving between CW20 assets and native bank denominations.
- [Injective Test Tube](https://github.com/InjectiveLabs/test-tube) - Test Wasm VM contracts against an Injective chain without mocks.

## EVM Development

- [EVM Overview](https://docs.injective.network/developers-evm) - Injective EVM concepts and development paths.
- [EVM Network Information](https://docs.injective.network/developers-evm/network-information) - Chain IDs, RPC endpoints, explorers, and wallet configuration.
- [Your First EVM Smart Contract](https://docs.injective.network/developers-evm/smart-contracts) - Compile, test, deploy, verify, and interact with Solidity contracts.
- [Your First EVM dApp](https://docs.injective.network/developers-evm/dapps) - Connect Injective EVM dApps through MetaMask and WalletConnect.
- [EVM Equivalence](https://docs.injective.network/developers-evm/evm-equivalence) - Compatibility details for Ethereum tooling and applications.
- [MultiVM Token Standard](https://docs.injective.network/developers-evm/multivm-token-standard) - Unified token representation across EVM and native execution.
- [Permissioned MultiVM Tokens](https://docs.injective.network/developers-evm/permissioned-multivm-token) - Permission controls for MultiVM tokens.
- [Precompiles](https://docs.injective.network/developers-evm/precompiles) - Solidity access to Injective-native modules.
- [Bank Precompile](https://docs.injective.network/developers-evm/bank-precompile) - Native bank operations from Solidity.
- [Exchange Precompile](https://docs.injective.network/developers-evm/exchange-precompile) - On-chain orderbook and exchange operations from Solidity.
- [Oracle Precompile](https://docs.injective.network/developers-evm/oracle-precompile) - Native oracle data from Solidity.
- [ERC-20 Module](https://docs.injective.network/developers-evm/erc20-module) - ERC-20 integration with Injective-native assets.
- [Infrastructure and Tooling](https://docs.injective.network/developers-evm/infrastructure-and-tooling) - RPC, explorers, wallets, and production services for EVM builders.
- [EVM Integrations Cheat Sheet](https://docs.injective.network/developers-evm/evm-integrations-cheat-sheet) - Production integration references for EVM applications.
- [EVM Integrations FAQ](https://docs.injective.network/developers-evm/evm-integrations-faq) - Common compatibility and deployment questions.
- [solidity-contracts](https://github.com/InjectiveLabs/solidity-contracts) - Solidity contracts used by Injective EVM components.
- [Foundry](https://github.com/InjectiveLabs/foundry) - Injective maintained fork of the Foundry toolkit.
- [etherman](https://github.com/InjectiveLabs/etherman) - Go CLI for managing and testing Solidity contract deployments.
- [rundler](https://github.com/InjectiveLabs/rundler) - Rust ERC-4337 bundler used for account-abstraction workflows.

## Wasm VM Development

- [Wasm VM Overview](https://docs.injective.network/developers-cosmwasm) - Starting point for Rust smart-contract development.
- [Your First Wasm VM Contract](https://docs.injective.network/developers-cosmwasm/smart-contracts/your-first-smart-contract) - Build and deploy a first Wasm VM contract.
- [Local Development](https://docs.injective.network/developers-cosmwasm/local-development-guide) - Run and test Wasm VM contracts locally.
- [Mainnet Deployment](https://docs.injective.network/developers-cosmwasm/mainnet-deployment-guide) - Production deployment workflow.
- [Using Injective Modules and Queries](https://docs.injective.network/developers-cosmwasm/cosmwasm-any) - Access native module messages and queries from Wasm VM.
- [Create a Swap Contract](https://docs.injective.network/developers-cosmwasm/create-your-swap-contract-guide) - Build an atomic swap contract on Injective.
- [Create Contract UIs](https://docs.injective.network/developers-cosmwasm/create-uis-guide) - Connect web interfaces to Wasm VM contracts.
- [CW20 Adapter Guide](https://docs.injective.network/developers-cosmwasm/cw20-adapter) - Convert Wasm VM CW20 token type balances to native Injective Core denominations.
- [Injective Test Tube Guide](https://docs.injective.network/developers-cosmwasm/injective-test-tube) - Integration test contracts against Injective Core modules.
- [swap-contract](https://github.com/InjectiveLabs/swap-contract) - Reference atomic token swap contract.
- [Wasm VM 101](https://github.com/InjectiveLabs/CosmWasm101) - Introductory workshop material and examples.

## Native and DeFi Development

- [Building dApps](https://docs.injective.network/developers/dapps) - React, Nuxt, TypeScript, DEX, and contract examples.
- [Transaction Examples](https://docs.injective.network/developers-native/examples) - Native Injective Core module transaction examples.
- [Querying the Chain](https://docs.injective.network/developers-native/query-chain) - Query core modules through typed clients.
- [Querying the Indexer](https://docs.injective.network/developers-native/query-indexer) - Accounts, markets, orders, positions, and portfolio data.
- [Streaming the Indexer](https://docs.injective.network/developers-native/query-indexer-stream) - Realtime account, market, oracle, and explorer streams.
- [Exchange Module](https://docs.injective.network/developers-native/injective/exchange) - State, messages, proposals, events, and exchange concepts.
- [Token Factory](https://docs.injective.network/developers/concepts/token-factory) - Native Injective Core token creation and management.
- [Launch a Token](https://docs.injective.network/developers-defi/token-launch) - Token launch workflow for Injective.
- [Launch a Market](https://docs.injective.network/developers-defi/market-launch) - Spot and derivatives market-launch workflow.
- [Provider Oracle](https://docs.injective.network/developers-defi/provider-oracle) - Create and operate a provider oracle.
- [Market Tick-Size Calculations](https://docs.injective.network/developers-defi/calculate-min-price-tick-size) - Calculate price and quantity tick sizes for markets.
- [Injective List](https://docs.injective.network/developers/assets/injective-list) - Asset metadata and canonical list integration.
- [Denoms and Token Metadata](https://docs.injective.network/developers/assets/denom) - Native Injective Core denomination and metadata conventions.

## AI and Agent Development

**Official**

- [AI Developer Overview](https://docs.injective.network/developers-ai) - AI application and agent development entry point.
- [agent-skills](https://github.com/InjectiveLabs/agent-skills) - Installable skills for EVM development, CLI operations, trading, and MCP.
- [Injective MCP Server](https://github.com/InjectiveLabs/mcp-server) - MCP server for trading, transfers, bridging, and raw EVM transactions.
- [MCP Server Guide](https://docs.injective.network/developers-ai/mcp) - Connect compatible AI assistants to Injective.
- [Documentation MCP](https://docs.injective.network/developers-ai/documentation-mcp) - Give agents current Injective documentation with source context.
- [CLI Agent Skill](https://docs.injective.network/developers-ai/injective-cli-skill) - Execute Injective Core `injectived` operations through natural language.
- [EVM Developer Skill](https://docs.injective.network/developers-ai/injective-evm-developer-skill) - Injective-specific EVM assistance for coding agents.
- [Trading Skills](https://docs.injective.network/developers-ai/injective-trading-skills) - Skills for querying markets and managing exchange positions.
- [injective-agent-sdk](https://github.com/InjectiveLabs/injective-agent-sdk) - SDK components for building Injective agents.
- [iAgent](https://github.com/InjectiveLabs/iAgent) - Agent fine tuned for the Injective trading framework and documentation.
- [iagent-ts](https://github.com/InjectiveLabs/iagent-ts) - TypeScript tools for Injective agents.

**Community**

- [dAppBuilder](https://dappbuilder.ai/) - Natural language builder for creating and deploying Injective applications.

## Starter Templates and Examples

**Official**

- [injective-ts-examples](https://github.com/InjectiveLabs/injective-ts-examples) - Runnable TypeScript SDK examples.
- [Nuxt Basic Starter](https://github.com/InjectiveLabs/injective-create-app-template-nuxt-basic-starter) - Minimal Nuxt application template.
- [Nuxt Full Starter](https://github.com/InjectiveLabs/injective-create-app-template-nuxt-full-starter) - Full Nuxt application scaffold.
- [Nuxt Smart-Contract Counter](https://github.com/InjectiveLabs/injective-create-app-template-nuxt-sc-counter) - Nuxt smart-contract example.
- [React Basic Starter](https://github.com/InjectiveLabs/injective-create-app-template-react-basic-starter) - Minimal React application template.
- [React Full Starter](https://github.com/InjectiveLabs/injective-create-app-template-react-full-starter) - Full React application scaffold.
- [React Smart-Contract Counter](https://github.com/InjectiveLabs/injective-create-app-template-react-sc-counter) - React smart-contract example.
- [Vue Turnkey Template](https://github.com/InjectiveLabs/injective-create-app-template-vue-turnkey) - Vue starter with Turnkey wallet integration.
- [Injective Helix Demo](https://github.com/InjectiveLabs/injective-helix-demo) - Reference implementation of an exchange frontend.
- [Injective API Demo](https://github.com/InjectiveLabs/injective-api-demo) - Example application for Injective APIs.
- [Foundry Injective Template](https://github.com/InjectiveLabs/inj-examples/tree/main/templates/foundry) - Minimal Foundry template for compiling, testing, deploying, verifying, and interacting with Injective EVM contracts.
- [Hardhat Injective Template](https://github.com/InjectiveLabs/inj-examples/tree/main/templates/hardhat) - Minimal Hardhat template for Injective EVM contracts.
- [React Injective Template](https://github.com/InjectiveLabs/inj-examples/tree/main/templates/react) - React dApp template with smart-contract, wallet, and MCP examples.
- [Injective x402 Tutorial](https://github.com/InjectiveLabs/inj-examples/tree/main/examples/usdc) - Build an x402-gated content application with USDC payments.
- [N Days of Injective](https://github.com/InjectiveLabs/inj-examples/tree/main/tutorials/n-days-of-injective) - Seven-part course covering setup, contracts, dApps, MultiVM tokens, SDKs, exchange, and nodes.

## APIs, Data, and Indexing

**Official**

- [Chain API Reference](https://sentry.lcd.injective.network/swagger/) - REST/LCD API reference for chain modules.
- [Exchange API Reference](https://api.injective.exchange/) - Exchange, market, account, and trading API reference.
- [Indexer API](https://docs.injective.network/developers/concepts/indexer-api) - Overview of the off chain indexer architecture.
- [Indexer API Reference](https://api.injective.network/swagger/) - Swagger reference for Injective indexer services.
- [gRPC and Protobuf](https://docs.injective.network/developers/concepts/grpc-protobuf) - Typed gRPC interfaces and protobuf definitions.
- [WebSocket Server](https://docs.injective.network/infra/websocket-server) - Stream realtime chain events through WebSockets.

**Community**

- [The Graph for Injective](https://docs.substreams.dev/how-to-guides/injective) - Substreams guide for indexing Injective data.
- [SubQuery](https://subquery.network/) - Multi-chain indexer with Injective support.
- [Google Cloud Web3](https://cloud.google.com/application/web3) - Managed blockchain data and infrastructure provider listed in the Injective ecosystem.
- [Alchemy](https://www.alchemy.com/) - EVM RPC and developer platform with Injective support.
- [QuickNode](https://www.quicknode.com/chains/inj) - Managed Injective endpoints and infrastructure.
- [NOWNodes](https://nownodes.io/injective-inj) - Hosted Injective RPC access.
- [1RPC](https://www.1rpc.io/) - Privacy preserving RPC service with Injective support.

## Trading and Market Making

**Official**

- [Trading Documentation](https://docs.injective.network/defi/trading) - Markets, orders, fees, margin, liquidations, and derivatives.
- [Injective Trader](https://docs.injective.network/developers-defi/injective-trader) - Strategy framework and implementation guide.
- [pdaas](https://github.com/InjectiveLabs/pdaas) - Perpetual DEX as a service.
- [Injective RFQ Toolkit](https://github.com/InjectiveLabs/injective-rfq-toolkit) - Toolkit for request-for-quote integrations.
- [Injective Liquidator Bot](https://github.com/InjectiveLabs/injective-liquidator-bot) - Reference liquidation bot for derivative markets.

**Community**

- [Hummingbot](https://hummingbot.org/) - Open source market making and trading bot framework with Injective connectivity.

## Infrastructure and Node Operations

**Official**

- [Infrastructure Overview](https://docs.injective.network/infra) - Operational documentation for node providers and validators.
- [Run a Node](https://docs.injective.network/infra/run-node) - Install and run an Injective node.
- [Join a Network](https://docs.injective.network/infra/join-a-network) - Connect a node to mainnet or testnet.
- [Mainnet Validator](https://docs.injective.network/infra/validator-mainnet) - Set up and operate a mainnet validator.
- [Testnet Validator](https://docs.injective.network/infra/validator-testnet) - Set up and operate a testnet validator.
- [Cosmovisor](https://docs.injective.network/infra/cosmovisor) - Configure automated binary upgrades.
- [Upgrade a Node](https://docs.injective.network/infra/upgrade-node) - Keep nodes aligned with current chain releases.
- [Archival Setup](https://docs.injective.network/infra/archival-setup) - Run archival chain and indexer infrastructure.
- [Premium Endpoints](https://docs.injective.network/infra/premium-endpoints) - Dedicated RPC and indexing providers.
- [coremon](https://github.com/InjectiveLabs/coremon) - Chain monitoring tool for benchmarks and mainnet debugging.
- [coretracer](https://github.com/InjectiveLabs/coretracer) - Tracing utilities for core-chain diagnostics.
- [chain-stresser](https://github.com/InjectiveLabs/chain-stresser) - Load generation utility for chain testing.
- [interchaintest](https://github.com/InjectiveLabs/interchaintest) - End-to-end testing framework for interchain networks.
- [injective-starnet](https://github.com/InjectiveLabs/injective-starnet) - Orchestration tooling for distributed Injective Core networks.
- [metrics](https://github.com/InjectiveLabs/metrics) - Injective fork of StatsD compatible metrics library.
- [otel](https://github.com/InjectiveLabs/otel) - Injective fork of OpenTelemetry metrics library.

**Community**

- [Polkachu](https://polkachu.com/) - Community snapshots, state sync, and validator infrastructure.

## Security

**Official**

- [Injective Bug Bounty](https://cantina.xyz/bounties/79042c5c-2331-4100-9bc7-249a540cd013) - Responsible disclosure bounty program hosted by Cantina.

**Community**

- [CertiK](https://www.certik.com/) - Security auditor and monitoring provider listed in the Injective ecosystem.
- [SCV Security](https://www.scv.services/) - Injective Core ecosystem validator and security provider.
- [Tenderly](https://dashboard.tenderly.co/explorer/injective-testnet) - EVM transaction simulation, debugging, and testnet exploration.
- [OpenZeppelin Contracts](https://github.com/OpenZeppelin/openzeppelin-contracts) - Audited Solidity components for EVM smart contracts.
- [Wasm VM Security](https://book.cosmwasm.com/security.html) - Security considerations for Wasm VM smart-contract development.

## Wallets and Custody

### User and Developer Wallets

- [MetaMask](https://metamask.io/) - EVM wallet compatible with Injective EVM.
- [Keplr](https://www.keplr.app/) - Core wallet with Injective support.
- [Leap](https://www.leapwallet.io/) - Core wallet with Injective support.
- [Cosmostation](https://www.cosmostation.io/) - Wallet and staking interface for Injective.
- [Phantom](https://phantom.app/) - Multi-chain wallet listed for Injective EVM.
- [Trust Wallet](https://trustwallet.com/) - Multi-chain wallet with INJ support.
- [SafePal](https://safepal.com/) - Software and hardware wallet with Injective support.
- [Ledger](https://www.ledger.com/) - Hardware signing through supported Injective wallet integrations.
- [Trezor](https://trezor.io/) - Hardware wallet listed in the Injective ecosystem.
- [Ninji](https://ninji.xyz/) - Injective focused wallet.
- [Station](https://station.money/) - Injective Core wallet with Injective support.
- [Gem Wallet](https://gemwallet.com/) - Open source multi-chain wallet with Injective support.
- [Exodus](https://www.exodus.com/) - Multi-chain wallet supporting INJ.

### Embedded Wallets and Custody

- [Turnkey](https://www.turnkey.com/) - Embedded wallet and key management infrastructure.
- [Fireblocks](https://www.fireblocks.com/) - Institutional digital asset custody and transfer infrastructure.
- [BitGo](https://www.bitgo.com/) - Institutional wallet and custody platform.
- [Cobo](https://www.cobo.com/) - Institutional custody and wallet infrastructure.
- [Fordefi](https://fordefi.com/) - Institutional MPC wallet platform.
- [Utila](https://utila.io/) - Enterprise wallet and asset operations platform.
- [Copper](https://copper.co/) - Institutional digital-asset custody and settlement.

## Interoperability and Bridges

- [IBC](https://ibcprotocol.org/) - Inter-Blockchain Communication protocol used by Injective.
- [Axelar](https://axelar.network/) - General message passing and cross chain connectivity.
- [Wormhole](https://wormhole.com/) - Cross-chain messaging and asset transfers.
- [Hyperlane](https://www.hyperlane.xyz/) - Permissionless interoperability infrastructure.
- [LayerZero](https://layerzero.network/) - Omnichain messaging infrastructure available to EVM applications.
- [deBridge](https://debridge.com/) - Cross chain transfer and messaging protocol for Injective EVM applications.
- [Stargate](https://stargate.finance/) - Omnichain liquidity transfer protocol.
- [Celer](https://celer.network/) - Cross chain messaging and bridging infrastructure.
- [Meson](https://meson.fi/) - Stablecoin transfer and swap protocol.
- [Rhino.fi](https://app.rhino.fi/bridge) - Multi-chain bridge with Injective ecosystem support.
- [Catalyst](https://catalyst.exchange/) - Cross chain liquidity and interoperability protocol.
- [Skip Go](https://skip.money/) - Cross chain routing and transaction infrastructure.

## Oracles

**Official**

- [Oracle Module](https://docs.injective.network/developers-native/injective/oracle) - Native oracle module specification and messages.

**Community**

- [Pyth](https://www.pyth.network/) - Low latency market data oracle integrated with Injective.
- [Chainlink](https://chain.link/) - Oracle and data infrastructure for Injective EVM applications.
- [Stork](https://www.stork.network/) - Low latency oracle infrastructure listed in the Injective ecosystem.
- [Band Protocol](https://bandprotocol.com/) - Cross chain data oracle used by Injective.
- [API3](https://market.api3.org/injective) - First party oracle feeds for Injective EVM.
- [DIA](https://www.diadata.org/) - Open source oracle and market data platform.
- [Truflation](https://truflation.com/) - Economic and real world data provider.

## Analytics and Explorers

**Official**

- [Injective Testnet Explorer](https://testnet.blockscout.injective.network/) - Blockscout explorer for Injective EVM testnet.

**Community**

- [Smart Stake](https://injective.smartstake.io/stats) - Network, staking, and validator analytics.
- [Coinhall](https://coinhall.org/) - Market analytics and trading interface.
- [DEX Screener](https://dexscreener.com/injective) - Token and liquidity-pool charts for Injective.
- [Pulsar Finance](https://app.pulsar.finance/portfolio) - Portfolio tracking for Injective assets and positions.
- [CoinGecko](https://www.coingecko.com/en/coins/injective) - INJ market data and ecosystem discovery.
- [CoinMarketCap](https://coinmarketcap.com/currencies/injective/) - INJ market data and exchange information.
- [TFM](https://tfm.com/) - Injective Core analytics and trading tooling with Injective support.
- [Elliptic](https://www.elliptic.co/) - Blockchain analytics and compliance infrastructure.

## Ecosystem Applications

### Exchanges and Trading

- [Injex Finance](https://app.injex.fi/) - Decentralized exchange in the Injective ecosystem.
- [Levana](https://trade.levana.finance/) - Perpetual-futures protocol deployed on Injective.
- [StreamSwap](https://app.streamswap.io/) - Token-streaming and liquidity application.
- [start.cooking](https://start.cooking/swap) - Token-launch and swap application.
- [DackieSwap](https://www.dackieswap.xyz/?chain=inEvm) - Multi-chain DEX with Injective EVM support.
- [Yei Finance](https://inj-swap.yei.finance/) - Swap interface for Injective EVM.
- [Meowtrade](https://www.meowtrades.com/) - Trading application on Injective EVM.

### Lending, Yield, and Stablecoins

- [Agora](https://www.agora.finance/) - Issuer of AUSD and stablecoin infrastructure used in the Injective ecosystem.
- [Elixir](https://elixir.finance/) - Liquidity and synthetic dollar infrastructure.
- [Ethena](https://www.ethena.fi/) - USDe issuer and DeFi integration.
- [Hydro Protocol](https://hydroprotocol.finance/) - Liquid staking and yield protocol native to Injective.
- [Mito](https://mito.fi/) - Automated vaults, launches, and yield strategies.
- [Neptune Finance](https://nept.finance/) - Lending and borrowing protocol native to Injective.
- [Ondo Finance](https://ondo.finance/) - Tokenized asset and yield products integrated with Injective.
- [Pryzm](https://pryzm.zone/) - Yield trading and asset management protocol.
- [Silo Finance](https://app.silo.finance/earn) - Isolated lending markets on Injective EVM.
- [Thetanuts Finance](https://www.thetanuts.finance/) - Options and structured products protocol.
- [Timeswap](https://app.timeswap.io/) - Oracleless lending and borrowing protocol.
- [Accumulated Finance](https://accumulated.finance/stake/inj) - Liquid staking application for INJ.
- [Bondi Finance](https://bondifinance.io/) - DeFi application on Injective EVM.
- [Filament](https://www.filament.finance/) - DeFi protocol listed in the Injective ecosystem.
- [RFY](https://rfy.finance/app) - Yield application on Injective EVM.
- [Stryke](https://www.stryke.xyz/) - Options and liquidity infrastructure on Injective EVM.

### Payments, Assets, and Tokenization

- [Circle USDC](https://www.circle.com/en/usdc) - Native USDC and cross chain transfer infrastructure.
- [Mountain Protocol](https://mountainprotocol.com/) - Issuer of USDM.
- [Noble](https://nobleassets.xyz/) - Native asset issuance infrastructure for the interchain ecosystem.
- [Paxos](https://paxos.com/) - Regulated stablecoin and tokenization infrastructure.
- [PayPal USD](https://www.paypal.com/us/digital-wallet/manage-money/crypto/pyusd) - Dollar stablecoin listed in the Injective ecosystem.
- [Valereum Markets](https://www.vlrm.markets/) - Tokenized market infrastructure.
- [DigiShares](https://digishares.io/) - Whitelabel real estate tokenization platform.
- [Realmint](https://app.realmint.io/discover) - Real world asset marketplace.
- [Kado](https://app.kado.money/) - Fiat on ramp with Injective support.
- [Transak](https://transak.com/) - Fiat on ramp and off ramp infrastructure.
- [Mercuryo](https://mercuryo.io/on-off-ramps/) - Fiat on ramp and off ramp provider.

### NFTs, Identity, and Consumer Apps

- [.inj Name Service](https://inj.space.id/) - Domain name service for Injective addresses.
- [Dagora](https://dagora.xyz/) - NFT marketplace in the Injective ecosystem.
- [Ninja Blaze](https://blaze.ninja/) - Consumer application built on Injective.
- [Rarible](https://rarible.com/injective) - NFT marketplace integration for Injective EVM.
- [SA World](https://saworld.io/) - Consumer and gaming application listed in the Injective ecosystem.
- [Talis](https://talis.art/) - NFT marketplace with Injective support.
- [Jecta](https://www.jectadotai.com/) - AI focused application in the Injective ecosystem.

### Developer and Application Infrastructure

- [Caldera](https://caldera.xyz/) - Rollup and application chain infrastructure.
- [Clusters](https://clusters.xyz/) - Cross chain naming and identity infrastructure.
- [Notifi](https://notifi.network/) - Notification and messaging infrastructure.
- [Ormi](https://ormilabs.com/) - Data and indexing infrastructure for EVM applications.
- [Palmera](https://www.palmeradao.xyz/) - Multisig and organization tooling for EVM applications.
- [Rarible Protocol](https://rarible.org/) - NFT infrastructure for EVM applications.
- [Tenderly](https://tenderly.co/) - EVM simulation, debugging, and observability.
- [thirdweb](https://thirdweb.com/) - Smart-contract and application development platform.
- [The Graph](https://thegraph.com/) - Decentralized indexing and query infrastructure.

## Learning and Research

**Official**

- [Injective Learn](https://injective.com/learn) - Learning center for Injective, DeFi, and on chain finance.
- [Injective Research](https://injective.com/research) - Research on markets, tokenization, stablecoins, and blockchain infrastructure.
- [Injective Blog](https://injective.com/blog) - Protocol releases, integrations, tutorials, and ecosystem news.
- [Injective YouTube](https://www.youtube.com/@injective) - Workshops, explainers, ecosystem sessions, and event recordings.

**Community**

- [30 Days of Solidity: Injective Track](https://www.youtube.com/playlist?list=PL3gCWoU4wyU0Ku2BBT3iuBpweou5UC-RQ) - Solidity course covering Injective precompiles and application development.
- [Injective Workshop Playlist](https://www.youtube.com/playlist?list=PLTS_stt4XpDC3isu2cnBGpfviy3y7_Egu) - Workshops on SDKs, Wasm VM, infrastructure, market making, IBC, and integrations.
- [Build a DEX with dAppBuilder](https://injective.com/blog/how-to-build-a-dex-on-injective-using-i-build-comprehensive-i-build-creators-guide) - No code guide to creating an Injective DEX.
- [Wasm VM Documentation](https://cosmwasm.com/) - Language, architecture, and smart-contract documentation.
- [Injective Core SDK Documentation](https://docs.cosmos.network/) - Framework documentation underlying Injective's native application layer.
- [IBC Documentation](https://ibcprotocol.dev/) - Developer documentation for interchain communication.

## Community and Programs

**Official**

- [Injective Community](https://injective.com/community) - Community portal and contribution paths.
- [Injective Events](https://injective.com/events) - Hackathons, meetups, developer events, and ecosystem sessions.
- [Injective Ambassadors](https://injective.com/ambassadors) - Community contribution program.
- [Injective Governance](https://injhub.com/governance/) - Governance proposals and voting.
- [Injective Discord](https://discord.gg/injective) - Community and developer discussion.
- [Developer Telegram](https://t.me/+8Y_0HOFLhnRlZDU9) - Developer support channel.
- [Injective X](https://x.com/Injective) - Protocol announcements and ecosystem updates.
- [Injective Brand Kit](https://github.com/InjectiveLabs/branding) - Logos and media assets.

**Community**

- [Injective Nova](https://injectivenova.com/) - AI-native Web3 builder program.
- [Outlier Ventures Injective Catalyst](https://outlierventures.io/base-camp/ecosystem-builder-catalyst/) - Accelerator program for teams building in the Injective ecosystem.

## Related Awesome Lists

- [Awesome Cosmos](https://github.com/cosmos/awesome-cosmos) - Cosmos SDK, IBC, applications, and ecosystem resources.
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust) - Rust libraries, tools, applications, and learning resources.
- [Awesome Blockchain Rust](https://github.com/rust-in-blockchain/awesome-blockchain-rust) - Rust projects and resources for blockchain development.
- [Awesome Go](https://github.com/avelino/awesome-go) - Go libraries and tooling relevant to native chain and service development.
- [Awesome Ethereum Security](https://github.com/crytic/awesome-ethereum-security) - EVM security tools, research, and best practices.
- [Awesome Ethereum](https://github.com/bekatom/awesome-ethereum) - Ethereum and EVM development resources.

## Contributing

Contributions are welcome. Please open a pull request that adds, updates, or
removes one resource at a time.

Before submitting an entry, confirm that it:

- Is directly useful to people learning, building, integrating, operating, or
  exploring Injective.
- Is public, functional, documented, and not archived or deprecated.
- Has been personally used or manually verified by the contributor.
- Is placed in the most specific category.
- Uses the format `- [Name](https://example.com/) - Concise, factual description.`
- Uses an objective description without price claims, superlatives, referral
  links, token promotion, or investment language.
- Includes an open-source license when the entry is a code project.

Maintainers may remove resources that are unavailable, abandoned, unsafe,
duplicative, or no longer useful. Mature projects with little recent activity
may remain when they are stable, documented, and still functional.

## License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
