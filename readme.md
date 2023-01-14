# Account Abstraction

An Account Abstraction implementation on zkSync

## Installation

You need Node.js and Yarn.

Install all dependencies with `yarn`.

Compile contracts with `yarn hardhat compile`

## Deployment and usage

To run the scripts to deploy and execute the contracts, use the `zksync-deploy` command:

- `yarn hardhat deploy-zksync --script deploy-factory.ts`: deploys the factory contract
- `yarn hardhat deploy-zksync --script deploy-multisig.ts`: deploys a multisig wallet and executes a transaction.
