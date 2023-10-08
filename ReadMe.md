# Automated Quantum Protocol Verification Based on Dynamic Quantum Logic

This repository presents a support tool developed in Maude to verify sequential quantum protocols and concurrent quantum protocols using Basic Dynamic Quantum Logic (BDQL) and Concurrent Dynamic Quantum Logic (CDQL).

## Dependencies
- Maude is a programming/specification language based on rewriting logic. How to download and install Maude can be found [here](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).

## How to install
- Clone the source code to your computer and go to the source code directory.

- Feed a Maude file that is the formal specification of a protocol being verified into Maude.

For example, we can type the following command in CLI in order to verify the correctness of the quantum teleportation protocol:

```console
maude examples/teleport.maude
```

Note that for `verifying sequential quantum protocols using BDQL`, all necessary files are in the outermost folder. Meanwhile, `verifying concurrent quantum protocols using CDQL`, all necessary files are in the `CDQL` folder.

- For testing, go to the `test` folder and run the `./tester` file in CLI.

## Case Studies
We successfully verified the correctness of some quantum protocols with the support tool as follows:
- Superdense Coding
- Quantum Teleportation
- Quantum Secret Sharing
- Entanglement Swapping
- Quantum Gate Teleportation
- Quantum Network Coding
- Quantum Replay Scheme
- Bidirectional Quantum Teleportation
- Two-qubit Quantum Teleportation
- ...

## Publication
- Tsubasa Takagi, Canh Minh Do and Kazuhiro Ogata: [Automated Quantum Program Verification in Dynamic Quantum Logic (To Appear)](#), DaLí 2023.
