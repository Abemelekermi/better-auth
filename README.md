<p align="center">
  <picture>
    <source srcset="./banner-dark.png" media="(prefers-color-scheme: dark)">
    <source srcset="./banner.png" media="(prefers-color-scheme: light)">
    <img src="./banner.png" alt="Better Auth Logo">
  </picture>
  <h2 align="center">
    Better Auth
  </h2>

  <p align="center">
    The most comprehensive authentication library for TypeScript
    <br />
    <a href="https://better-auth.com"><strong>Learn more »</strong></a>
    <br />
    <br />
    <a href="https://discord.com/invite/GYC3W7tZzb">Discord</a>
    ·
    <a href="https://better-auth.com">Website</a>
    ·
    <a href="https://github.com/better-auth/better-auth/issues">Issues</a>
  </p>

[![npm](https://img.shields.io/npm/dm/better-auth)](https://www.npmjs.com/package/better-auth)
[![npm version](https://img.shields.io/npm/v/better-auth.svg)](https://www.npmjs.com/package/better-auth)
[![GitHub stars](https://img.shields.io/github/stars/better-auth/better-auth)](https://github.com/better-auth/better-auth/stargazers)
</p>


> [!WARNING]
> **Note:** 🚧 This project is currently in beta. Features and APIs may change.

## About the Project

Better Auth is framework-agnostic authentication (and authorization) library for TypeScript. It provides a comprehensive set of features out of the box and includes a plugin ecosystem that simplifies adding advanced functionalities with minimal code in short amount of time. Whether you need 2FA, multi-tenant support, or other complex features. It lets you focus on building your actual application instead of reinventing the wheel. 

### Why Better Auth

Authentication in the TypeScript ecosystem is a half-solved problem. Other open-source libraries often requires a lot of additional code for anything beyond basic authentication. Rather than just pushing third-party services as the solution, I believe we can do better as a community—hence, Better Auth.

### Goals
****

- **Be Comprehensive**: save users from reinventing the wheel as much as possible.
- **Prioritize Best Practices**: provide best practices rather than overwhelming configuration options.
- **Framework Agnostic**: Support most frameworks and avoid framework specific features and solutions if possible.
- **Consistency**: Provide a consistent and predictable API across all platforms
- **Type Safety**: Value type-safety and embrace typescript magic when necessary.

### Non-Goals
****

- **JWT-Based Authentication**: We won’t support JWT-based auth unless provided by a third-party plugin.
- **Extensive Customization**: Our focus is on giving you opinionated, best-practice defaults, rather than enabling deep customization.

## Contribution

Better Auth is free and open source project licensed under the [MIT License](./LICENSE.md). You are free to do whatever you want with it.

You could help continuing its development by:

- [Contribute to the source code](./CONTRIBUTING.md)
- [Suggest new features and report issues](https://github.com/better-auth/better-auth/issues)

## Security
If you discover a security vulnerability within Better Auth, please send an e-mail to security@better-auth.com.

All reports will be promptly addressed, and you'll be credited accordingly.