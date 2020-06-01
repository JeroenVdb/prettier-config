# prettier-config

Personal prettier for pet projects.

## Usage

```
npm install @jeroenvdb/prettier-config --save-dev
```

```
# .prettierrc.js

module.exports = {
    ...require("@jeroenvdb/prettier-config")
};

```

## Publish to NPM

```
npmrc default # to activate the public npm.js registry
npm login
npm publish --access public
```
