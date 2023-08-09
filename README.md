# POnto:  An ontology for the Polkadot multichain ecosystem
POnto is a Polkadot ontology designed to represent and relate the main entities of the ecosystem. Besides being a contraction of Polkadot Ontology, "POnto" has inspiration on the meaning of the word *ponto* in Portuguese, which can be translated to both point and *dot*. POnto's focus is to support developers, researchers, and enthusiasts to enhance data analysis, communicability and domain knowledge sharing within the Polkadot community.

A draft version of it was initially based on Polkadot's [whitepaper](https://assets.polkadot.network/Polkadot-whitepaper.pdf). Afterwards, POnto was subsequently enriched according to discussions with domain experts and latest [documentation](https://wiki.polkadot.network/) available. As part of a conceptual framework, POnto was designed as a modular ontology organized hierarchically and provides a representation of different aspects and features of the Polkadot ecosystem. POnto is a structured representation of the ecosystem's fundamental components, concepts, and relationships.

The ontology currently covers eleven modules, including the Core module, and others to represent specific aspects of the Polkadot ecosystem. These other modules are Consensus, Governance, Ledger, Network, Oracle, Stake, Token, Tooling, Transaction, and Wallet. POnto’s Core module defines classes to represent common entities that serve as a sort of upper ontology, supporting the other modules. It covers entities such as architecture components, protocols, wallets, modules, pallets, decentralized applications, etc. 

The Consensus module focuses on the mechanisms and protocols used in the ecosystem to achieve agreement and validity of transactions across multiple chains. It includes concepts such as block production, finality, consensus algorithms, and block authorship. 

The governance mechanisms and processes specifications are part of the Governance module. It includes concepts related to on-chain governance, where voting and delegation are made through blockchain-based mechanisms. This module encompasses entities like voting systems, proposal submission, committee structures, and referendum processes. 

The Network module focuses on the network infrastructure and protocols used in the Polkadot ecosystem. It includes concepts such as network nodes, connectivity, network synchronization, and message propagation. 

The integration of external data into the Polkadot ecosystem is part of the Oracle module. It includes concepts related to how oracles provide external data to smart contracts and decentralized applications (dApps). The module covers data feeds, queries, and the interaction between oracles and the blockchain. 

The Stake module describes staking mechanisms of the ecosystem. It covers concepts such as stake, stake holder accounts, and stake pools (groups of stake holders who combine their stakes). Digital tokens and assets are covered in the Account module, describing concepts related to different types of account such as multisig account and proxy account, as well as concepts related to fungible and non-fungible tokens. 

The Transaction module focuses on the representation and processing of transactions. It includes concepts such as extrinsics (representing transaction data), senders and recipients of transactions, transaction properties (e.g., amount transferred, asset type), and the association of transactions with ledger records and blocks. 

The other three modules (Ledger, Tooling, and Wallet) aim at representing key individuals of the ecosystem to exemplify the use of the ontology. The Ledger module specifies the Polkadot and Kusama relay chains and some of their parachains, like Acala and Moonbeam for Polkadot and Statemine for Kusama. The Tooling module encompasses individuals to represent various tools of the ecosystem, including libraries, and development frameworks available for building applications. Individuals representing essential wallets of the ecosystem are part of the Wallet module.

![POnto](https://github.com/mobr-ai/POnto/assets/779451/1bc8066a-2474-4818-992f-64cbad28da02)

<br>

# License
All the ontology Turtle files and other code that may be created are licensed under Apache 2.0. All the available PDF documents are under [CC-SA license](https://creativecommons.org/licenses/by-sa/2.0/).

<br>

# Additional information

POnto online [documentation](https://www.mobr.ai/ponto)

Scientific [paper](https://arxiv.org/abs/2308.00735)

<br>

# Directory structure
| Dir | Desc |
| -------- | ------- |
| src  | Turtle ontology files |
| docs | POnto ontospy documentation. See docs/index.hml |
| deliverables | Resources delivered during W3F research grant execution |
