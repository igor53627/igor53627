## Privacy & cryptography for Ethereum

Research and implementations across private information retrieval, lattice cryptography, obfuscation, and Tor-based infrastructure.

> **Note** — these are research projects, much of the code AI-assisted. Not security-audited and not intended for production use without independent review.

---

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
      <td>Rust implementation of the Unified Binary Trie (EIP-7864) — a reference state-tree structure for efficient Ethereum state storage and migration experiments.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ubt-exex">ubt-exex</a></td>
      <td>Reth execution extension that plugs a UBT-backed state engine into a real client to evaluate EIP-7864 end-to-end.</td>
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
      <td>Practical Rust implementation of the PLINKO PIR protocol; extracts Sepolia state and generates hints to serve real PIR queries over on-chain Ethereum data.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/plinko-research">plinko-research</a></td>
      <td>Research and experiments on PLINKO PIR; prototypes, benchmarks, and design notes exploring latency/bandwidth trade-offs and deployment models.</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/inspire-rs">inspire-rs</a></td>
      <td>Rust implementation of the INSPIRE PIR protocol, with production-ready primitives and integration for Ethereum-style datasets.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/inspire-exex">inspire-exex</a></td>
      <td>Two-lane InsPIRe PIR for private Ethereum state queries under an honest-but-curious server.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/morphogenesis">morphogenesis</a></td>
      <td>A 2-server, GPU-accelerated DPF-PIR covering the full Ethereum state.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/rms24-rs">rms24-rs</a></td>
      <td>RMS24 single-server PIR in Rust, with optional CUDA acceleration and KeywordPIR benchmarks.</td>
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
      <td>Curated configs and examples for running Ethereum RPCs, explorers, and infrastructure as Tor onion services.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/webtor-rs">webtor-rs</a></td>
      <td>Rust library for exposing HTTP APIs as Tor onion services and managing Tor integration in Rust backends.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/onion-service-monitor">onion-service-monitor</a></td>
      <td>Uptime, reachability, and health monitoring for the Tor onion-service endpoints behind privacy-focused infrastructure.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/blockscout-onion">blockscout-onion</a></td>
      <td>Full Blockscout explorer stack packaged behind a Tor onion service for censorship-resistant chain analytics.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/gethrelay">gethrelay</a></td>
      <td>Relay that carries Geth/Ethereum node communication over the Tor network.</td>
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
      <td>Inner-product functional encryption for the EVM via bn256 precompiles, enabling private computation over encrypted on-chain data.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/fair.sol">fair.sol</a></td>
      <td>Fair.sol: Stablecoin with PoA ~= 1.0 - fair liquidation mechanism that eliminates front-running and value extraction</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/liq">liq</a></td>
      <td>Ultra gas-optimized ERC-3156 flash loans for atomic arbitrage and liquidation bots.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/iconregistry.eth">iconregistry.eth</a></td>
      <td>On-chain registry mapping assets and contracts to icons, improving UX for wallets, explorers, and dapps.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-lwe-math">evm-lwe-math</a></td>
      <td>Gas-optimized LWE inner-product primitives for on-chain lattice cryptography; supports both prime and power-of-two moduli.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-linear-accumulator">evm-linear-accumulator</a></td>
      <td>Seed-derived linear hash accumulator over Z_q for trace integrity, state accumulators, and fraud proofs.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-mhf">evm-mhf</a></td>
      <td>EVM-native memory-hard function primitive.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-lattice-pow">evm-lattice-pow</a></td>
      <td>Standalone LatticePoW challenge primitive for the EVM.</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-regev">evm-regev</a></td>
      <td>Additively homomorphic Regev (LWE) encryption for the EVM; cheapest-by-gas additive HE, plausibly post-quantum, for aggregate-reveal apps (hidden tallies, sealed bids, game scores).</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/lwe-jump-table">lwe-jump-table</a></td>
      <td>LWE-based control-flow flattening for the EVM; encrypts branch destinations as LWE ciphertexts for on-chain strategy obfuscation (n=768, q=4096, ~130-bit PQ security).</td>
    </tr>
    <tr>
      <td nowrap><a href="https://github.com/igor53627/ma-dai-shi-io">ma-dai-shi-io</a></td>
      <td>Quasi-linear iO (Ma–Dai–Shi 2025): Rust library, Lean 4 proofs, and an on-chain seed-phrase challenge demo.</td>
    </tr>
    <!--
    <tr>
      <td nowrap><a href="https://github.com/igor53627/evm-glue">evm-glue</a></td>
      <td>Fork of EVM Glue with optimization for Fusaka; tuned for performance and experimentation with custom EVM backends.</td>
    </tr>
    -->
    <tr>
      <td nowrap><a href="https://github.com/igor53627/voidgun">voidgun</a></td>
      <td>Drop-in RPC privacy for Ethereum — a proxy that turns existing multi-chain wallets into private transaction endpoints.</td>
    </tr>
  </tbody>
</table>
