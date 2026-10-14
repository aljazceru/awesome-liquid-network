---
layout: default
title: Liquid Network Directory
description: A curated list of Liquid Network resources, libraries, tools and applications. Liquid Network is a Bitcoin layer-2 (technically sidechain) enabling the issuance of security tokens and other digital assets.
permalink: /
---

# Liquid Network Resources

A curated list of Liquid Network resources, libraries, tools and applications. Liquid Network is a Bitcoin layer-2 (technically sidechain) enabling the issuance of security tokens and other digital assets.

## What is the Liquid Network?

The Liquid Network is a Bitcoin sidechain operated by a federation of functionaries. It enables faster settlement (2-minute blocks vs Bitcoin's 10-minute), confidential transactions (amounts and asset types are blinded), and the issuance of custom tokens pegged to LBTC. It's run by Blockstream and partner exchanges; trust is distributed across the federation rather than a single operator.

## Where to start

Start with the [official Liquid documentation](https://docs.liquid.net/) and the [Elements project](https://elementsproject.org/), since Liquid is built on top of Elements. If you're issuing an asset, the [Liquid Asset Issuance guide](https://docs.liquid.net/docs/issuance) is the canonical reference. For development, the [Liquid Wallet Kit (LWK)](https://github.com/Blockstream/lwk) gives you a Rust/WASM toolkit for Liquid wallets without needing to run a full node.

This directory is organized by category. Pick the workflow that matches what you're trying to do.

## Browse by category

- [Official Resources]({{ '/official-resources/' | relative_url }}) — Liquid Network project home, technical documentation, official releases
- [Documentation & Guides]({{ '/documentation/' | relative_url }}) — getting started, asset labeling, multisig issuance, hardware node setup
- [Explorers]({{ '/explorers/' | relative_url }}) — block explorers, asset registries, electrum servers
- [Network Tools]({{ '/network-tools/' | relative_url }}) — network statistics, sidechain bridges, monitoring
- [Asset Management]({{ '/asset-management/' | relative_url }}) — mainnet/testnet asset registries, AMP, AMMs
- [Development Tools]({{ '/development-tools/' | relative_url }}) — wallets, debugging, swap infrastructure, DEXs
- [Libraries]({{ '/libraries/' | relative_url }}) — Rust, Go, JavaScript, Python, Dart bindings
- [Testing Resources]({{ '/testing-resources/' | relative_url }}) — testnet faucets, demo assets, testnet explorers
- [Wallets]({{ '/wallets/' | relative_url }}) — Marina, Jade, Green, Aqua, Bull Bitcoin, SideSwap

## Contributing

If you'd like to add something to this list, please submit a [Pull Request on GitHub](https://github.com/aljazceru/awesome-liquid-network).

This resource guide is maintained by [aljaz](https://disobey.dev/contact/). Your contributions help keep this information up-to-date and valuable for the Liquid Network community.
