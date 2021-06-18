# @thingbound/eslint-config-typescript

ESLint configuration for TypeScript projects in the @thingbound organization.

This configuration tries to be fairly lenient and error on things that may 
cause bugs. Warnings are provided for some style issues and other things that
may be ignored.

Install `eslint` and the configuration:

```
$ npm install --save-dev eslint @thingbound/eslint-config-typescript
```

A small `.eslintrc.js` is then required to setup the linting:

```javascript
{
  parserOptions: {
    project: './tsconfig.eslint.json'
  },
  extends: [
    '@thingbound/eslint-config-typescript'
  ]
}
```
