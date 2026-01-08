### Research on Ethereum Execution Client

| Project | Description |
|---------|-------------|
| [ubt-rs](https://github.com/igor53627/ubt-rs) | Rust implementation of Unified Binary Trie; reference EIP-7864 data structure for efficient Ethereum state storage and migration experiments. |
| [ubt-exex](https://github.com/igor53627/ubt-exex) | Reth execution extension for UBT; plugs a UBT-backed state engine into Reth to evaluate EIP-7864 in a real client. |
| [reth-ubt-migration](https://github.com/igor53627/reth-ubt-migration) | Migration tooling for UBT in Reth; utilities to convert existing Reth state to UBT and benchmark migration performance. |
| [mdbx-rs-releases](https://github.com/igor53627/mdbx-rs-releases) | Prebuilt static and dynamic libraries for mdbx-rs; Linux x86_64 and macOS ARM64 binaries. |
| [mdbx-rs](https://github.com/igor53627/mdbx-rs) | [alpha] Pure Rust implementation of libmdbx; zero C dependencies, binary-compatible with existing libmdbx databases. Not for production use. |

### Private Information Retrieval (PIR)

| Project | Description |
|---------|-------------|
| [plinko-rs](https://github.com/igor53627/plinko-rs) | Practical Rust implementation of the PLINKO PIR protocol with data extraction from Sepolia and hint generation; built to feed real-world PIR queries from on-chain Ethereum data. |
| [plinko-research](https://github.com/igor53627/plinko-research) | Research and experiments on PLINKO PIR; prototypes, benchmarks, and design notes exploring latency/bandwidth trade-offs and deployment models. |
| [inspire-rs](https://github.com/igor53627/inspire-rs) | Rust implementation of the INSPIRE PIR protocol; focuses on production-ready primitives and integration with Ethereum-style datasets. |
| [inspire-exex](https://github.com/igor53627/inspire-exex) | Two-Lane InsPIRe PIR for private Ethereum state queries with honest-but-curious server. |

### Obfuscation

| Project | Description |
|---------|-------------|
| [tlos](https://github.com/igor53627/tlos) | Practical circuit obfuscation for EVM; four-layer security (topology, LWE, wire binding, puzzle) protects low-entropy secrets on-chain. ~3.3M gas for 128 gates, 99.6% storage reduction. Enables password-gated vaults, sealed-bid auctions, and on-chain treasure hunts. |
| [ma-dai-shi-io](https://github.com/igor53627/ma-dai-shi-io) | Quasi-linear iO implementation (Ma-Dai-Shi 2025); Rust library, Lean 4 proofs, and on-chain seed phrase challenge demo. |

### Tor & Privacy Infrastructure

| Project | Description |
|---------|-------------|
| [tor-ethereum-ecosystem](https://github.com/igor53627/tor-ethereum-ecosystem) | Ethereum ecosystem tools accessible over Tor; curated configs and examples for running RPCs, explorers, and infra as onion services. |
| [webtor-rs](https://github.com/igor53627/webtor-rs) | Rust library for Tor web services; simplifies exposing HTTP APIs as onion services and managing Tor integration in Rust backends. |
| [onion-service-monitor](https://github.com/igor53627/onion-service-monitor) | Monitoring tool for onion services; tracks uptime, reachability, and health of Tor endpoints used by privacy-focused infrastructure. |
| [blockscout-onion](https://github.com/igor53627/blockscout-onion) | Blockscout blockchain explorer over Tor; packages a full Blockscout stack behind an onion service for censorship-resistant chain analytics. |
| [gethrelay](https://github.com/igor53627/gethrelay) | Geth relay service for Tor; enables Ethereum node communication over the Tor network. |

### Smart Contracts & EVM

| Project | Description |
|---------|-------------|
| [ipfe.sol](https://github.com/igor53627/ipfe.sol) | Inner Product Functional Encryption for EVM using bn256 precompiles; enables private computation over encrypted on-chain data. |
| [fair.sol](https://github.com/igor53627/fair.sol) | Fair.sol: Stablecoin with PoA ≈ 1.0 — fair liquidation mechanism that eliminates front-running and value extraction |
| [liq](https://github.com/igor53627/liq) | Ultra gas-optimized ERC-3156 flash loans; minimizes gas costs for atomic arbitrage and liquidation bots. |
| [iconregistry.eth](https://github.com/igor53627/iconregistry.eth) | Icon registry smart contract; on-chain mapping for asset/contract icons to improve UX for wallets, explorers, and dapps. |
| [evm-glue](https://github.com/igor53627/evm-glue) | Fork of EVM Glue with optimization for Fusaka; tuned for performance and experimentation with custom EVM backends. |
| [voidgun](https://github.com/igor53627/voidgun) | Drop-in RPC privacy for Ethereum. Proxy architecture that turns existing multi-chain wallets into private transaction endpoints. |

### Private

*These repos are not publicly available. Links are used by Player 53627 for easy navigation.*

| Project | Description |
|---------|-------------|
| [circuit-mixing-research](https://github.com/igor53627/circuit-mixing-research) | Experimental lab for understanding how far we can push pure circuit mixing (without heavy cryptography) against compression and structural attacks. |
| [yolo](https://github.com/igor53627/yolo) | Privacy-preserving yield-bearing stablecoin on Ethereum L1; explores fully collateralized stablecoin design with hidden balances and flows. |
| [reth-relay](https://github.com/igor53627/reth-relay) | Privacy-focused P2P relay for reth with Tor/I2P support. |
| [ex-exex](https://github.com/igor53627/ex-exex) | Blockscout-compatible indexer as a Reth sidecar; consumes Reth execution data to power Blockscout without a separate indexing stack. |
| [blockscout-proxy](https://github.com/igor53627/blockscout-proxy) | Caddy + Nodecore + TIG stack for Blockscout; production-oriented reverse proxy, logging, and observability layer for Blockscout deployments. |
| [fast-frontend](https://github.com/igor53627/fast-frontend) | High-performance frontend framework; optimized UI rendering for blockchain applications. |
