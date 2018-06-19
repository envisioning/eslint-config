# @envisioning/eslint-config

## Usage

### Install peer dependencies

```bash
yarn add -D babel-eslint@8.2.3 eslint@4.19.1 eslint-config-airbnb@16.1.0 eslint-config-prettier@2.9.0 eslint-plugin-babel@5.1.0 eslint-plugin-import@2.12.0 eslint-plugin-jest@21.17.0 eslint-plugin-jsx-a11y@6.0.3 eslint-plugin-prettier@2.6.0 eslint-plugin-react@7.9.1 prettier@1.13.5
```

### Install this package
```bash
yarn add -D @envisioning/eslint-config
```

### Add config into your .eslintrc.js file

```js
module.exports = {
  extends: "@envisioning"
}
```

### *If you are using VSCode:
- Disable Prettier extension
- Install ESLint extension
