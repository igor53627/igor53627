*Here is a table of contents since pin functionality is quite basic when there are many projects; scroll categories and projects or use 搜索*

### Research on Ethereum Execution Client

| Project | Description |
|---------|-------------|
| [ubt-rs](https://github.com/igor53627/ubt-rs) | Rust implementation of Unified Binary Trie; reference EIP-7864 data structure for efficient Ethereum state storage and migration experiments. |
| [ubt-exex](https://github.com/igor53627/ubt-exex) | Reth execution extension for UBT; plugs a UBT-backed state engine into Reth to evaluate EIP-7864 in a real client. |
| [reth-ubt-migration](https://github.com/igor53627/reth-ubt-migration) | Migration tooling for UBT in Reth; utilities to convert existing Reth state to UBT and benchmark migration performance. |
| [mdbx-rs-releases](https://github.com/igor53627/mdbx-rs-releases) | MDBX releases for UBT; pre-built binaries and release artifacts for the Rust MDBX implementation. |
| [reth-pse](https://github.com/igor53627/reth-pse) | [private] Privacy and scaling oriented fork of Reth. |
| [mdbx-rs](https://github.com/igor53627/mdbx-rs) | [private] A pure Rust implementation of libmdbx, an extremely fast, compact, and powerful embedded transactional key-value database |

### Private Information Retrieval (PIR)

| Project | Description |
|---------|-------------|
| [plinko-rs](https://github.com/igor53627/plinko-rs) | Practical Rust implementation of the PLINKO PIR protocol with data extraction from Sepolia and hint generation; built to feed real-world PIR queries from on-chain Ethereum data. |
| [plinko-research](https://github.com/igor53627/plinko-research) | Research and experiments on PLINKO PIR; prototypes, benchmarks, and design notes exploring latency/bandwidth trade-offs and deployment models. |
| [inspire-rs](https://github.com/igor53627/inspire-rs) | Rust implementation of the INSPIRE PIR protocol; focuses on production-ready primitives and integration with Ethereum-style datasets. |
| [inspire-exex](https://github.com/igor53627/inspire-exex) | Two-Lane InsPIRe PIR for private Ethereum state queries with honest-but-curious server ^_^ |

### Obfuscation

| Project | Description |
|---------|-------------|
| [tlos](https://github.com/igor53627/tlos) | TLOS: Topology-Lattice Obfuscation for Smart Contracts |
| [larc](https://github.com/igor53627/larc) | [archived] LARC: LWE-Activated Reversible Contracts - functionally equivalent to symmetric encryption; use commit-reveal instead (see [a16z/auction-zoo](https://github.com/a16z/auction-zoo)). |
| [tlo](https://github.com/igor53627/tlo) | [archived] TLO: Topology-Lattice Obfuscation - superseded by LARC (topology adds no on-chain security). |
| [ma-dai-shi-io](https://github.com/igor53627/ma-dai-shi-io) | Honeypot for Ma-Da-Shi Quasi-linear indistinguishability obfuscation from evasive LWE (Ma-Dai-Shi 2025). |
| [circuit-mixing-research](https://github.com/igor53627/circuit-mixing-research) | [private] Experimental lab for understanding how far we can push pure circuit mixing (without heavy cryptography) against compression and structural attacks. |

### TOR & Privacy Infrastructure

| Project | Description |
|---------|-------------|
| [tor-ethereum-ecosystem](https://github.com/igor53627/tor-ethereum-ecosystem) | Ethereum ecosystem tools accessible over TOR; curated configs and examples for running RPCs, explorers, and infra as Tor onion services. |
| [webtor-rs](https://github.com/igor53627/webtor-rs) | Rust library for TOR web services; simplifies exposing HTTP APIs as onion services and managing Tor integration in Rust backends. |
| [onion-service-monitor](https://github.com/igor53627/onion-service-monitor) | Monitoring tool for onion services; tracks uptime, reachability, and health of Tor endpoints used by privacy-focused infrastructure. |
| [blockscout-onion](https://github.com/igor53627/blockscout-onion) | Blockscout blockchain explorer over TOR; packages a full Blockscout stack behind an onion service for censorship-resistant chain analytics. |
| [gethrelay](https://github.com/igor53627/gethrelay) | Geth relay service for TOR; enables Ethereum node communication over the Tor network. |

### Smart Contracts & EVM

| Project | Description |
|---------|-------------|
| [ipfe.sol](https://github.com/igor53627/ipfe.sol) | IPFE.sol: Inner Product Functional Encryption for EVM using bn256 precompiles |
| [fair.sol](https://github.com/igor53627/fair.sol) | Fair.sol: Stablecoin with PoA ≈ 1.0 — fair liquidation mechanism that eliminates front-running and value extraction |
| [liq](https://github.com/igor53627/liq) | LIQ Flash Mint: Ultra Gas-Optimized ERC-3156 Flash Loans |
| [iconregistry.eth](https://github.com/igor53627/iconregistry.eth) | Icon registry smart contract; on-chain mapping for asset/contract icons to improve UX for wallets, explorers, and dapps. |
| [evm-glue](https://github.com/igor53627/evm-glue) | Fork of EVM Glue with optimization for Fusaka; tuned for performance and experimentation with custom EVM backends. |
| [voidgun](https://github.com/igor53627/voidgun) | Drop-in RPC privacy for Ethereum. Proxy architecture that turns existing multi-chain wallets into private transaction endpoints. |
| [yolo](https://github.com/igor53627/yolo) | [private] Privacy-preserving yield-bearing stablecoin on Ethereum L1; explores fully collateralized stablecoin design with hidden balances and flows. |

### Private

*These repos are not publicly available. Links are used by Player 53627 for easy navigation.*

| Project | Description |
|---------|-------------|
| [reth-relay](https://github.com/igor53627/reth-relay) | Privacy-focused P2P relay for reth with Tor/I2P support. |
| [amp-config](https://github.com/igor53627/amp-config) | Global config for Amp; personal workspace, presets, and automation for AI-assisted development. |
| [orgmode](https://github.com/igor53627/orgmode) | Personal knowledge base; long-term research notes, design docs, and project planning in Emacs Org-mode. |
| [ex-exex](https://github.com/igor53627/ex-exex) | Blockscout-compatible indexer as a Reth sidecar; consumes Reth execution data to power Blockscout without a separate indexing stack. |
| [blockscout-proxy](https://github.com/igor53627/blockscout-proxy) | Caddy + Nodecore + TIG stack for Blockscout; production-oriented reverse proxy, logging, and observability layer for Blockscout deployments. |
| [fast-frontend](https://github.com/igor53627/fast-frontend) | High-performance frontend framework; optimized UI rendering for blockchain applications. |
