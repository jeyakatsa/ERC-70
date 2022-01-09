# New-ERC Token Research & Development

### Estimated Roadmap:

#### Month-By-Month *(2022)*
January:
- Complete First Draft of EIP, create pull request/publish. *[Status: **[Complete](https://github.com/ethereum/EIPs/pull/4649)**]*.
- Begin building Java Abstraction Layer. *[Status: [In-Development](https://github.com/jeyakatsa/New-ERC-Token-Java-Abstraction)]*
- Complete Final Draft of EIP. *[Status: Announced]*
- *More TBA(To-Be-Announced)*

#### Year-By-Year
2022-2024: 
- ***Java*** Abstraction Layer Build. *[Status: [In-Development](https://github.com/jeyakatsa/New-ERC-Token-Java-Abstraction)]*

2024-2025:
- ***Rust*** Abstraction Layer Build. *[Status: Announced]*

2025-2026: 
- ***Python*** Abstraction Layer Build. *[Status: Announced]*

2026-2027: 
- ***Go*** Abstraction Layer Build. *[Status: Announced]*

## EIP (Ethereum Improvement Proposal) Notes/References:
### [Guideline](https://eips.ethereum.org/EIPS/eip-1)
### [Pull-Request](https://github.com/ethereum/EIPs)

## General Notes/References:
### [Intro-To-Smart-Contracts-in-Solidity](https://docs.soliditylang.org/en/v0.8.10/introduction-to-smart-contracts.html)
### [WASM](https://medium.com/chainsafe-systems/ethereum-2-0-a-complete-guide-ewasm-394cac756baf)
Important takes from the above medium post:
- One of the central aspects of the Ethereum 2.0 update will be a transition from the EVM to Ewasm.
- The WASM team aims to implement an Ewasm backend for the Solidity compiler and to provide instructions and a ***library for writing contracts in C and Rust*** *(this library could also be expanded to parlay with this current ERC proposed languages [Java, Go, Python, etc])*.
### [Layer-2](https://github.com/ethereum/ethereum-org-website/blob/dev/src/content/developers/docs/scaling/layer-2-rollups/index.md)

---------------------------------------------------

### Abstraction:

#### *While building the [Light Client Infrastructure for Teku](https://github.com/jeyakatsa/teku/tree/master/light-client), these are the said discoveries:*

- Clients serve as arbiters or "bridges" to the Ethereum main chain.
- Such clients offer differing languages that connect with the transactions offered on Ethereum, thus concluding if said clients can offer a base layer capable of inferring transactions from Ethereum's base layer, can tokens created in said languages also offer the same results?
