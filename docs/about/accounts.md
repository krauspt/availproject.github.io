---
id: accounts
title: How to Create and Manage an Avail Account
sidebar_label: Create an Account
description: Comprehensive guide on creating and managing Avail accounts.
keywords:
  - docs
  - avail
  - explorer
  - accounts
image: https://docs.availproject.org/img/avail/AvailDocs.png
---

import useBaseUrl from '@docusaurus/useBaseUrl';

## Introduction

This guide will walk you through the process of creating and managing an Avail account, while also providing insights into the account specifications and formats.

**[<ins>Skip to Creating an Account on the Goldberg Testnet</ins>](#creating-an-account-on-the-goldberg-testnet).**

### Address Specifications & Format

Built on the Substrate framework, Avail leverages its robust and flexible account system to provide users with a secure and efficient way to manage their digital assets and identity.

Avail addresses are encoded in the [<ins>SS58 format</ins>](https://docs.substrate.io/reference/address-formats/), an enhanced version of [<ins>base-58 encoding</ins>](https://en.wikipedia.org/wiki/Binary-to-text_encoding). This format offers several advantages, such as shorter and more identifiable addresses and network-specific prefixes. For a detailed technical explainer, refer to the [<ins>Substrate documentation on Accounts, Addresses, and Keys</ins>](https://docs.substrate.io/learn/accounts-addresses-keys/).

### Avail JS Apps: Your Interface to Avail

[<ins>Avail JS Apps</ins>](https://goldberg.avail.tools/#/explorer), a fork of [<ins>Polkadot JS Apps</ins>](https://polkadot.js.org/apps/#/explorer), serves as your primary interface for the Avail network. Currently, its focus is solely on the Goldberg testnet, and as such, it is also referred to as the **Goldberg Testnet Explorer**. The scope of Avail JS Apps will expand as Avail matures into a production-ready network.

Avail JS aims to offer functionalities similar to those found in the [<ins>Polkadot-JS UI guide</ins>](https://wiki.polkadot.network/docs/polkadotjs-ui), including but not limited to:

- **Accounts**: Create, manage, and recover accounts.
- **Staking**: Engage in network staking and manage validators.
- **Explorer**: Browse blockchain data, view block details, and monitor network activity.

### Seed Phrases

Before creating an account, it's essential to understand [<ins>seed phrases</ins>](https://en.wikipedia.org/wiki/Cryptocurrency_wallet). During the account creation process, you'll receive a seed phrase—a series of words that can be used to recover your account.

> Seed Phrase Security
NEVER share your seed phrase with anyone and keep it in a secure and offline location. Anyone with access to your seed phrase can gain control of your account.

## Creating an Account on the Goldberg Testnet

### 1. Open the Explorer

Navigate to the [Goldberg Avail Explorer](https://goldberg.avail.tools/).

### 2. Go to Accounts

Once on the explorer, go to `Accounts -> Accounts` in the navigation bar.
<img src={useBaseUrl("img/avail/account.png")} width="100%" height="100%" />

### 3. Generate a New Account

Click on the `+Account` button on the right-hand side to initiate the account creation process.
<img src={useBaseUrl("img/avail/add-account.png")} width="100%" height="100%" />

### 4. Follow the Wizard

Follow the on-screen instructions to complete the account creation process. Make sure to securely store your seed phrase for future reference.

### 5. Download the JSON File

Upon completion, a JSON file containing your account information will be downloaded to your file system. You may be prompted to grant browser permissions for the download.

#### What is the JSON File?

The JSON file serves as a backup for your account and contains all the necessary information to recover it. It is encrypted with a password that you set during the account creation process.

> Backup and Recovery
Always keep your JSON file in a secure and offline location. Losing this file and your password could result in the loss of your assets.

## Next Steps

Congratulations on successfully creating and managing your Avail account! Remember to always safeguard your account details, JSON file, and seed phrase to ensure the security of your assets.

Ready to explore further? Navigate to the next guide to learn [<ins>how to use the Goldberg Testnet Explorer</ins>](/docs/about/explorer.md) and get hands-on experience with the network.
