# Style Guide
As we are using TypeScript for this project, we will strive to adhere to TypeScript standards, which can be reviewed here: https://www.typescriptlang.org/docs/home.html. Once we arrive at the desired TypeScript configuration, that will be linked here.

[TypeScript Configuration](./configs/tsconfig.json)

## Environment

The following elements will make up the backbone of the development environment. It may be necessary to install the following elements globally to get them to function properly.

- [ ] homebrew -> [Homepage](https://brew.sh)
- [ ] node.js -> [Installation Instructions](https://nodejs.org/en/download/package-manager/#macos)
- [ ] Vue CLI -> [Getting Started](https://cli.vuejs.org/#getting-started)
- [ ] TypeScript -> [Installing TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html#installing-typescript)
- [ ] Prettier -> [Installing Prettier](https://prettier.io/docs/en/install.html) **<- Install global ()**
- [ ] TSLint -> [TSLint command-line interface](https://palantir.github.io/tslint/usage/cli/) **<- Install global ()**

## Formatting / Linting
We will be using Prettier and TSlint or ESlint (currently absorbing TSlint), code formatting standards, with the linked configurations. It is advised that prettier is either run as a plugin in your IDE of choice or as part of the build process via a script entry in package.json

[Prettier Configuration](./configs/prettier.config.js)

[TSlint Configuration](./configs/tslint.json)

## Naming strategies
The following naming strategies will be in use in all code for this project:
* File Naming - Kebab case (`lp-<filename>-<descriptor>.<extension>`)
* CSS Styling - Kebab case (`lp-<classname-or-id>`)
* Variable Naming - Camel case (`someVariable`)
* Functions/Methods - Camel case (`someFunction()`)
* Core Objects - Upper first (`import Object from 'library';`)
* Component Names - Upper first (`name: ThisComponent`)


## Automation / Deployment

## Unit testing practices / Coverage expectation
We aim to conduct unit testing using mocha, chai, sinon, and chai-as-expected. Additional testing libraries may be required and will be published here and included as a devDependency in the final code framework package for the NPM module format.

Information for using TypeScript for the unit testing:
https://journal.artfuldev.com/unit-testing-node-applications-with-typescript-using-mocha-and-chai-384ef05f32b2

Target coverage: 80%
Testing expectation: All methods and functions within source files (.ts & .vue) should be exercised to be considered for merging into master branch. Testing should include positive and negative testing to thoroughly exercise the code.
