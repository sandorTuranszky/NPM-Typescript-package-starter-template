# NPM Typescript package starter template

Based on [Step by step: Building and publishing an NPM Typescript package](https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c). It uses the deprecated TSLint and I updated it to used ESlint based on [TSLint is deprecated: How to upgrade to ESlint](https://www.darraghoriordan.com/2020/03/06/upgrade-tslint-deprecated-to-eslint/)

### Features

- Typescript
- ESlint
- Prettier
- Tesing with Jest

### NPM scripts

- `npm build` - build source code
- `npm test` - run tests
- `npm lint` - run ESlint
- `npm format` - format code with Prettier

There ate more scripts, e.g: `prepare`, `preversion` ... that are nicely explained in [Step by step: Building and publishing an NPM Typescript package](https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c)

### Publish a package to NPM

- Create an NPM account (if you do not have one yet) - https://www.npmjs.com/signup
- `npm login` - login to you NPM account
- `npm publish` - Publish to NPM
