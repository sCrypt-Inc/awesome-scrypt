<div align="center">
  <h1 align="center">Awesome sCrypt</h1>
  <p align="center">
    <a href="https://github.com/sindresorhus/awesome">
      <img alt="awesome list badge" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg">
    </a>
    <a href="http://makeapullrequest.com">
      <img alt="pull requests welcome badge" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat">
    </a>
  </p>
  
  <p align="center">A curated list of awesome <a href="https://scrypt.io">sCrypt</a> resources, libraries, tools and more.</p>
  <p align="center">Please check the <a href="CONTRIBUTING.md">contribution guidelines</a> for information on formatting and writing pull requests.</p>
  
</div>

### Contents

- [Official](#official)
- [Tutorials](#tutorials)
- [Articles](#articles)
  - [From Official Blog](#from-official-blog)
  - [Community](#community)
- [Videos](#videos)
- [Code Samples](#code-samples)
- [Libraries](#libraries)
- [SDKs](#sdks)
- [IDEs](#ides)
- [Applications](#applications)
- [Wallet Supports](#wallet-supports)
- [Community](#community-1)
- [License](#license)


## Official

- [Web](https://scrypt.io) - Official website.
- [Docs](https://scryptdoc.readthedocs.io/en/latest/) - Official documentation.
- [Blog](https://medium.com/@xiaohuiliu) - Official blog with regular updates on the latest smart contract development.


## Tutorials

- [Learn sCrypt](https://learn.scrypt.io) - An interactive learning website, #1 sCrypt tutorial.
- [Learn sCrypt by Example](https://by-example.scrypt.io) - An introduction to sCrypt with simple examples.
- [Introduction to Bitcoin Smart Contracts](https://xiaohuiliu.medium.com/introduction-to-bitcoin-smart-contracts-9c0ea37dc757) - Introduction on UTXO Model, Bitcoin Virtual Machine, and Script.
- [A Step-by-Step Guide to Developing Bitcoin Smart Contracts](https://xiaohuiliu.medium.com/a-step-by-step-guide-to-developing-bitcoin-smart-contracts-e43f00f42f05) - Complete workflow of the design, development, testing, deployment, and invocation process of sCrypt smart contracts.
- [Full Stack Bitcoin Dapp Tutorial](https://xiaohuiliu.medium.com/full-stack-bitcoin-dapp-tutorial-adff2bc4f657) - Build a full-stack decentralized Tic-Tac-Toe with a frontend.
- [Bitcoin vs Ethereum Smart Contracts](https://xiaohuiliu.medium.com/bitcoin-vs-ethereum-smart-contracts-921e0a12b043) - Advantages of UTXO over account based model.
- [Stateful Smart Contracts on Bitcoin](https://xiaohuiliu.medium.com/stateful-smart-contracts-on-bitcoin-sv-c24f83a0f783) - How to maintain state across transactions in a contract.


## Articles

### From Official Blog
- [Play Conway’s Game of Life on Bitcoin Forever](https://xiaohuiliu.medium.com/play-conways-game-of-life-on-bitcoin-forever-47c6fb7ed682) - Turing-Complete Conway's Game of Life on Bitcoin.
- [AI on Bitcoin](https://xiaohuiliu.medium.com/ai-on-bitcoin-96bbc97a62b9) - Perceptron.
- [Zero Knowledge Proof and its Applications in Bitcoin](https://xiaohuiliu.medium.com/zero-knowledge-proof-and-its-applications-in-bitcoin-aca833d7d745) - Escrow for purchasing physical goods.
- [Machine Learning on Bitcoin](https://xiaohuiliu.medium.com/machine-learning-on-bitcoin-40f830ad1b43) - Singular Value Decomposition (SVD).
- [Machine Learning Marketplace on Bitcoin](https://xiaohuiliu.medium.com/machine-learning-marketplace-on-bitcoin-d8eb577be812) - Decentralized Kaggle Competitions.
- [Secure Multiparty Computations (MPC) on Bitcoin](https://xiaohuiliu.medium.com/secure-multiparty-computations-on-bitcoin-953a64843b94) - Decentralized Lottery.
- [Oracle on Bitcoin](https://xiaohuiliu.medium.com/access-external-data-from-bitcoin-smart-contracts-2ecdc7448c43) - Rabin signatures.
- [Auction on Bitcoin](https://xiaohuiliu.medium.com/auction-on-bitcoin-4ba2b6c18ba7) - Secure and transparent auction system.
- [Patreon on Bitcoin](https://xiaohuiliu.medium.com/patreon-on-bitcoin-4c3626d4ce5) - Recurring payments and checking accounts.
- [Outsource Computation on Bitcoin](https://xiaohuiliu.medium.com/outsource-computation-on-bitcoin-sv-3beac7c7771b) - Travelling salesman problem.
- [Sudoku on Bitcoin](https://xiaohuiliu.medium.com/sudoku-on-bitcoin-bd78551956fb) - On-chain Sudoku.
- [Read More](https://xiaohuiliu.medium.com/)

### Community
- [TimeLock Bitcoin and Tokens via sCrypt](https://coingeek.com/timelock-bitcoin-and-tokens-via-scrypt-%E2%8C%9B/) - Provably lock up bitcoins/tokens till a certain time by Joshua Henslee.
- [Non-Custodial Agent Bitcoin Transfer](https://medium.com/tokenized-blog/non-custodial-agent-bitcoin-transfer-afacb9c4c625) - Avoid custodial risk using OP_PUSH_TX by Tokenized.
- [How to "Hack" OP_PUSH_TX](https://www.getrevue.co/profile/NikamotoSV/issues/a-1-65k-probability-to-fail-875203) - by frenchfrog42
- [Merkle tree proof based data storage](https://powping.com/posts/fe6cc987ecfc2f799ed465b41bc959e4c58f2fe8b2af477ce27da49103f26bf9) - A contract data storage approach by zhangweis.
- [Bitcoin Script Engineering part II](https://medium.com/@Stas33496115/bitcoin-script-engineering-part-ii-ba8095f093c0) - Weather Derivative contract by Stas Trock.
- [Alan meets Satoshi](https://shilch.me/bitcoin-turing-complete/) - Understanding the bitcoin [turing completeness proof](https://xiaohuiliu.medium.com/turing-machine-on-bitcoin-7f0ebe0d52b1) of X. Liu by shilch
- [trustless on-chain Bitcoin vanity address generation](https://medium.com/@sinkec.mihael/on-chain-outsourcing-of-vanity-address-generation-on-bitcoin-fe816729be06) by msinkec
- [global unique ID enforced by miners](https://github.com/mr-word/manadocs-public/blob/master/for-bsv-devs.md) a proposal to have L1 tokens by Mr Word
- [First attempt at the “Back to Genesis” issue](https://medium.com/@buildonbsv/first-attempt-at-the-back-to-genesis-issue-6144f398b724) - by Andrew Kondelin
- [“Back to Genesis” Simplest Explanation](https://medium.com/@buildonbsv/back-to-genesis-simplest-explanation-7a9264ca6aed) - by Andrew Kondelin
- [How to Create Overlay Networks inside Bitcoin Script](https://mdtechnologies.medium.com/how-to-create-overlay-networks-inside-bitcoin-script-a5f1a0504386) - by Murray Distributed Technologies
- [Bitcoin’s Decentralized Exchange based on UTXO](https://chainbow.medium.com/bitcoins-decentralized-exchange-based-one-utxo-5c6665494550) - by Chainbow

## Videos

- [Learning sCrypt](https://www.youtube.com/playlist?list=PL0Kn1t30VSpG4Fu2ze81uDptBd1ZML99A) - A tutorial series teaching sCrypt
- [Bitcoin Class with Satoshi](https://youtube.com/playlist?list=PL0Kn1t30VSpEmlsKxlTrlW7s9zGoLgJFY) - Weekly Bitcoin class with Dr. Craig Wright and Xiaohui Liu.
- [sCrypt Online Meetups](https://www.youtube.com/playlist?list=PL0Kn1t30VSpFvpa872C_sZLwFaccHxU9W) - Recordings of Weekly sCrypt meetups
- [Smart Contracts with sCrypt](https://youtube.com/watch?v=neFzipqzegU) - 4-part series by Stephan February of TwoStack.
- [Getting Started with sCrypt](https://www.buildonbsv.com/) - Setup, deploy, and line-by-line breakdown of an escrow contract by Ty Everett.
- [Developing Smart Contracts on BSV](https://youtu.be/9v3bKpvABXA) - Introduction to sCrypt, a talk given at BSV DevCon 2020 by X. Liu.
- [OP_PUSH_TX and Its Applications in Bitcoin Smart Contracts](https://youtu.be/NDIlSRnm2Uc) - OP_PUSH_TX and the smart contract applications that can be built with it, a talk given at BSV DevCon 2021 by X. Liu.
- [What is Bitcoin Script? What is sCrypt and why it is needed.](https://youtu.be/ZKn0yR8jpec) - Introduction to Bitcoin Script and sCrypt by Ken Sato.
- [How to Program Smart Contracts on BSV](https://youtu.be/9v3bKpvABXA) - Demonstrate how to build Smart Contracts using sCrypt at BSV SF Meetup 2019 by X. Liu.
- [sCrypt: A High Level Smart Contract Language for BSV](https://youtu.be/wDkOyB0DkIk) - sCrypt debut at CoinGeek Seoul 2019 by X. Liu.
- [Smart Contracts on BSV](https://youtu.be/tQE9a46KHmk) - sCrypt progress update at CoinGeek London 2020 by X. Liu.
- [Introduction to sCrypt](https://youtu.be/kQlA1VwzU70) - At BSV Devcon China 2020 by Yiqiang Wang (in Chinese).
- [An introduction of sCrypt Development Tools](https://youtu.be/TX7HXq7EeKc) - BSV Webinar Episode 3 in 2021 by Yiqiang Wang (in Chinese).
- [How to Program Smart Contracts on BSV](https://youtu.be/9v3bKpvABXA) - Demonstrate how to build Smart Contracts using sCrypt at BSV SF Meetup 2019 by X. Liu.


## Code Samples

- [sCrypt Project Boilerplate](https://github.com/sCrypt-Inc/boilerplate) - Official boilerplate with 80 contract examples and growing.
- [Aaron's sCrypt playground](https://github.com/gitzhou/scrypt-playground)
- [Gist](https://gist.github.com/ccoincash) - Sample contract and deploy code for token sale, transaction parsing, merkle tree, token swap, and binary option by ccoincash
- [Sensible Fungible Token](https://github.com/sensible-contract/token_sensible)
- [Sensible NFT](https://github.com/sensible-contract/nft)
- [Sensible NFT Auction](https://github.com/sensible-contract/nft-auction-js)
- [Pricing betting](https://gist.github.com/gitzhou/7f4f8709590995ac8b7c008d7860bada) - price info from Oracle WitnessOnChain
- [Evisource](https://github.com/BuildOnBSV/evisource) - oracle service

## Libraries

- [OP_PUSH_TX](https://xiaohuiliu.medium.com/op-push-tx-3d3d279174c1) - Standard library OP_PUSH_TX.
- [Optimal OP_PUSH_TX](https://xiaohuiliu.medium.com/optimal-op-push-tx-ded54990c76f) - Optimized OP_PUSH_TX.
- [Fixed and Float Point](https://xiaohuiliu.medium.com/floating-point-in-scrypt-aa4637633ee7) - Fixed and floating point support.
- [Elliptic Curve](https://xiaohuiliu.medium.com/efficient-elliptic-curve-point-addition-and-multiplication-in-scrypt-script-f7e143a752e2) - Efficient elliptic curve point addition and multiplication on secp256k1
- [Schnorr Signatures](https://xiaohuiliu.medium.com/schnorr-signatures-on-bitcoin-397ca51d8bda) - Schnorr signatures.
- [Rabin Signatures](https://xiaohuiliu.medium.com/access-external-data-from-bitcoin-smart-contracts-2ecdc7448c43) - Oracle to sign arbitrary data.
- [MAST](https://xiaohuiliu.medium.com/merkelized-abstract-syntax-tree-6a49b2008435) - Merklized Abstract Syntax Tree to Compress a Smart Contract Logarithmically.
- [Tree Signatures](https://xiaohuiliu.medium.com/tree-signatures-8d03a8dd3077) - Efficient and Private Multisig.


## SDKs

- [scryptlib](https://github.com/sCrypt-Inc/scryptlib) - Javascript/Typescript.
- [py-scryptlib](https://github.com/sCrypt-Inc/py-scryptlib) - Python.
- [go-scryptlib](https://github.com/sCrypt-Inc/go-scryptlib) - Go.


## IDEs

- [Desktop](https://marketplace.visualstudio.com/items?itemName=bsv-scrypt.sCrypt) - Visual Studio Code Extension.
- [Cloud](https://scrypt.studio) - Online IDE.


## Applications

- [TokenSwap](https://tswap.io) - Onchain DEX.
- [CUTP](https://github.com/CUTP) - Controllable UTXO Token Protocol.


## Wallet Supports

- [DotWallet](https://www.dotwallet.com/en/article/269) - Support arbitrary sCrypt Smart Contracts, like MetaMask.
- [Volt](https://volt.id)


## Community

- [Slack](https://join.slack.com/t/scryptworkspace/shared_invite/enQtNzQ1OTMyNDk1ODU3LTJmYjE5MGNmNDZhYmYxZWM4ZGY2MTczM2NiNTIxYmFhNTVjNjE5MGYwY2UwNDYxMTQyNGU2NmFkNTY5MmI1MWM) - Official main communication channel.
- [Github](https://github.com/sCrypt-Inc) - Open source contracts, SDKs, and dApps.
- [Telegram](https://t.me/joinchat/GwaRAxKT16JjXyHt5PuhHw)


---

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, sCrypt Inc has waived all copyright and related or neighboring rights to this work.
