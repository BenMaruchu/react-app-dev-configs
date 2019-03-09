# react-app-configs

This is an opinionated react app development configurations on top of [create-react-app](https://github.com/facebook/create-react-app) generated project.

### Usage

To use this repo just clone it and make sure to change the git origin url so that you won't push you codes by mistake to this repo.

```sh
git clone https://github.com/BenMaruchu/react-app-configs.git $APP_NAME
```

Replace `$APP_NAME` with your application name

> Make sure to install all dependencies depending on your favourite package manager.

If you are using npm remember to delete yarn.lock and then run

```sh
npm install
```

to install all dependencies

If you are using `yarn` just run

```sh
yarn install
```

### Configurations

##### Committing codes

This repo use [commitizen](https://github.com/commitizen/cz-cli) which helps to ensure consistency on how contributors writes commit messages.

To ensure commit message rules are followed there is a [commint linter](https://github.com/conventional-changelog/commitlint) which is run to validate commit message before commiting your codes into the repo.

Based on configs you can commit using `npm scripts` by execute `yarn commit` or `npm run commit` to commit staged changes or normal `git commit` command, but either way your commit messages will be linted.

If you want to stage and commit all changed files you can do that by `yarn commit:all` or `npm run commit:all`.

#### Linting codes

This project extends create-react-app eslint rules and add more rules which can be viewed on .eslintrc file.

#### Linting JSDocs

On documenting code functions and code using JSDocs, there are rules configured on what properties to be included while documenting a piece of code using JSDoc. Read more [eslint-plugin-jsdoc](https://github.com/gajus/eslint-plugin-jsdoc)

#### Formating codes

For code formating [prettier](https://github.com/prettier/prettier) have been configured and used.

#### Generating release changelog

Changelog for releases can generated by running `yarn changelog` or `npm run changelog` which will update `CHANGELOG.md` file by extracting changes from commit messages.

#### LICENSE

MIT License

Copyright (c) 2019 - present BenMaruchu & Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
