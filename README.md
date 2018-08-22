React 16 in Typescript 3 using Webpack 4
====

[![Build Status](https://ci.ulv.io/api/badges/myth/typescript-react-webpack/status.svg)](https://ci.ulv.io/myth/typescript-react-webpack)

Boilerplate for starting a React 16 application in Typescript 3 using Webpack 4.

Features:

- React 16
- Typescript 3 (transpiling to ES2015)
- Webpack 4
- Webpack Dev Server 3
- CSS Loader
- SASS / SCSS Loader
- Extract HTML Plugin
- Source Maps / Source Map Loader
- PostCSS with Autoprefixer
- UglifyJS and OptimizeCSSAssets minimizers for production optimization
- Hot Module Reload (HMR) support

#### Install

Install system dependencies

```
apt install nodejs yarn
```

Install JS dependencies

```
make install
```

or alternatively 

```
yarn install --ignore-optional
```

#### Build a development bundle

```
make dev
```

or alternatively

```
yarn run build:dev
```

#### Build a production bundle

```
make prod
```

or alternatively

```
yarn run build:prod
```

#### Run tests

Run linting and tests

```
make test
```

or alternatively

```
yarn run test
```

#### Run Webpack development server

Run webpack development server

```
make run
```

or alternatively

```
yarn run dev
```
