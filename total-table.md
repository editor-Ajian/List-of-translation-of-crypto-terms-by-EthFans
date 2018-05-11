贡献者请点击[这里](#tonggao)跳到文末通知区查看其他贡献者提供的更新，阅读者可使用 “Ctrl + F” 使用浏览器的搜索功能搜索词条。

### Bitcoin

比特币

第一个实现的公有区块链系统。诞生于2009年。（阿剑）

参见 Blockchain

参见 Public Chain

### Blockchain

区块链

一些通过某种方程而联系起来、具有前后顺序的数据块；后一个数据块中会保留前一个区块被该方程处理之后的数据结果。当前已实现的区块链系统使用的方程为 Hash Function（哈希方程）。由于此种技术常常被用来建构无需中心来强制执行的交易系统（数据块记录的是交易），它也被称为“分布式账本技术”。（阿剑）

参见 Decentralized

参见 Distributed Ledger Technology (DLT)

参见 Hash Function

参见 Public Chain

参见 Private Chain

### Block Reward

区块奖励

在区块链中，为鼓励大家参与产生新区块的过程并为整个系统提供安全性，区块链系统本身会为创造新区块的成员发放一定的原生加密货币奖励。这部分奖励就叫区块奖励。（阿剑）

参看 Blockchain

参看 Security

### Consensus Algorithm

共识算法

特定的规则，规定在区块链上合法的区块如何产生，并对同一高度相互冲突的区块进行选择。使用这些规则的目的是让参与者在一个没有可信特定参与者的系统中形成共识，故称“共识算法”。当前常见的共识算法有 Proof of Work 和 Proof of Stake。（阿剑）

参看 Block Height

参看 Proof of Work

参看 Proof of Stake

参看 Security


### Decentralized

去中心化

交易系统的一种属性，即系统功能的正常执行不依赖于特定中心的存在。（阿剑）

### Distributed Ledger Technology (DLT)

分布式账本技术

用于建构具备特定属性的账本（交易记录）的技术，此种账本并不由特定中心来保存，其可信性也不依赖于特定中心。（阿剑）

### Double Spend

双花

即同一笔钱可以花两次乃至以上。实际上即等同于伪造货币。如不能解决这个问题，则记账单位本身是不可信的，以此建构的账本也将失去意义。（阿剑）

参看 Security

参看 Blockchain

### Ethereum

以太坊

第一个允许实现智能合约的区块链系统。诞生于2013年。（阿剑）

参见 Blockchain

参见 Smart Contract

### Ethereum Improvement Proposal (EIP)

以太坊改进提议

EIP 描述了以太坊平台的标准，包含核心协议规范、客户端 API 及合约标准。[查看官方 EIP 网站](http://eips.ethereum.org/)

### Genesis Block

创世区块

创世区块指区块链上的第一个区块，用来初始化相应的加密货币。

### Hash Function

哈希方程；散列函数

一类单向函数，其特性是给定输入，输出唯一确定；但给定输出不能反推出输入。因此，想获得特定形式的输出值，只能进行穷举式的重复计算。有不止一种哈希方程。（阿剑）

例如：

> ` sha256(EthFans) ` = ` 27f9a531cb719a1127962fad2a8b9ab38e985ef4148ae59213b0d0d07030efa4 ` 
>
> ` sha256(ethfans)  ` = ` 1a64ed5b74670156e60e10d8b4f94b02347169cda06b6f1493f80db0c24f2d6c ` 
>
> ` sh1(ethfans) ` =  ` 37a127fc6ee44155ce50ed31d817d7a5963a10ba ` 

### Know Your Customer (KYC)

了解你的账户

充分了解你的账户（ KYC，Know Your Customer ）是一个商业过程，用于认证和验证顾客的身份信息。也指银行对这些活动的监管。

### Merkle Tree

默克尔树；梅尔克树

生成一棵完整的 Merkle 树需要递归地对哈希节点对进行哈希，并将新生成的哈希节点插入到 Merkle 树中，直到只剩一个哈希节点，该节点就是 Merkle 树的根。在比特币中，叶子节点来自于单个区块中的交易。

### Miner

矿工

在工作量证明中试图产生合法区块的人。在工作量证明中，若某个节点产生了一个新的合法区块，则该节点可以获得一定的原生加密货币奖励。由于这个过程很像挖出矿产，故被称为“挖矿”。而运行区块链软件并试图提供工作量证明的人自然也就被称为“矿工”。（阿剑）

参看 Block Reward

### Nonce

Nonce

本意为只使用一次的随机数。但在工作量证明中，要在区块链上产生一个新的合法区块，必须找到一个 Nonce，对 Nonce 加入初始数据包之后形成的数据块进行哈希计算，所得哈希值会符合某种形式上的要求（如开头有 3 个数字 0）。可以说，Nonce 的设置才真正使得哈希方程成为工作量证明。（阿剑）

参见 Hash Function

参见 Miner

### Private Chain

私有链；私链

特定主体建立并为参与者设置准入门槛的区块链系统；换言之，只有获得特定主体许可的参与者才能保存账本以及发起交易。（阿剑）

参见 Public Chain

### Proof of Stake

权益证明

一种共识算法。即要求合法区块的产生必须获得相关参与者一定比例的投票同意，对同一高度相互冲突的区块也通过同样的投票规则来抉择；参与者的投票权重等同于其抵押的原生货币数量占全部抵押货币的比例。

参看 Consensus Algorithm

### Proof of Work (PoW)

工作量证明

一种共识算法。工作量证明要求区块链上的任一合法区块必须具有一个数据片，该数据片加入原始数据后，对整个数据块进行哈希运算所得结果能符合特定要求。在工作量证明系统中，要成为出块者（产生合法的区块），只能也只需要进行重复的哈希计算（以找到符合要求的数据片）。（阿剑）

参看 Consensus Algorithm

参看 Hash Function

参看 Nonce

参看 Miner

### Public Chain

公有链；公链

不对参与者设置准入门槛的区块链系统；换言之，任何人都可以保存分布式账本的副本以及发起交易。（阿剑）

参见 Private Chain

### Security

安全性

（1）指区块链系统自身的安全性，即区块链中的数据能否被轻易篡改；当区块链用于建构分布式账本时，除了账本数据能否被篡改之外，还要考虑的是该账本是否会因为其记账单位（即原生加密货币）可以被伪造（例如 Double Spend）而完全失去意义。

（2）指区块链系统上的智能合约的安全性，即代码逻辑是否允许一个人任意盗走资产或造成意料之外的资产损失。（阿剑）

参看 Blockchain

参看 Distributed Ledger Technology

参看 Double Spend

参看 Smart Contract

### Smart Contract

智能合约

因具备相当的安全性而能自动执行特定类型的交易的东西，例如自动贩卖机。可以理解为有能力执行特定类型交易的机器人。在以太坊上，智能合约即是一个由代码来控制的账户。智能合约的概念由 Nick Szabo（尼克·萨博）在 1997 年提出。（阿剑）

参看 [智能合约的理念](https://ethfans.org/posts/smart-contract-nick-szabo)

<h2 id="tonggao">通告</h2>





