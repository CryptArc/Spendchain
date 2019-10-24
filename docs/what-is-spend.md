# What is Spend?

`spend` is the name of the Spend SDK application for the Spend Hub. It comes with 2 main entrypoints:

- `spend`: The Spend Daemon, runs a full-node of the `spend` application.
- `spendcli`: The Spend command-line interface, which enables interaction with a Spend full-node.

`spend` is built on the Spend SDK using the following modules:

- `x/auth`: Accounts and signatures.
- `x/bank`: Token transfers.
- `x/staking`: Staking logic.
- `x/mint`: Inflation logic.
- `x/distribution`: Fee distribution logic.
- `x/slashing`: Slashing logic.
- `x/gov`: Governance logic.
- `x/ibc`: Inter-blockchain transfers.
- `x/params`: Handles app-level parameters.

>About the Spend Hub: The Spend Hub is the first Hub to be launched in the Spend Network. The role of a Hub is to facilitate transfers between blockchains. If a blockchain connects to a Hub via IBC, it automatically gains access to all the other blockchains that are connected to it. The Spend Hub is a public Proof-of-Stake chain. Its staking token is called the Stakings.

Next, learn how to [install Spend](./installation.md).
