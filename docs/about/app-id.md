---
id: app-ids
title: How to Generate an Avail Application Id
sidebar_label: Generate an AppId
description: 'Learn how to generate unique application identifers for your Avail-based solution.'
keywords:
  - docs
  - avail
  - identifier
  - appid
  - app
  - transaction
image: https://docs.availproject.org/img/avail/AvailDocs.png
---

## Introduction

As a general-purpose base layer, Avail is designed to support many
modular chains at the same time, providing consensus and data
availability to all of them simultaneously.

How does this work? Avail headers contain an index that allows a given
modular chain (or "application" in Avail terminology) to determine and
download _only_ the sections of a block that have data for that
particular application.

This has significant benefits, including:

- Modular applications are mainly unaffected by other uses of the
  base layer at the same time.
- Block sizes can increase without requiring applications to fetch
  more data because they don't fetch the whole block, only what's
  relevant to them.

Data availability sampling is still done on the entire block,
however--this is the process where clients sample tiny parts of
the block at random to verify availability.

If you'd like to learn how your idea could
benefit from Avail, please [join our
Discord](https://discord.gg/S2XQJjHsZt). We'd love to chat.

## Use the Application Id Generator

### Generate a New AppId

1. **Access the Website**: Open your web browser and go to the [<ins>Generator web application</ins>](https://app-id-gen.vercel.app/).

1. **Account Detection / Selection**:

   - The website will automatically detect any accounts linked via browser extensions.
   - Ensure you have the relevant extension installed and are logged in.
   - Select the account you wish to use for the AppId creation.

1. **Input Application Name**: In the provided field, enter the name of your application. Make sure the name is unique and identifies your app.

1. **Send Transaction**: Submit the transaction after entering the application name. This will involve a confirmation step through your browser extension.

1. **Receive Your Application Id:**
   - Upon successful transaction completion, your AppId will be displayed.
   - Note down the Id for future reference.

### Retrieve an Existing AppId

1. **Access the Website**: Navigate to [Generator web application](https://app-id-gen.vercel.app/) in your web browser.

2. **Input Application Name for Id Retrieval**: If you've previously created an AppId but forgot it, you can retrieve it easily. Enter the exact name of your application in the designated field.

3. **Get Your Application Id:**
   - After entering the name, the website will search for your AppId.
   - If the Id exists, it will be displayed on the screen.
   - Note it down for your records.
