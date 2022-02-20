<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


# KeystoneJS and NextJS monorepo template

Monorepo template for client-server applications using KeystoneJS (as a server) and NextJS (as a client). There is also *common* library to share code between both server and client.

## Build with

- [KeystoneJS](https://keystonejs.com)
- [NextJS](https://nextjs.org)
- [TypeScript](https://www.typescriptlang.org)
- [ESLint](https://eslint.org)
- [Prettier](https://prettier.io)
- [Husky](https://typicode.github.io/husky/#/)
- [Yarn](https://yarnpkg.com)

## Why yarn workspaces?

First approach to create monorepo was using [Nx](https://nx.dev). But KeystoneJS is at the time of creating this repo not really suited to be used in monorepo. See [discussion](https://github.com/keystonejs/keystone/discussions/7220). Came up with this solution using *Yarn workspaces* which is not that convenient but working.

## Getting started

### Prerequisites

- Node@16
- Yarn

### Installation

Install packages:
```
yarn install
```

## Usage

Just change names in *package.json* files and install packages.

To run bootstraped code locally run `yarn dev:server` to run server and `yarn dev:client` to run client.
