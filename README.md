# POnto - An ontology for the Polkadot multichain ecosystem
POnto is a Polkadot ontology designed to represent and relate the main entities of the ecosystem. Besides being a contraction of Polkadot Ontology, "POnto" has inspiration on the meaning of the word *ponto* in Portuguese, which can be translated to both point and *dot*.

Aiming at a better organization and support for evolution, POnto was designed in a modular fashion, using different modules that describe the various aspects of the Polkadot system. POnto entities have labels describing the symbolic name of the entity along with a brief description of its purpose and characteristics. 

Currently there are eleven modules. The main module describes the basic concepts of system and distributed ledger architectures. The other modules group concepts for the Polkadot Ecosystem components: consensus, governance, ledger, oracle, stake, token, tooling, transaction, and wallet. There is also a module to state the ecosystem rules and constraints called RBox, which is a container of rule descriptions. Each module is a separate ontology that is imported into the main module using the owl:imports property.


![POnto - Core](https://user-images.githubusercontent.com/779451/229795569-636a9b14-5c76-4ac3-949f-b187b9a7f750.png)
