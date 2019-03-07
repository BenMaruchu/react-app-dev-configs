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

### Configuration included in this repo

##### Committing codes

This repo use [commitizen](https://github.com/commitizen/cz-cli) which helps to ensure consistency on how people writes commit messages.

To ensure commit message rules are followed there is a [commint linter](https://github.com/conventional-changelog/commitlint) which is run to validate commit message before commiting your codes into the repo.

#### Linting codes

#### Linting JSDocs

#### Formating codes

#### Generating release changelog
