# Smart Contracts as Authorized Production Rules

Rainfall is a smart contract programming model that allows mutually distrusting parties to manage assets on a distributed ledger. The model consists of a tuple space of authorized facts, and a set of production rules. Rules match on authorized facts, gaining their authority, and produce new facts with a subset of the gained authority. Rainfall allows assets such as crypto currencies to be defined in user code, rather than being baked directly into the ledger framework. Our authorization model also provides a natural privacy model, where not all rules or facts need to be revealed to all parties.

This repository contains the latex source code for the paper describing the Rainfall model.

* A paper PDF including appendices is at
 [distro/Rainfall-PPDP2019-with-appendices.pdf](https://github.com/rainfall-lang/rainfall-paper/blob/master/distro/Rainfall-PPDP2019-with-appendices.pdf)
 
* An interpreter implementation is at
 [https://github.com/rainfall-lang/rainfall-model](https://github.com/rainfall-lang/rainfall-model)
 
* Proof scripts for the formalization are at 
 [https://github.com/rainfall-lang/rainfall-model/tree/master/proof](https://github.com/rainfall-lang/rainfall-model/tree/master/proof)
