# Cosmwasm on Optimint

CosmWasm is a smart contracting platform built for the Cosmos
ecosystem by making use of WebAssembly (Wasm) to build smart contracts
for Cosmos-SDK. In this tutorial, we will be exploring how to integrate
CosmWasm with Celestia's Data Availability Layer using Optimint.

You can learn more about Cosmwasm [here](https://docs.cosmwasm.com/docs/1.0/).

In this tutorial, we will going over the following:

* Setting Up Your Dependencies for Your Cosmwasm Smart Contracts
* Setting Up Optimint on Cosmwasm
* Instantiate A Local Network For Your Cosmwasm Chain connected to Celestia
* Deploying A Rust Smart Contract to Cosmwasm Chain
* Interacting With The Smart Contract

The smart contract we will use for this tutorial is one provided by
the Cosmwasm team for Nameservice purchasing.

You can check out the contract [here](https://github.com/InterWasm/cw-contracts/tree/main/contracts/nameservice).

How to write the Rust smart contract for Nameservice is outside the scope of
this tutorial. In the future we will add more tutorials for writing CosmWasm
smart contracts for Celestia.