# ESM/CJS dual package template

This repository is a template to make NPM packages in __ESM__ and __CommonJS__. This repositoy includes:
- The configuration files required and ready to develop in.
- Output in ESM and CommonJS.
- Unit testing.

## Dependencies

- __[typescript](https://www.npmjs.com/package/typescript)__: The language server and CLI for typescript.
- __[ts-node](https://www.npmjs.com/package/ts-node)__: A package to execute TS files without transpile.
- __[ava](https://www.npmjs.com/package/ava)__: Unit testing with native support to ESM.

## How to begin

First install the dependencies:
```bash
npm i
```

If you want to execute the project without transpiling, use:
```bash
npm run start
```

If do you want to transpile your project:
```bash
npm run build
```

To execute unit testing:
```bash
npm run test
```

To execute `./src/index.ts` (as ESM):
```bash
npm run start
```