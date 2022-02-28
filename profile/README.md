_Hexagonal architecture for API integrations_

[![npm packages](https://img.shields.io/badge/npm-%40superfaceai-5850ec)](https://www.npmjs.com/org/superfaceai)
[![Twitter profile](https://img.shields.io/badge/Twitter-%40superfaceai-5850ec)](https://twitter.com/superfaceai)
[![Discord server](https://img.shields.io/badge/Discord-superface.ai-5850ec)](https://sfc.is/discord)

## Welcome to Superface

API integrations take forever to build. They’re brittle and hard to test. APIs can change on you without notice and break your integrations.

Superface changes this. If your Node.js app depends on multiple API integrations, Superface is the right solution for you!

The motivation behind Superface is described in [this video](https://www.youtube.com/watch?v=BCvq3NXFb94) from APIdays conference.

## How it works

Superface is a language and a protocol for abstracting integrations to application use-cases. It allows use-case discovery and distribution of integration code at runtime.

This approach gives you a framework to decouple lifecycle of your application and integrations it uses. 

Superface has two parts:

- **Registry** for use-case discovery and distribution of integration code at runtime
- **Client** for executing the integration code in your application

Superface does not rely on any proxy. There is no integration middleman between your application and the APIs it uses. 

You can read more about Superface on its [homepage](https://superface.ai) and in the [documentation](https://superface.ai/docs).

## Get started

Superface protocol can be implemented in any language. The first production-ready implementation is in Node.js. For more details check [OneSDK repository](https://github.com/superfaceai/one-sdk-js).

<!-- TODO: sharkies -->
