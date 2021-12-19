# [ERC-70 Token Proposal](https://ethresear.ch/t/erc-70-token-proposal/11540)

#### This project is set to commence after [Light-Client-Server for Teku](https://github.com/jeyakatsa/teku/tree/master/light-client) build is completed.

## Problem

As gathered, the main currencies that power the Ethereum ecosystem are ERC-20 tokens (with ERC-223 and ERC-777 tokens further improving upon ERC-20's flaws). With the plethora of currencies that have burgeoned Ethereum's thriving ecosystem, there is still a major flaw hindering Ethereum's evolution: 

*Ethereum currencies can only be created with one language, Solidity*.

## Solution

An Ethereum currency capable of being created in any language feasible: ***the ERC-70 Token***.

*According to the [Ethereum-2 Roadmap](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth2.0-teams/teams-building-eth2.0/), there are many more clients and languages available on Ethereum 2, but for now (due to experimentation purposes), this is the abstraction layer proposed to be worked on via the Architecture & Estimated Roadmap:*

### Architecture:

![](https://i.imgur.com/ezpWKnw.jpg)


### Estimated Roadmap:

- 2022-2024 (ERC-70 Java Abstraction Layer Build)
*If the Java Abstraction layer build is successful, work on the next layers will commence...*
- 2024-2025 (ERC-70 Rust Abstraction Layer Build)
- 2025-2026 (ERC-70 Python Abstraction Layer Build)
- 2026-2027 (ERC-70 Go Abstraction Layer Build)



| ETH2 Client   | Language     | Team                |
|:--------------|:------------ |:------------------- |
| Teku          | Java         | Consensys           |
| Lighthouse    | Rust         | Sigma Prime         |
| Trinity       | Python       | Ethereum Foundation |
| Prysm         | Go           | Prysmatic Labs      |

### ERC-20 tokens vs. Fiat currencies vs. ERC-70 tokens:

![](https://i.imgur.com/2bmvZj8.jpg)

ERC-20 tokens in their current forms act not only as currencies, but are mostly used as investment contracts whereas Fiat currencies are used solely as exchange barters for goods and services.

ERC-70 tokens are encapsulated to act as Fiat currencies, but with a twist... *ERC-70 token market caps are envisioned to rise and fall based on the exchange rates agreed upon*. ERC-70 tokens are envisioned not to be "bought and sold" via fiat-on-ramp exchanges but rather, only exchanged or "swapped" via decentralized exchanges like Uniswap, etc.

The goal for ERC-70 tokens are for them to be exchanged into and out of both ERC-20 tokens and Fiat currencies without the act of "buying and selling" the tokens.

### Exchange Rate Mechanics:

***ERC-70 tokens will act as "Personal Currencies"*** so in order for them to be successfully exchanged, they will need the consent of both parties *(like trading one NFT for another OR specifically speaking, trading 1 Yuan for 1 Dollar, or 50 Yuans for 1 Dollar, etc)*.

**Scenario 1:** *Party A agrees to exchange 1 of their Tokens for 1 Token from Party B.*

> ***Before Exchange***
> 
> | Party A Token              | Party B Token              |
> | -------------------------- | -------------------------- |
> | Market Cap = 2kUSD         | Market Cap = 1kUSD         |
> | Tokens In Circulation = 1k | Tokens In Circulation = 1k |
> | 1 Token = 2USD             | 1 Token = 1USD             |
> 
> ***After Exchange***
> 
> | Party A Token              | Party B Token              |
> | -------------------------- | -------------------------- |
> | Market Cap = 1.998kUSD     | Market Cap = 1.002kUSD     |
> | Tokens In Circulation = 1k | Tokens In Circulation = 1k |
> | 1 Token = 1.998USD         | 1 Token = 1.002USD         |

**Scenario 2:** *Party A agrees to exchange 50 of their Tokens for 1 Token from Party B.*

> ***Before Exchange***
> 
> | Party A Token              | Party B Token              |
> | -------------------------- | -------------------------- |
> | Market Cap = 2kUSD         | Market Cap = 1kUSD         |
> | Tokens In Circulation = 1k | Tokens In Circulation = 1k |
> | 1 Token = 2USD             | 1 Token = 1USD             |
> 
> ***After Exchange***
> 
> | Party A Token                 | Party B Token                  |
> | ----------------------------- | ------------------------------ |
> | Market Cap = 1.900kUSD        | Market Cap = 1.100kUSD         |
> | Tokens In Circulation = .951k | Tokens In Circulation = 1.049k |
> | 1 Token = 1.997USD            | 1 Token = 1.048USD                 |

--------------------------------------------------
***Note: This proposal is still early in its development as more information, rules and architecture is gathered and is ever so evolving thus, questions, thoughts and feedback are very welcome.***

*As previously incepted from the [Light Client Token Creation Proposal](https://ethresear.ch/t/light-client-custom-token-creation-proposal/11433).*

##### [HackMd Post](https://hackmd.io/SFNfIcFcRLG5jge6N0onmQ?view)
