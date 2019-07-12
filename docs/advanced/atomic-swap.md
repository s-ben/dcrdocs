# Atomic Swaps

---

## Overview

An Atomic Swap is a smart contract technology which makes possible to exchange coins from two different blockchains without having to trust any third party, for example a centralized exchange.
The smart contracts used in this case are not necessarily Turing-complete smart contracts (like in the system of Ethereum).
Smart contracts also exist in the system of Bitcoin or Decred, or any other cryptocurrency.  The scripting languages of these cryptocurrencies are not Turing-complete, which is intentionally designed like this to avoid loops.  
For an atomic swap, a cryptocurrency must have the 'OP_CHECKLOCKTIMEVERIFY' opcode, which makes a timelock possible.
The other prerequisite is that they need to have the same hash algorythm.

---

## History of Atomic Swaps

Tier Nolan is consider the inventor of atomic swaps. The concept of decentralized exchanges were widely discussed already in 2012. The first atomic swap happened between Decred and Litecoin on September 20, 2017.

## Further Information

For more technical information about Atomic Swaps, visit Decred's [atomicswap Github repo](https://github.com/decred/atomicswap).
