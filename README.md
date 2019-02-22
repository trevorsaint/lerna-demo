# Manage a monorepo with Lerna

An example I’ve put together to demonstrate how Lerna can be used to maintain multiple npm packages with one repository.


## Install Lerna

Install Lerna on your machine.

```
npm instal -g lerna
```


## Bootstrap the packages

Installs all dependencies and links any cross-dependencies.

```
lerna bootstrap
```

## Run package

```
node packages/calc-module/index.js
```