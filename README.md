# fairstaking1kv

项目名称： Non-profit DElegated Staking Tool (NDeST) 
简称： NDeST

## 一，项目背景：

### 1.1 去中心化的问题
长期来看，随着ksm/dot价值的越来越大，机构特别是交易所或者一些专门的节点运营机构可能占据越来越重要重要的位置，他们可能会持有越来越多的节点，而机构持有节点过多会非常影响影响ksm/dot网络的去中心化程度，因此提高个人用户持有节点的比例是保持系统去中心化的关键手段。机构持有过多节点不仅仅会造成去中心化的问题，而且会使得系统总体参与程度下降，比如投票，比如参与提案，比如新版本的更新速度等等，以及因为一些图发情况导致的节点大面积下线，都会对系统发展不利。1kv计划（web3特地发起了1kv计划，即通过web3的支持，部分个人用户只需要提供少量质押，即可以拥有一个节点。）是降低系统中心化程度，保持系统足够分散性和足够参与者的关键项目

### 1.2 1kv中选举成功率较低，需要web3提供更多的质押
目前1kv共约167个valid node（https://kusama.yaohsin.net/api/validators） ，只有84个节点被成功选举成为验证人节点，选举成功率约为50%。虽然1kv计划尝试通过各种方法使得尽可能提高成功率，让更多的参与者能够分享收益，但是如果让167个节点都成为选举人节点，每个节点至少需要5000个抵押，如果所有的节点都来自web3，那么至少需要83万5000ksm。而且随着参与者越来越多，需要web3提供的质押越辣越多，如果仅仅依靠web3 foundation可能不足与提供足够多的staking支持大多数节点选举成功。

### 1.3 个人提名者参与1kv质押是解决问题的根本办法
个人提名者参与1kv质押可以解决一部分质押资金来源的问题，大量的个人提名者参与1kv，也可以极大增加1kv计划的资金实力；个人提名者参与1kv计划，还可以增加1kv计划中节点获取稳定收益的能力，因为个人提名者一般不会频繁质押以及撤销质押，大部分个人用户还是习惯于质押在某一个确定的节点上。

## 二，项目目标
通过polkadot App提供个人提名者对于1kv计划节点的直接质押（一键质押）提升1kv参与者得选举成功率，从而增加1kv计划中质押资金得来源（目前1kv质押资金主要来源于web3），提升系统去中心化程度，增加系统活跃度。

## 三，项目内容
### 个人提名者质押入口
在polkadot app中，对于个人提名者而言，提供更多1kv操作入口
```
Bond more funds
Unbond funds
Withdraw unbound funds
_______________________
Change Controller account
Change Reward destination
_________________________

Staking in Web3 1KV (新增）

```

### 


### 去中心化的问题
长期来看，随着ksm/dot价值的越来越大，机构质押可能占据一个非常非常重要的位置，而机构质押过多会非常影响影响ksm/dot网络的去中心化程度，因此提高freeusers对于散户的直接质押将是增加系统稳定性的核心。

## 目标

### 短期目标

解决目前1kv中大部分节点难以获取web3的直接支持，从而不能进入1KV Active Set的问题。
### 长期目标
发展基于kusama的Non-Profit Defi,增加free users对于free validator的直接质押比例，提高系统的去中心化程度，应该是这个系统的核心目标

## 和Defi的关系
### Non-Profit Defi

我们可以考虑创建一个新名词Non-profit Defi，传统的Defi需要发行自己的代币或者需要直接进行资产的转移然后进行相关的金融活动，Non-Profit Defi也是一种Defi，但是不以进行资产的转移为目标，而是借助某种生态体系（ksm/dot）创建一种金融工具，系统本身不盈利。在本项目中，Non-Profit Defi本质上一种委托质押工具，其中没有利差的存在。当然，不排除，未来，本项目可能会向Defi演进，这可能是另外一个项目。

## 相对Defi的优势

### 解决方案
我们创建Defi，接受来自任何ksm用户的自动委托，通过委托向1kv中的inactive set提供一键质押功能（随机选择任意4个inactive set进行质押），在功能上该质押等同于用户直接选择节点质押，所以在任意时刻用户均可以撤回质押或者再次选择手动质押。

## 意义
通过Defi，解决1kv中流动性不足的问题，通过吸纳自有用户的为1kv增加流动性，提高1kv用户的质押比例。

## 希望的支持 

### 功能支持
希望能在polkadot app中提供fairstaking1kv入口。
### 国库支持
500ksm
