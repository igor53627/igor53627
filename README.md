### Research on Ethereum Execution Client

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ubt-rs">ubt-rs</a></td>
      <td>Rust implementation of Unified Binary Trie; reference EIP-7864 data structure for efficient Ethereum state storage and migration experiments.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ubt-exex">ubt-exex</a></td>
      <td>Reth execution extension for UBT; plugs a UBT-backed state engine into Reth to evaluate EIP-7864 in a real client.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/reth-ubt-migration">reth-ubt-migration</a></td>
      <td>Migration tooling for UBT in Reth; utilities to convert existing Reth state to UBT and benchmark migration performance.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/mdbx-rs-releases">mdbx-rs-releases</a></td>
      <td>Prebuilt static and dynamic libraries for mdbx-rs; Linux x86_64 and macOS ARM64 binaries.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/mdbx-rs">mdbx-rs</a></td>
      <td>[alpha] Pure Rust implementation of libmdbx; zero C dependencies, binary-compatible with existing libmdbx databases. Not for production use.</td>
    </tr>
    -->
  </tbody>
</table>

### Private Information Retrieval (PIR)

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/plinko-rs">plinko-rs</a></td>
      <td>Practical Rust implementation of the PLINKO PIR protocol with data extraction from Sepolia and hint generation; built to feed real-world PIR queries from on-chain Ethereum data.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/plinko-research">plinko-research</a></td>
      <td>Research and experiments on PLINKO PIR; prototypes, benchmarks, and design notes exploring latency/bandwidth trade-offs and deployment models.</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/inspire-rs">inspire-rs</a></td>
      <td>Rust implementation of the INSPIRE PIR protocol; focuses on production-ready primitives and integration with Ethereum-style datasets.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/inspire-exex">inspire-exex</a></td>
      <td>Two-Lane InsPIRe PIR for private Ethereum state queries with honest-but-curious server.</td>
    </tr>
  </tbody>
</table>

### Obfuscation

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/tlos">tlos</a></td>
      <td>Topology-Lattice Obfuscation for Smart Contracts; four-layer security (topology, LWE, wire binding, puzzle) protects low-entropy secrets on-chain. Enables password-gated vaults, sealed-bid auctions, and on-chain treasure hunts.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ma-dai-shi-io">ma-dai-shi-io</a></td>
      <td>Quasi-linear iO implementation (Ma-Dai-Shi 2025); Rust library, Lean 4 proofs, and on-chain seed phrase challenge demo.</td>
    </tr>
  </tbody>
</table>

### Tor & Privacy Infrastructure

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/tor-ethereum-ecosystem">tor-ethereum-ecosystem</a></td>
      <td>Ethereum ecosystem tools accessible over Tor; curated configs and examples for running RPCs, explorers, and infra as onion services.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/webtor-rs">webtor-rs</a></td>
      <td>Rust library for Tor web services; simplifies exposing HTTP APIs as onion services and managing Tor integration in Rust backends.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/onion-service-monitor">onion-service-monitor</a></td>
      <td>Monitoring tool for onion services; tracks uptime, reachability, and health of Tor endpoints used by privacy-focused infrastructure.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/blockscout-onion">blockscout-onion</a></td>
      <td>Blockscout blockchain explorer over Tor; packages a full Blockscout stack behind an onion service for censorship-resistant chain analytics.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/gethrelay">gethrelay</a></td>
      <td>Geth relay service for Tor; enables Ethereum node communication over the Tor network.</td>
    </tr>
  </tbody>
</table>

### Smart Contracts & EVM

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ipfe.sol">ipfe.sol</a></td>
      <td>Inner Product Functional Encryption for EVM using bn256 precompiles; enables private computation over encrypted on-chain data.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/fair.sol">fair.sol</a></td>
      <td>Fair.sol: Stablecoin with PoA ~= 1.0 - fair liquidation mechanism that eliminates front-running and value extraction</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/liq">liq</a></td>
      <td>Ultra gas-optimized ERC-3156 flash loans; minimizes gas costs for atomic arbitrage and liquidation bots.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/iconregistry.eth">iconregistry.eth</a></td>
      <td>Icon registry smart contract; on-chain mapping for asset/contract icons to improve UX for wallets, explorers, and dapps.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-glue">evm-glue</a></td>
      <td>Fork of EVM Glue with optimization for Fusaka; tuned for performance and experimentation with custom EVM backends.</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/voidgun">voidgun</a></td>
      <td>Drop-in RPC privacy for Ethereum. Proxy architecture that turns existing multi-chain wallets into private transaction endpoints.</td>
    </tr>
  </tbody>
</table>

### Private

*These repos are not publicly available. Links are used by Player 53627 for easy navigation.*

<table>
  <thead>
    <tr>
      <th align="left">Project</th>
      <th align="left">Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/circuit-mixing-research">circuit-mixing-research</a></td>
      <td>Experimental lab for understanding how far we can push pure circuit mixing (without heavy cryptography) against compression and structural attacks.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/yolo">yolo</a></td>
      <td>Privacy-preserving yield-bearing stablecoin on Ethereum L1; explores fully collateralized stablecoin design with hidden balances and flows.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/reth-relay">reth-relay</a></td>
      <td>Privacy-focused P2P relay for reth with Tor/I2P support.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ex-exex">ex-exex</a></td>
      <td>Blockscout-compatible indexer as a Reth sidecar; consumes Reth execution data to power Blockscout without a separate indexing stack.</td>
    </tr>
    -->
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/blockscout-proxy">blockscout-proxy</a></td>
      <td>Caddy + Nodecore + TIG stack for Blockscout; production-oriented reverse proxy, logging, and observability layer for Blockscout deployments.</td>
    </tr>
    -->
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/fast-frontend">fast-frontend</a></td>
      <td>High-performance frontend framework; optimized UI rendering for blockchain applications.</td>
    </tr>
    -->
  </tbody>
</table>
