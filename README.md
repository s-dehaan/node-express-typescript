# node-typescript

Node Project - Express Typescript

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
