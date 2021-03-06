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

Executing this script without arguments returns the list of available commands:
```sh
./package.sh
```

## Available commands

- `./package.sh begin`
    > Initialize the project generating a new `package.json` file and installing the dev-dependencies.
    
- `./package.sh clean`
    > Deletes `./dist` folder, and all `./**/*.tsbuildinfo` files.
    
- `./package.sh build`
    > Transpile the entire project.
    
- `./package.sh watch`
    > Transpile and watch the entire project.
    
- `./package.sh test`
    > Test your  project.
