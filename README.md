# ESM Template

This repository is a template to make pure ESM projects using typescript. It contains the minimun required packages to work, to test and to deploy.

## Dependencies

- __[typescript](https://www.npmjs.com/package/typescript)__: The language server and CLI for typescript.
- __[esno](https://www.npmjs.com/package/esno)__: A package to execute TS files without transpile.
- __[ava](https://www.npmjs.com/package/ava)__: Unit testing with native support to ESM.

## How to start

First install the dependencies:
```bash
npm i
```

If you want to execute the project without transpiling, use:
```bash
npm run start
```

If do you want to generate the `*.mjs` files:
```bash
npm run build
```

To execute unit testing:
```bash
npm run test
```