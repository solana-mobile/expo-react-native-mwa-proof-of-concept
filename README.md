# Solana Mobile Expo Go Proof of Concept

This repository is an example of how you can use `@solana-mobile/mobile-wallet-adapter-protocol` in an Expo Go project through the use of a custom Expo [development build](https://docs.expo.dev/development/create-development-builds/).

## Background

Expo Go bundles a hand-picked set of native modules. This is what [Expo has to say](https://github.com/expo/fyi/blob/main/whats-in-the-sdk.md) if you want to use a module _not_ on that list:

> We only include native modules in the Expo SDK if we believe they satisfy a wide range of needs, or if we think that integrating them deeply into Expo tools and services will provide additional value. If you need a specific tool that isn't provided in the Expo SDK, which is a very common requirement, then it's time to migrate from Expo Go to development builds.

## Quick Start

Here's how to create an Expo Development Build that includes the Solana Mobile Stack's Mobile Wallet Adapter Protocol. You will need an [Expo account](https://expo.dev/signup).

```shell
npm install
npx eas build --profile development --platform android
npm start
```
