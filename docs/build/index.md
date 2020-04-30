---
title: Start Building
meta:
  - name: description
    content: Learn the basics of Ethereum with Ethereum Studio, our web-based IDE for building and testing smart contracts.
  - property: og:title
    content: Start Building | Ethereum.org
  - property: og:description
    content: Learn the basics of Ethereum with Ethereum Studio, our web-based IDE for building and testing smart contracts.
sidebar: false
layout: home
hideHero: true
lang: en-US
base:
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Ethereum and APIs
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /build/apis/
      button: true
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Block explorers
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /build/block-explorers/
      button: true
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Clients and nodes
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /build/clients-and-nodes/
      button: true
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Design and UX
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /build/design-and-ux/
      button: true
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Developer tools
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /build/developer-tools/
      button: true
base2:
  - title: APIs
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/apis/
  - title: Block explorers
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/block-explorers/
  - title: Clients and nodes
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/clients-and-nodes/
  - title: Design and UX
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/design-and-ux/
  - title: Developer tools
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/developer-tools/
  - title: Integrated development environments
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/integrated-development-environments/
  - title: Security
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/security/
  - title: Smart contract languages
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/smart-contract-languages/
  - title: Standards
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/standards/
  - title: Storage
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/storage/
  - title: Testing
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/testing/
  - title: Testnets and faucets
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      to: /build/testnets-and-faucets/
base3:
  - header: https://source.unsplash.com/featured?waving
    hero: true
    level: 2
    title: Our docs
    content: Our docs will walk you through the various stages of setting working on your Ethereum application. They cover developer tools , programming languages , security tools  and more
    link:
      text: Read the docs
      to: /developers/
      button: true
---

<BuildPage />

# Need some help?

Dive into our documentation if you need some help setting up your Ethereum application.

<CardList :items="$page.frontmatter.base" />
<CardList :items="$page.frontmatter.base2" level="2" desktopColumns="2"/>
<CardList :items="$page.frontmatter.base3" level="2" desktopColumns="1"/>

Option 1: picture cards for docs sections
Option 2: card list for docs sections
Option 3: one card to a docs landing page which is the jumping off point

Make sure developer support and training is covered on this page (most already is)
Note: this list is currently in alphabetic order but maybe there's a better order e.g. the steps you'd undertake, creating a dapp
