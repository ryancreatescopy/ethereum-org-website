---
title: Ethereum and APIs
meta:
  - name: Ethereum and APIs
    content: The frontend and backend APIs you can use with Ethereum
  - property: og:title
    content: Ethereum and APIs | Ethereum.org
  - property: og:description
    content: The frontend and backend APIs you can use with Ethereum
lang: en-US
sidebar: auto
sidebarDepth: 1
web3js:
  - title: Documentation
    link: 'https://web3js.readthedocs.io/en/v1.2.7/'
  - title: GitHub
    link: 'https://github.com/ethereum/web3.js/'
ethersjs:
  - title: Documentation
    link: 'https://docs.ethers.io/ethers.js/html/'
  - title: GitHub
    link: 'https://github.com/ethers-io/ethers.js/'
lightjs:
  - title: Documentation
    link: 'https://paritytech.github.io/js-libs/light.js/'
  - title: GitHub
    link: 'https://github.com/paritytech/js-libs/tree/master/packages/light.js'
infura:
  - title: Infura.io
    link: 'https://infura.io'
  - title: Documentation
    link: 'https://infura.io/docs'
  - title: GitHub
    link: 'https://github.com/INFURA'
base:
  - title: <- Back
    content: Developer tools
    link:
      to: /developers/developer-tools
  - title: Next ->
    content: Storage
    link:
      to: /developers/storage
---

# Ethereum and APIs {#ethereum-and-apis}

Short intro explaining that there are a number of frontend and backend APIs you can use with Ethereum.

## Frontend JavaScript APIs {#frontend-javascript-apis}

### Web3.js

The most used Ethereum javascript API that allows you to interact with a local or remote Ethereum node using HTTP or IPC connection.

<list-card :items="$page.frontmatter.web3js" level="5"/>

### Ethers.js

Complete Ethereum wallet implementation and utilities in **Javascript** and **TypeScript**.

<list-card :items="$page.frontmatter.ethersjs" level="5"/>

### light.js

A high-level reactive JS library optimized for light clients.

<list-card :items="$page.frontmatter.lightjs" level="5"/>

## Backend APIs {#backend-apis}

### Infura

The Ethereum API service. Nearly all Ethereum applications runs on Infura.

<list-card :items="$page.frontmatter.infura" level="5"/>

---

<CardList :items="$page.frontmatter.base" />
