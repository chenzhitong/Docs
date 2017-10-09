<<<<<<< HEAD
# AntShares node introduction

Full nodes are nodes that store all of the blockchain data. The nodes are connected to the blockchain, through a P2P network. In the blockchain network, all the nodes are equal, where it acts both as a client interface, and as a server.

There are two full-node programs. The first one is for ordinary users, displayed with a graphical user interface and all the basic functions of a user-client. We call it AntSharesCore-GUI.

The other is meant to be used by developers, hosted within the command line interface, and provides an external API for most of the basic wallet functions. This node also helps other nodes achieve consensus with the network, and is also involved in the generation of new blocks. We call It AntSharesCore-CLI.

## AntShares node download address

|      | AntSharesCore-GUI                        | AntSharesCore-CLI                        |
| ---- | ---------------------------------------- | ---------------------------------------- |
| Releases | [Official website](https://www.antshares.org/download) or [Github](https://github.com/antshares/antsharescore/releases) | [Github](https://github.com/AntShares/antsharescore/releases) |
Source code | [Github](https://github.com/antshares/antsharescore) | [Github](https://github.com/antshares/antsharescore) |
=======
# NEO node introduction
Nodes that store all of the blockchain are called “full-nodes”. They are connected to the blockchain through a P2P network. All the nodes in the blockchain network are equal, they act both as a client interface and as a server.

There are two full-node programs. The first one is Neo-GUI, it has all the basic functions of a user-client including a graphical user interface and is intended for NEO users. The second one is Neo-CLI, it provides an external API for basic wallet functions and is intended for NEO developers. It will also help other nodes achieve consensus with the network and will be involved in generating new blocks.

The NEO [network protocol](network-protocol.md) will provide a low level API for some transaction types that are not currently supported by the CLI, such as claiming GAS or sending NEO without an open wallet.

## NEO node download address

|      | Neo-GUI                        | Neo-CLI                        |
| ---- | ---------------------------------------- | ---------------------------------------- |
| Releases | [Official website](https://www.neo.org/download) or [Github](https://github.com/neo-project/neo-gui/releases) | [Github](https://github.com/neo-project/neo-cli/releases) |
| Source code | [Github](https://github.com/neo-project/neo-gui) | [Github](https://github.com/neo-project/neo-cli) |
>>>>>>> e5e43331cd35f87f336ded6b98df4277306e0359

## Comparison of GUI node and CLI node functions

|           | GUI  | CLI  |
| --------- | ---- | ---- |
| Graphic Interface | ✅    |      |
| Command Line Interface |      | ✅    |
| Create Wallet | ✅    | ✅    |
| Open Wallet | ✅    | ✅  |
| Reconstruct Wallet Index | ✅    | ✅    |
| Show all key pairs | ✅    | ✅    |
| Import/Export Key Pair | ✅    | ✅    |
| Show all addresses | ✅    | ✅    |
| Show all assets | ✅    | ✅    |
| Create Address | ✅    | ✅    |
| Transfer | ✅    | ✅    |
| Transaction (Asset swap)  | ✅    |      |
| Create a multi-party signature contract | ✅    |      |
| Create a custom smart contract | ✅    |      |
| Signature | ✅    |      |
| Election Consensus Node | ✅    |      |
| Voting | ✅    |      |
| Register assets | ✅    |      |
| Distribution of assets | ✅    |      |
<<<<<<< HEAD
| Extraction of AntShares | ✅    |      |
=======
| Extraction of NEO | ✅    |      |
>>>>>>> e5e43331cd35f87f336ded6b98df4277306e0359
| Batch Generation Address  |      | ✅    |
| JSON-RPC |      | ✅    |
| The consensus of the participating blocks |      | ✅    |

## Port description

If you want an external program to access the node's API, an open firewall port is required. The following is a port description that can be set to fully open or open-on-demand.

|                    | Main Net | Test Net |
| ------------------ | ------------ | ------------- |
| JSON-RPC via HTTPS | 10331        | 20331         |
| JSON-RPC via HTTP  | 10332        | 20332         |
| P2P via TCP        | 10333        | 20333         |
| P2P via WebSocket  | 10334        | 20334         |

For more information, please refer to [test network](testnet.md).
