
# STARK、StarkEx 和 StarkNet

> 原文：[STARKs, StarkEx, and StarkNet](https://medium.com/starkware/starks-starkex-and-starknet-9a426680745a)
>
> 原作者：StarkWare Glossary
>
> 译者：Captain Hook、Whisker、Eve Xu
>
> 校对：StarkNet 中文
>


## **TL;DR**

-   STARK 通过高效证明计算的完整性来实现区块链的扩展
-   StarkEx 是针对应用的扩展引擎
-   StarkNet 是无需许可的智能合约 L2 网络

## **STARK**

STARK，其英文全称为 Scalable Transparent ARgument of Knowledge，即可扩展的、透明的知识证明方法。STARK 是一个能够证明计算并验证计算的证明系统，它首先处理大型计算，然后生成可以证明计算正确的证明，最后验证此证明的真实性。

STARK 在区块链的可扩展性中发挥着关键作用，通过此方法，大型计算在链下以开销更小的方式完成，只留下需要一小部分计算的验证在链上完成。换句话说，验证者只在链上执行很少的步骤，就能证明在链下进行的其余的庞大计算的完整性。

L2 解决方案通过 STARK 批量化计算成千上万的交易，然后在链上验证 STARK 证明的有效性。链上验证成本由批量交易均摊，这就保证每笔交易继承以太坊安全性的同时，gas 消耗降低。

低计算成本的特性将催生出以往无法在链上运行的新型应用。同时，这些特性使 STARK 成为改善用户体验和降低 gas 成本的最佳构件的同时，能够延续以太坊结算层的安全性。

StarkWare 用 STARK 提供了两种以太坊解决方案：StarkEx 和 StarkNet。

## **StarkEx**

StarkEx 是用于创建需许可的、针对特定应用的扩展解决方案框架。StarkEx 作为一个有用的应用流程工具箱，项目可以通过它节约成本，以进行链下计算。链下生成能证明执行正确性的 STARK 证明，其中包括多达 12,000-500,000 笔交易（取决于交易类型）。然后，证明发送给 STARK 验证器，链上验证后接受。这意味着对所有交易进行一次验证--每笔交易分摊的 gas 成本低得惊人。

部署在 StarkEx 上的应用的几个例子是 dYdX（永续交易）、Immutable 和 Sorare（NFT 的铸造和交易）、DeversiFi（现货交易）和 Celer（DeFi 池）。

StarkWare 公司正在根据市场和客户的需求不断向 StarkEx 添加更多的应用流。

## **StarkNet**

StarkNet 是无需许可的的 L2 网络，任何用户或开发者都可以用 Cairo 语言在 StarkNet 上部署智能合约。

在 StarkNet 生态部署的合约与在以太坊部署体验类似，所有合约都可以与生态系统内任何其他合约交互，实现多样的可组合性。StarkNet 上的合约也可以通过异步消息与以太坊上的合约交互。

StarkEx 中，应用自己负责提交交易，而 StarkNet 则需要定序器打包交易，再发送进行处理和证明。（StarkNet 的定序器目前由 StarkWare 运营，计划在未来实现去中心化）这意味着一旦应用程序在 StarkNet 上部署了 Cairo 合约，就不必再额外处理运营基础设施。StarkNet 支持 Rollup 数据可用性模式，Rollup 的状态会与 STARK 证明一起写入以太坊。

庞大的开发者社区正在深度参与 StarkNet 生态系统建设，积极构建应用、工具和基础设施。DeFi、游戏、投票、人工智能等几十个应用已经在测试网上线。此外，StarkNet 社区还在研发区块浏览器、本地测试环境和架构、多国语言的 SDK 等各种开发者工具。如有任何改进建议，潜在功能和最优方案都可以在论坛讨论。

## **总结**

StarkEx 和 StarkNet 都是基于 STARK 的扩展解决方案，都能实现扩展性、低 gas 费和安全性，但两者有不同的运行条件和互操作模式。StarkEx 更适合独立性较强和匹配 StarkEx API 的协议。而StarkNet 更适合需要与其他协议同步交互的协议，以及一些超出 StarkEx 应用范围的协议

STARK 已经彻底改变了以太坊上应用开发的模式。StarkEx 和 StarkNet 将持续为之前被技术条件限制的应用赋能，不断探索区块链应用的潜能。
