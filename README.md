# Azure SDK Partner Feed Vcpkg Registry
This repo contains vcpkg registry for a select set of Azure SDK releases.

## Important
Do not use this repo unless instructed to - features may not work for your Azure account.
Use [vcpkg](https://github.com/microsoft/vcpkg) or [vcpkg-betas](https://github.com/Azure/azure-sdk-vcpkg-betas) feeds instead.

## Usage
0. These instructions assume you know how to [get Azure SDK from the official vcpkg repo](https://github.com/Azure/azure-sdk-for-cpp#download--install-the-sdk). This document only documents the differences.
1. Download [`vcpkg-configuration.json`](https://github.com/azure/azure-sdk-vcpkg-partner-feed/blob/main/vcpkg-configuration.json) file from this repository, and put it into your vcpkg directory [^1].
2. Use `vcpkg` as usual.
3. Next time a release is available in this repo, get the updated `vcpkg-configuration.json` (step 1).

[^1]: In case you have other private registries configured in `vcpkg-configuration.json`, or have any other changes there that you don't want to be overwritten, manually merge your local config section related to `azure-sdk-vcpkg-partner-feed` repo.

