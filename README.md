# node-express-typescript

<p style="text-align: center;">Node Project Template - Express Typescript</p>

<p style="text-align: center;">![Typescript](https://img.shields.io/badge/Typescript-007ACC?style=for-the-badge&logo=Typescript&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-323330?style=for-the-badge&logo=Jest&logoColor=white)
![Eslint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)</p>

# Installation

The easiest way to get a consistent development environment every time is to make use of the [devcontainer](https://code.visualstudio.com/docs/devcontainers/containers).

Once you open up this project VS Code, run the **Dev Containers: Reopen Folder in Container...** command from the Command Palette **(F1)**

Copy `.env.example` to `.env`. Modify if required.

After that just install packages using npm.

```
npm ci install
```

# Usage

## Build

```
npm run build
```

## Development environment

```
npm run start:devserver
```

## Lint

```
npm run lint
```

## Production environment

```
npm run start
```

## Test

Run all tests:

```
npm run test
```

Run coverage:

```
npm run test:coverage
```

Run a single test file:

```
npm run test:single tests/app.test.ts
```

# License

Copyright © 2023-present Sebastiaan de Haan

This project is [MIT](#LICENSE) licensed.
