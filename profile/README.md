_Let AI connect the APIs for you_

[![npm packages](https://img.shields.io/badge/npm-%40superfaceai-5850ec)](https://www.npmjs.com/org/superfaceai)
[![Twitter profile](https://img.shields.io/badge/Twitter-%40superfaceai-5850ec)](https://twitter.com/superfaceai)
[![GitHub Discussions](https://img.shields.io/github/discussions/superfaceai/.github?color=5850ec)](https://github.com/orgs/superfaceai/discussions)

## Superface.ai

Integrations, generated code, and API documentation... All suck.

If your app depends on multiple API integrations, Superface is the right solution for you.

Want to see it in action? [Check out the Superface CLI overview video](https://www.youtube.com/watch?v=anweAsYLqo8) that demonstrates using an Open API Specification to create Comlinks that can send an email with Resend.

## How it works

Superface handles the documentation analysis to create a Comlink that you can use to communicate with the API of your choice directly.

This approach gives you a framework to decouple the lifecycle of your application and the integrations it uses.

Superface has two parts:

- **[Superface CLI](https://github.com/superfaceai/cli)** for analysis and creation of Comlinks.
- **[OneSDK](https://github.com/superfaceai/one-sdk)** for executing the integration code in your application.

Superface does not rely on any proxy. There is no integration middleman between your application and the APIs it uses.

## Get started today

You can install the Superface CLI via Homebrew:

```
brew install superfaceai/cli/superface
```
Or via NPM:

```
npm install -g @superfaceai/cli@latest
```
