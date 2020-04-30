---
title: Smart contracts
meta:
  - name: Smart contracts
    content: The 101 on Ethereum smart contracts
  - property: og:title
    content: Smart contracts | Ethereum.org
  - property: og:description
    content: The 101 on Ethereum smart contracts
lang: en-US
sidebar: auto
sidebarDepth: 1
solidity:
  - title: Documentation
    link: 'https://solidity.readthedocs.io/'
  - title: GitHub
    link: 'https://github.com/ethereum/solidity/'
  - title: Gitter chatroom
    link: 'https://gitter.im/ethereum/solidity/'
  - title: Blog
    link: 'https://solidity.ethereum.org/'
vyper:
  - title: Documentation
    link: 'https://docs.ethers.io/ethers.js/html/'
  - title: GitHub
    link: 'https://github.com/ethers-io/ethers.js/'
  - title: Update Jan 8, 2020
    link: 'https://blog.ethereum.org/2020/01/08/update-on-the-vyper-compiler'
  - title: Gitter chatroom
    link: 'https://gitter.im/vyperlang/community'
  - title: Cheatsheet
    link: 'https://reference.auditless.com/cheatsheet'
base:
  - title: <- Back
    content: Security
    link:
      to: /developers/security/
  - title: Next ->
    content: Standards
    link:
      to: /developers/standards/
languages:
  - header: https://asdgvdoyen.cloudimg.io/width/2560/webp/https://api.kauri.io:443/ipfs/QmPyoXQaK9uA1oedsptssr1EhYRBF1A9vrnypbKAkMhuxQ
    hero: true
    level: 2
    title: Java
    content: content
    link:
      text: Java docs
      to: /java/
  - header: https://i.imgur.com/MFg8Nop.png
    hero: true
    level: 2
    title: Golang
    content: content
    link:
      text: Golang docs
      to: /golang/
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Delphi
    content: content
    link:
      text: Delphi docs
      to: /delphi/
  - header: https://i.imgur.com/VhoX4LM.png
    hero: true
    level: 2
    title: Python
    content: content
    link:
      text: Python docs
      to: /python/
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: JavaScript
    content: content
    link:
      text: JavaScript docs
      to: /javascript/
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Rust
    content: content
    link:
      text: Rust docs
      to: /rust/
  - header: https://raw.githubusercontent.com/Nethereum/Nethereum/master/logos/logo192x192t.png
    hero: true
    level: 2
    title: .NET
    content: content
    link:
      text: .NET docs
      to: /dot-net/
dappSys:
  - title: DappSys
    link: https://dapp.tools/dappsys/
  - title: GitHub
    link: https://github.com/dapphub/dappsys
openZeppelin:
  - title: OpenZeppelin
    link: https://openzeppelin.com/contracts/
  - title: GitHub
    link: https://github.com/OpenZeppelin/openzeppelin-contracts
  - title: Community forum
    link: https://forum.openzeppelin.com/c/contracts
aragonOs:
  - title: Aragon
    link: https://hack.aragon.org/docs/aragonos-intro.html#aragonos-provides-the-following-functionality
  - title: Documentation
    link: https://wiki.aragon.org/
scwr:
  - title: Smart Contract Weakness Registry
    link: https://smartcontractsecurity.github.io/SWC-registry/
  - title: GitHub
    link: https://github.com/SmartContractSecurity/SWC-registry
---

include best practice content

# Smart contracts {#smart-contracts}

Any program that runs on the Ethereum Virtual Machine (EVM) is commonly referred to as a “smart contract”. The most popular languages for writing smart contracts on Ethereum are Solidity and Vyper, though there are others under development.

## Languages {#languages}

### Solidity

The most popular language on Ethereum, inspired by C++, Python and JavaScript.

<list-card :items="$page.frontmatter.solidity" level="5"/>

### Vyper

Based on python

<list-card :items="$page.frontmatter.vyper" level="5"/>

## Best practices {#best-practices}

### Make it modular

**DappSys**  
Safe, simple, flexible building-blocks for smart-contracts.

<list-card :items="$page.frontmatter.dappSys" level="5"/>

### Make it secure

**OpenZeppelin contracts**  
Library for secure smart contract development.

<list-card :items="$page.frontmatter.openZeppelin" level="5"/>

**Smart contract weakness registry**

<list-card :items="$page.frontmatter.scwr" level="5"/>

### Make it future-proof

**aragonOS**  
Patterns for upgradeability and permission control

<list-card :items="$page.frontmatter.aragonOs" level="5"/>

## Get started {#get-started}

More details on smart contracts based on what you're already comfortable using.

<CardList :items="$page.frontmatter.languages" level="2" desktopColumns="3"/>

---

<CardList :items="$page.frontmatter.base" />
