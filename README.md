# A New ERC Token Proposal

##### *Work to commence after [Light Client Infrastructure for Teku](https://github.com/jeyakatsa/teku/tree/master/light-client) is completed.*
-----------------------------------------------------------------

> *What if more developers with desires to create tokens in their desired languages could be easily onboarded into the Ethereum ecosystem (developers with deep knowledge in their favored languages [Java, Go, Python, Rust, etc])?*

## Currently...

*Ethereum currencies can only be created with one language, Solidity*. 

As gathered, the main currencies that power the Ethereum ecosystem are ERC-20 tokens (with ERC-223 and ERC-777 tokens further improving upon ERC-20's flaws). With the plethora of currencies that have burgeoned Ethereum's thriving ecosystem, the ecosystem could still be farther expanded to onboard millions of tokens (and thousands of more developers) into the Ethereum ecosystem.

## Solution

An Ethereum currency capable of being created in any language feasible: *a **New-ERC Token** (exact ERC standard to be determined via EIP metrics)*.

*According to the [Ethereum-2 Roadmap](https://docs.ethhub.io/ethereum-roadmap/ethereum-2.0/eth2.0-teams/teams-building-eth2.0/), there are many more clients and languages available on Ethereum 2, but for now (due to experimentation purposes), this is the abstraction layer proposed to be worked on via the Architecture & Estimated Roadmap.*

### Architecture:

![](https://i.imgur.com/PovmQ4X.jpg)

### Estimated Roadmap:

- Year 2022-2024 (New-ERC Token Java Abstraction Layer Build)
*If the Java Abstraction layer build is successful, work on the next layers will commence.*
- Year 2024-2025 (New-ERC Token Rust Abstraction Layer Build)
- Year 2025-2026 (New-ERC Token Python Abstraction Layer Build)
- Year 2026-2027 (New-ERC Token Go Abstraction Layer Build)

| ETH2 Client   | Language     | Team                |
|:--------------|:------------ |:------------------- |
| Teku          | Java         | Consensys           |
| Lighthouse    | Rust         | Sigma Prime         |
| Trinity       | Python       | Ethereum Foundation |
| Prysm         | Go           | Prysmatic Labs      |

### ERC-20 tokens vs. Fiat currencies vs. New-ERC tokens:

![](https://i.imgur.com/EanU6S8.jpg)

ERC-20 tokens in their current forms act not only as currencies, but are mostly used as investment contracts whereas Fiat currencies are used solely as exchange barters for goods and services.

New-ERC tokens are encapsulated to act as Fiat currencies, but with a twist... The tokens are not to be "bought and sold" via fiat-on-ramp exchanges but rather, only exchanged or "swapped" via decentralized exchanges like Uniswap, etc. *Thus, their market caps will rise and fall based on the exchange rates agreed upon*. 

The goal for New-ERC tokens are for them to be exchanged into and out of both ERC-20 tokens and Fiat currencies without the act of "buying and selling" the tokens.

### Exchange Rate Mechanics:

***New-ERC tokens will act as "Personal Currencies"*** so in order for them to be successfully exchanged, they will need the consent of both parties *(like trading one NFT for another OR specifically speaking, trading 1 Yuan for 1 Dollar, or 50 Yuans for 1 Dollar, etc)*.

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
