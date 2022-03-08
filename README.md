# `@combeenation/ts-config`

> Combeenation TypeScript base config.

## Usage

- Install:

  ```bash
  $ npm i --dev @combeenation/ts-config
  ```

- Create new `tsconfig.json` file or add to `extends` section of existing config.
  Example config using the package:

  ```jsonc
  {
    "extends": "@combeenation/ts-config",
    "compilerOptions": {
      // "outDir" & "srcDir" does not come from the config...
      "outDir": "dist"

      // Overwrite further settings as needed...
    }
  }
  ```
