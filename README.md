# eslint-config-base

Base Eslint rules by Nviro

## Installation

`npm i --save-dev @nviro/eslint-config-base`

Once the `@nviro/eslint-config-base` package is installed, you can use it by specifying `@nviro/base` in the extends section of your ESLint configuration.

``` js
{
  "extends": "@nviro/base", // or ["eslint:recommended", "@nviro/base"] if you want "eslint:recommended" and "@nviro/base" rules
  "rules": {
    // Additional rules...
  }
}
```
