# 测试网

<<<<<<< HEAD
小蚁的测试网（Test Net）是官方提供的，专供用户来开发、调试和测试的。测试网上面的系统费用是测试网中的小蚁币，并非真实的小蚁币，测试网的小蚁股和小蚁币可以在官网上免费申请。

测试网的所有区块数据都是独立于主网的。如果开发简单的智能合约或者尝试注册资产的话，用测试网就足够了，待开发完成后可以迁移到小蚁的主网上运行。
=======
NEO 的测试网（Test Net）是官方提供的，专供用户来开发、调试和测试的。测试网上面的系统费用是测试网中的 NeoGas，并非真实的 NeoGas，测试网的 NEO 和 NeoGas 可以在官网上免费申请。

测试网的所有区块数据都是独立于主网的。如果开发简单的智能合约或者尝试注册资产的话，用测试网就足够了，待开发完成后可以迁移到 NEO 的主网上运行。
>>>>>>> e5e43331cd35f87f336ded6b98df4277306e0359

## 测试网的特点

1. 资产注册、资产分发、合约执行等不会消耗真实货币。
2. 全球化的，部署在 Internet 环境上的。
3. 测试网中的区块、交易等信息可以在区块链浏览器中方便地查看到。
4. 部署在测试环境上的智能合约，全世界任何人都可以调用。
5. 测试网不能作为商业应用的实际落地环境。

## 客户端下载

测试网客户端与主网客户端相同，通过修改客户端的配置文件来让客户端在主网和测试网中切换。

<<<<<<< HEAD
参考：[小蚁节点介绍](introduction.md)。

|      | AntSharesCore-GUI                        | AntSharesCore-CLI                        |
| ---- | ---------------------------------------- | ---------------------------------------- |
| 程序   | [官网](https://www.antshares.org/download) 或 [Github](https://github.com/antshares/antsharescore/releases) | [Github](https://github.com/antshares/antsharescore/releases) |
| 源代码  | [Github](https://github.com/antshares/antsharescore) | [Github](https://github.com/antshares/antsharescore) |

## 切换测试网的方法

1、将程序目录下的 `protocal.testnet.json` 里的内容复制到 `protocol.json`，如图。

![](~/images/2017-06-08_14-16-35.png)

2、将程序（GUI）目录下的 `AntSharesUI.exe.testnet.config` 里的内容复制到 `AntSharesUI.exe.config`，如图

![](~/images/2017-06-08_14-16-12.png)

注：如果是 CLI 节点，需要将 `config.testnet.json` 里的内容复制到 `config.json`。
=======
参考：[NEO 节点介绍](introduction.md)。

|      | neo-gui                                  | neo-cli                                  |
| ---- | ---------------------------------------- | ---------------------------------------- |
| 程序   | [下载地址](https://github.com/neo-project/neo-gui/releases) | [下载地址](https://github.com/neo-project/neo-cli/releases) |
| 源代码  | [Github](https://github.com/neo-project/neo-gui) | [Github](https://github.com/neo-project/neo-cli) |

## 切换测试网的方法

1、将程序目录下的 `protocal.testnet.json` 里的内容复制到 `protocol.json`（替换原有配置文件），如图。

![](/assets/testnet_1_v2.png)

2、将程序（GUI）目录下的 `config.testnet.json` 里的内容复制到 `config.json`（替换原有配置文件），如图

![](/assets/testnet_2_v2.png)

注：旧版客户端此步是将 `neo-gui.testnet.config` 里的内容复制到 `neo-gui.exe.config`（替换原有配置文件）。




>>>>>>> e5e43331cd35f87f336ded6b98df4277306e0359



