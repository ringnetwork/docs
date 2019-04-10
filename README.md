[![Gitter](https://badges.gitter.im/Ring-Network/community.svg)](https://gitter.im/Ring-Network/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
# Ring Network
Ring Network is an in-progress implementation of the DAG-based Ledger system. You can find some introductions here. Many characteristics of Ring Network are still undefined. 
### Directed-Acyclic-Graph
The separation of powers between entry and attestation allows a node being able to write transactions into the ledger directly without blocking. A well-designed incentive system built upon consensus mechanism will reduce the willingness of attestors to behave “evil” in a large extent.

### Scalability
Benefited from the DAG technology, the Ring Network avoids the block size limitation and provides a verifiable general-purpose scripting system which can be used to extend its functionality at Layer Two.

### Hybrid Consensus
The integration of Free Unit-Reference, Proof of Work (PoW), Delegate Proof of Stake (PoS) and Tendermint Byzantine Agreement will make sure decentralization and incentivized token economy never stop. Transactions are finalized immediately after being attested without rollback.

### Privacy
Ring Network dual-token model combines both ordinary token and privacy token in Layer One and will provide extended functionality and improve transaction security. Privacy token is based on homomorphic encryption, confidential transaction, Conjoin, Cut-Through etc. Users can also issue ordinary token and privacy token.

### Cross-Chain
Ring Network will implement IBC (Inter-Blockchain Communication) protocol and cryptographic cross-chain Atom Exchange Protocol to break the barrier between different systems and integrate functions and resources of them. Side-chain technologies will be supported to build Layer Two.


## What is here in "docs"?
Documents about Ring Network and TrustME consensus algorithm, their implementations, and more.

We have:
- Introduction Material
- Technical documentation
   - [TrustME-Hybrid Consensus](./TrustMEHybridConsensus_CN.md)
   - [Double Spend](./DoubleSpend_CN.md)
   - [Economic Model](./EconomicModel_CN.md)
- The Wiki, open for all to edit and improve! Has things like
   - [Getting started with RingNetwork](https://github.com/ringnetwork/docs/wiki/Getting-Started-With-RingNetwork-Links-and-Resources)
   - [FAQ](https://github.com/ringnetwork/docs/wiki/FAQ)
   - [RNG for programmers](https://github.com/ringnetwork/docs/wiki/Hacking-and-contributing)
   - [Glossary and jargon](https://github.com/ringnetwork/docs/wiki/Jargon-file-and-glossary)
   - [Archive of some design discussions](https://github.com/ringnetwork/docs/wiki/Design-discussions)
   - [and more...](https://github.com/ringnetwork/docs/wiki/)

## Get involved

Please read [how to contribute](./CONTRIBUTING.md)
and be aware of our
[code of conduct](./CODE_OF_CONDUCT.md).

### Find us:

* Chat: [Gitter](https://gitter.im/Ring-Network/community).
* Mailing list: [see archives](https://lists.launchpad.net/ringnetwork/) or
join the [~Ring Network team](https://launchpad.net/~ringnetwork)
and click there to request to join the mailing list.

