# Automated Quantum Program Verification in a Dynamic Quantum Logic

This repository presents a support tool developed in Maude to verify quantum programs using a Dynamic Quantum Logic.

## Dependencies
- Maude is a programming/specification language based on rewriting logic. How to download and install Maude can be found at [here](http://maude.cs.illinois.edu/w/index.php/The_Maude_System).

## How to install
- Clone the source code to your computer and go to the source code directory.

- Feed a Maude file that is the formal specification of a protocol being verified into Maude.

For example, we can type the following command in CLI in order to verify the correctness of the quantum teleportation protocol:

```console
maude teleport.maude
```
- For testing, go to the `test` folder and run the `./tester` file in CLI.

## Case Studies
We successfully verified the correctness of five quantum protocols with the support tool as follows:
- Superdense Coding
- Quantum Teleportation
- Quantum Secret Sharing
- Entanglement Swapping
- Quantum Gate Teleportation

## Publication
- Tsubasa Takagi, Canh Minh Do and Kazuhiro Ogata: [Automated Quantum Program Verification in Dynamic Quantum Logic (To Appear)](#), DaLí 2023.
