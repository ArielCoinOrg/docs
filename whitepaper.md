Whitepaper draft.

ArielCoin

Feb 22, 2022


Our current Internet architecture relies on a combination of public-key cryptography and elliptic curve cryptography. 
Public-key encryption systems allow two parties to send secret messages online but need a mathematically related key to the data, 
like a lock and key. These algorithms are used in everything from securing online banking to authentication on social networks.

Quantum computers are infinitely faster at solving specific problems, such as factoring large numbers. 
That’s how encryption keys are generated in elliptic curve algorithms. So if an eavesdropper had access to a quantum computer, 
they could decrypt any communication secured by these algorithms. This kind of attack isn’t possible with classical computers.

To avert this catastrophe, the researchers advising governments, businesses, and the public call for a coordinated effort to prepare for Q-day.
The result will be systems that use encryption that can withstand quantum-computer attacks—and already, several protocols are being developed to do just that.
Efforts to build quantum-robust systems go beyond military and government encryption.

Our project focuses on using these technologies in a business context, proving ownership of objects and transactions on the blockchain.

ArielCoin includes a first-class implementation of the CRYSTALS-Dilithium algorithm for quantum-resistant signatures.

Dilithium is a digital signature scheme that is strongly secure under chosen message attacks based on the hardness of lattice problems over module lattices. 
The security notion means that an adversary having access to a signing oracle cannot produce a signature of a message whose signature he hasn’t yet seen, 
nor produce a different signature of a message that he already saw signed. 

Dilithium is one of the candidate algorithms submitted to the NIST post-quantum cryptography project.

We are using the Dilithium3 parameter set, which achieves more than 128 bits of security against all known classical and quantum attacks 
according to a very conservative analysis.

ArielCoin employs KAWPOW as a proof-of-work hashing algorithm.

In the future, we plan to upgrade to the Proof-of-Useful-Work (PoUW) as an alternative mechanism for transaction validation
that puts the squandered computing resources to beneficial use. 

KAWPOW is GPU-friendly, ASIC unfriendly algorithm. 
We want to attract miners with powerful hardware that can later be used for AI and other computationally intensive tasks.

ArielCoin is committed to contributing to this effort by building technology on top of existing, secure protocols and standards to ensure 
that transactions remain confidential and decentralized authorities verify them in a manner we all can trust.

