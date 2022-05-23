<div align="center">
  <img alt="starknet logo" src="./assets/starknet.png" width="200" >
  <h1 align="center">Awesome StarkNet 中文</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="#buildstatus">
      <img alt="build status badge" src="https://github.com/gakonst/awesome-starknet/workflows/Build/badge.svg">
    </a>
    <a href="https://github.com/gakonst/awesome-starknet/graphs/contributors">
      <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/gakonst/awesome-starknet">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>

  <p align="center">本文档汇聚<a href="https://medium.com/starkware/starknet-alpha-is-coming-to-mainnet-b825829eaf32"> StarkNet </a>资源、工具、代码库、生态、应用等内容。由<a href="https://twitter.com/StarkNet_ZH">「StarkNet 中文」</a>编撰。</p>
  <p align="center">欢迎大家按照<a href="CONTRIBUTING.md">《贡献者指南》</a>为本库 PR 贡献</p>
  
  <p align="center">StarkNet 中文<a href="https://twitter.com/StarkNet_ZH"> Twitter </a> | <a href="https://starknetzh.substack.com"> Substack 日报/周报</a>  |  <a href="https://t.me/starknet_zh"> Telegram</a></p>

</div>


## 官方资源

- [官网](https://starknet.io/)
- [StarkNet 概况](https://starknet.io/)
- [StarkNet 文档](https://starknet.io/docs/)
- [StarkNet 开发指南](https://starknet.io/building-on-starknet/)
- [Setting up the environment](https://www.cairo-lang.org/docs/quickstart.html) - 运行 Cairo 开发环境
- [Hello Cairo](https://www.cairo-lang.org/docs/hello_cairo/index.html) - Cairo 合约开发指南
- [Cairo Reference](https://www.cairo-lang.org/docs/reference/index.html) - Cairo 语义详解
- [Cairo – 图零完备 STARK 友好 CPU 架构](https://eprint.iacr.org/2021/1063.pdf) - Cairo 白皮书
- [Cairo 程序执行的验证代数表达式](https://arxiv.org/abs/2109.14534) - 使用 [精益证明助理 (Lean proof assistant)](<https://en.wikipedia.org/wiki/Lean_(proof_assistant)>) 的 Cairo 证明有效性
- [StarkNet Playground](https://www.starknet.io/playground) - 浏览器 StarkNet 示例
- [Cairo Playground](https://www.cairo-lang.org/playground/) - 浏览器 Cairo IDE、范例和谜题
- [StarkNet Voting Workshop](https://starkware.notion.site/starkware/StarkNet-Voting-Workshop-b61ef5f4a62d45af86892cba3158f7e6) - 投票 dApp 开发指南
- [YouTube channel](https://www.youtube.com/channel/UCnDWguR8mE2oDBsjhQkgbvg/playlists) - StarkWare 官方 YouTube 频道


## 生态工具

- OpenZeppelin 合约标准：
  - [入门指南](https://blog.openzeppelin.com/getting-started-with-openzeppelin-contracts-for-cairo)
  - [OpenZeppelin Cairo 合约库](https://github.com/OpenZeppelin/cairo-contracts)
  - [Cairo 合约文档](https://github.com/OpenZeppelin/cairo-contracts/blob/main/docs)
  - [Cairo 扩展功能](https://github.com/OpenZeppelin/cairo-contracts/blob/main/docs/Extensibility.md)
  - [帐户抽象](https://github.com/OpenZeppelin/cairo-contracts/discussions/41)
  - [Nile](https://github.com/OpenZeppelin/nile) - CLI 工具 
- [Cairo 合约向导](https://wizard.openzeppelin.com/cairo) - 交互式合约生成器
- [Warp](https://github.com/NethermindEth/warp) - Solidity -> Cairo 转译器
- [Amarna](https://github.com/crytic/amarna) - Trail of Bits 推出的[静态安全分析工具](https://blog.trailofbits.com/2022/04/20/amarna-static-analysis-for-cairo-programs)，用于识别错误代码和安全隐患
- [starknet](https://github.com/software-mansion/starknet.py) - StarkNet Python SDK
- [starknet-hardhat-plugin](https://github.com/Shard-Labs/starknet-hardhat-plugin) - Hardhat Starknet 工具
- [starknet-devnet](https://github.com/Shard-Labs/starknet-devnet) - Starknet 本地测试网
- [cairo-jupyter](https://github.com/ankitchiplunkar/cairo-jupyter) - Cairo 合约语言 Jupyter 内核
- [Starkops](https://github.com/0xs34n/starkops) - TypeScript 语言 StarkNet 工具链命令行
- [starknet-web3-rpc-adapter](https://github.com/software-mansion-labs/starknet-web3-rpc-adapter) - 向 StarkNet 传输信息的转接器应用
- [cairo-glyph](https://github.com/sambarnes/cairo-glyph) - Cairo 管理器
- [starknet-boilerplate](https://github.com/threepwave/starknet-boilerplate) - 使用 starknetjs 和 nile 部署 starknet/cairo 项目
- [pytest-cairo](https://github.com/TimNooren/pytest-cairo) - cairo-lang 和 starknet pytest 支持
- [Protostar](https://github.com/software-mansion/protostar) - 发布智能合约开发管理工具
- [Nethermind 全节点客户端](https://github.com/NethermindEth/juno)
- [Pathfinder 全节点](https://github.com/eqlabs/pathfinder)
- [StarkTx 交易解码器](https://starktx.info/)
- [StarkNet 数据仓库 (“SDW”)](https://tokenflow.live/blog/edw-open)
- [pre-commit-cairo](https://github.com/franalgaba/pre-commit-cairo) - Cairo git 代码管理工具
- [ZigZag StarkNet 预言机](https://github.com/ZigZagExchange/starknet-oracle)
- [Felucca](https://github.com/franalgaba/felucca) - 代码依赖性管理工具 Felucca
- [voyager](https://voyager.online) - 区块链浏览器
- 交易解码工具 [http://starktx.info](https://t.co/xw9zlzTtT9) | [源代码和文档](https://github.com/TokenFlowInsights/StarkTx)
- [Fossil](https://docs.oiler.network/oiler-network/products/fossil/getting-started) - Starknet L2 Verifier 验证合约 by [@OilerNetwork](https://twitter.com/OilerNetwork) | [API](https://fossil.oiler.network/docs) | [官宣](https://medium.com/oiler-network/introducing-fossil-ce4c23ad17c4)
- [React + Redux 库](https://github.com/ruleslabs/starknet-redux-multicall) - 通过批量缓存调用，撷取每个区块的状态
- [DEX 聚合交易解码器](https://github.com/zoeAD/basic-solver)
- 一站式管理工具 #StarkNet [@yeoman](https://twitter.com/yeoman) [生成器](https://github.com/onlydustxyz/generator-starknet)


## 官方 GitHub 库

- [StarkWare](https://github.com/starkware-libs)
- [Cairo Language](https://github.com/starkware-libs/cairo-lang)
- [starkex-contracts](https://github.com/starkware-libs/starkex-contracts)
- [veedo](https://github.com/starkware-libs/veedo) - Verifiable Delay Function
- [starkex-resources](https://github.com/starkware-libs/starkex-resources)
- [starkgate-frontend](https://github.com/starkware-libs/starkgate-frontend) - StarkGate 前端
- [stark-perpetual](https://github.com/starkware-libs/stark-perpetual) - 永续合约
- [starkex-for-spot-trading](https://github.com/starkware-libs/starkex-for-spot-trading) - 现货交易
- [starkex-js](https://github.com/starkware-libs/starkex-js)
- [starknet-specs](https://github.com/starkware-libs/starknet-specs) - 标准
- [starknet-addresses](https://github.com/starkware-libs/starknet-addresses) - 地址
- [starknet-docs](https://github.com/starkware-libs/starknet-docs)
- [starknet-snap](https://github.com/starkware-libs/starknet-snap)
- [cairo-playground](https://github.com/starkware-libs/cairo-playground)
- [starkware-crypto-utils](https://github.com/starkware-libs/starkware-crypto-utils)


## 学习资源

- [starknet-edu](https://github.com/starknet-edu/) - Cairo 合约学习指南
  - [Cairo 101](https://github.com/starknet-edu/starknet-cairo-101) - 如何阅读 Cairo 代码
  - [ERC20](https://github.com/starknet-edu/starknet-erc20) - 如何在 StarkNet 部署 ERC20
  - [ERC721](https://github.com/starknet-edu/starknet-erc721) - 如何在 StarkNet 部署 ERC721
  - [通讯桥](https://github.com/starknet-edu/starknet-messaging-bridge) - 部署 StarkNet <-> Ethereum 跨链应用
- 《[从 Puzzle 解题来理解 zkSTARK](https://mp.weixin.qq.com/s/9MkDahDq2mJulzQpYvDFEA)》（中文）| 作者：[@trapdoor_tech](https://twitter.com/trapdoor_tech) 
- [Perama 博客](https://perama-v.github.io/cairo/intro/) - StarkNet / Cairo 学习笔记
- [@RoboTeddy StarkNet 开发实操心得](https://hackmd.io/@RoboTeddy/BJZFu56wF)
- [StarkWare 开发笔记](https://seen-joke-82c.notion.site/StarkWare-Development-965f54711eb84dc79f3b61f22df9e383)


## 生态开发部署

- [用 Cairo 运行物理数学 Gamma 函数](https://github.com/abstractnull/specialfunctions_cairo)
- [用 Solidity 部署 StarkNet pedersen hash](https://github.com/zknoname/pedersen-hash-solidity)
- Cairo 部署 [ERC721R 标准](https://github.com/ctrlc03/ERC721R-Cairo) (https://erc721r.org)
- 通过 OpenZepplin Cairo 合约标准[部署机枪池代币 ERC-4626](https://github.com/OpenZeppelin/cairo-contracts/issues/277) | [代码](https://github.com/koloz193/ERC4626)
- [StarkNet 钱包 API](https://github.com/myBraavos/get-starknet-wallet)
- [Gradual Dutch](https://github.com/sambarnes/cairo-dutch/pull/1)
- [RICKS](https://github.com/FawadHa1der/ricks-cairo-contracts) - NFT 碎片化协议
- Cairo 部署 [NFT 限价拍卖机制 CRISP](https://github.com/08351ty/CRISP-cairo)
- [Pytest](https://github.com/TimNooren/pytest-cairo) - Cairo 测试合约
- 多签 - [代码](https://github.com/eqlabs/starknet-multisig) | [使用](http://starknet-multisig.vercel.app)
- [安装 Hardhat 写 Cairo 测试](https://github.com/gaetbout/starknet-stack)
- [Cairo Base-64](https://github.com/dhruvkelawala/cairo-base64)
- [Flashloan](https://github.com/tohrnii/flashloan-starknet)
- [Oriac](https://github.com/xJonathanLEI/oriac) - Rust 部署 Cairo VM
- 用 Cairo [部署 ERC-721 合约](https://github.com/scaffold-eth/scaffold-eth/tree/starknet-nft)
- [Rust 部署  Cairo VM](https://github.com/lambdaclass/giza)
- [链上存取控制合约](https://github.com/419Labs/access-controller-contracts) - 卡槽模式，用以链上注册 | by [@alpharoad_fi](https://twitter.com/alpharoad_fi)
- [tiny-dnn-on-starknet](https://github.com/guiltygyoza/tiny-dnn-on-starknet) - 神经网络
- [Basic Solver](https://github.com/zoeAD/basic-solver) - DEX 聚合交易解码器
- [用 Wintefell 部署 Cairo VM](https://github.com/maxgillett/giza)
- [BLS 椭圆曲线](https://github.com/0xNonCents/multi-precision_cairo) | [BLS12-381](https://github.com/0xNonCents/cairo-bls12-381)
- [alt_bn128](https://github.com/tekkac/cairo-alt_bn128) - 验证 SNARKS 运算的椭圆曲线
- [starknet-btc-lightclient](https://github.com/samlaf/starknet-btc-lightclient) - 比特币轻节点客户端
- 用 Cairo 部署[现金流应用 SuperFluid](https://github.com/ayushm2003/basic-superfluid)
- StarkNet 运行[以太坊开发环境 Hardhat 范例](https://github.com/Shard-Labs/starknet-hardhat-example)
- [全节点安装指南](https://twitter.com/StarkNet_ZH/status/1522111642498048000)



## 社区讨论

- [费用机制](https://community.starknet.io/t/fees-in-starknet-alpha/286) | [文档](https://starknet.io/documentation/fee-mechanism/#How) | [博客](https://www.ethereum.cn/Layer2/fees-in-starknet-alpha)
- [桥接通讯](https://github.com/starknet-edu/starknet-messaging-bridge) | [文档](https://starknet.io/docs/hello_starknet/l1l2.html) | [视频](https://www.youtube.com/watch?v=C-6SBaDi5_c) | [Slide](https://slideshare.net/TinaBregovi/starknet-l1l2-messaging-workshop)
- [去中心化](https://community.starknet.io/t/starknet-decentralization-kicking-off-the-discussion/711) | [Tentermint 方案](https://community.starknet.io/t/starknet-decentralization-tendermint-based-suggestion/998) | [最长链原则](https://community.starknet.io/t/decentralized-consensus-potential-candidate-longest-chain/824) | [视频](https://www.youtube.com/watch?v=rQd6xXIQ43g)
- [特殊情况逃逸出口研究](https://community.starknet.io/t/starknet-escape-hatch-research/1108)
- [Cairo 合约扩展模式](https://github.com/OpenZeppelin/cairo-contracts/blob/main/docs/Extensibility.md) | [社区讨论](https://community.starknet.io/t/contract-extensibility-pattern/210?u=martriay) | [Twitter](https://twitter.com/StarkNet_ZH/status/1521704816916922368)
- [AAVE <> StarkNet 讨论](https://governance.aave.com/t/request-for-approval-aave-starkware-phase-i/7145)
- [MakerDAO x StarkNet 方案讨论](https://forum.makerdao.com/t/mip39c2-sp19-adding-the-starknet-engineering-core-unit-sne-001/9745)


## 开发技巧

- 使用 Cairo 开发，[实现 Github 语法高亮](https://twitter.com/StarkNet_ZH/status/1511925350443278342)
- [设置合约在特定时段切换不同模式](https://github.com/0xtonysprocket/zz_simple_liquidity_pool/blob/main/contracts/Time_window_base.cairo)



## 生态
- [StarkNet 生态](https://starknet-ecosystem.com) - [社区发起](https://github.com/419Labs/starknet-ecosystem.com) StarkNet 生态项目和团队汇总
- [在建生态汇总](https://starkware.notion.site/Projects-Building-on-StarkNet-a33dee55778a4515a9be9bdae02ee682)


## 应用

- [Argent-x](https://github.com/argentlabs/argent-x) - 网页插件钱包
- [Braavos](https://braavos.app) - 智能合约插件钱包
- [Opera 插件和手机钱包](https://www.opera.com/crypto/next) - 目前 Deversifi 可使用
- [跨链桥 StarkGate](https://goerli.starkgate.starknet.io) | [前端 repo](https://github.com/starkware-libs/starkgate-frontend) | [合约](https://github.com/starkware-libs/starkgate-contracts/tree/main/src/starkware/starknet/apps/starkgate) |  [合约地址](https://github.com/starkware-libs/starknet-addresses)


## 其他

- [Winterfell](https://github.com/novifinancial/winterfell) - STARK 证明者架构
- [RISC ZERO](https://www.risczero.com/docs/tutorial-examples/what_is_risc_zero) - zkEVM


---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law,
[Georgios Konstantopoulos](https://github.com/gakonst) has waived all copyright
and related or neighboring rights to this work.
