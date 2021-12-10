# eslint-config-base

Base Eslint rules by CSW Consultores Ambientales

## Installation

`npm i --save-dev @csw/eslint-config-base`

Once the `@csw/eslint-config-base` package is installed, you can use it by specifying `@csw/base` in the extends section of your ESLint configuration.

``` js
{
  "extends": "@csw/base", // or ["eslint:recommended", "@csw/base"] if you want "eslint:recommended" and "@csw/base" rules
  "rules": {
    // Additional rules...
  }
}
```
