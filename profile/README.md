_Hexagonal architecture for API integrations_

[![npm packages](https://img.shields.io/badge/npm-%40superfaceai-5850ec)](https://www.npmjs.com/org/superfaceai)
[![Twitter profile](https://img.shields.io/badge/Twitter-%40superfaceai-5850ec)](https://twitter.com/superfaceai)
[![Discord server](https://img.shields.io/badge/Discord-superface.ai-5850ec)](https://sfc.is/discord)

## Welcome to Superface

API integrations take forever to build. They’re brittle and hard to test. APIs can change on you without notice and break your integrations.

Superface is changing this. If your Node.js app depends on multiple API integrations, Superface is the right tool for you!

Our motivation behind Superface is nicely described in this [video](https://www.youtube.com/watch?v=BCvq3NXFb94) from APIdays conference.

## How it works

Superface is a language and a protocol for abstracting integrations to application use-cases. It allows use-case discovery and distribution of integration code at runtime.

This approach gives you a framework to decouple lifecycle of your application and integrations it uses.

Superface's technology consists of two parts:

- **Registry** for use-case discovery and distribution of integration code at runtime
- **Client** for executing the integration code in your application

You can read more about the technology on [Superface's site](https://superface.ai) and in the [documentation](https://superface.ai/docs).

## Get started

Superface's technology can be implemented in any language. Currently we provide reference implementation for Node.js. For more details check [OneSDK repository](https://github.com/superfaceai/one-sdk-js).

<!-- TODO: sharkies -->
