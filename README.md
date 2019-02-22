# Manage a monorepo with Lerna

An example I’ve put together to demonstrate how Lerna can be used to maintain multiple npm packages with one repository.


## Bootstrap the packages

Installs all of their dependencies and links any cross-dependencies.

```
lerna bootstrap
```

## Run package

```
node packages/calc-module/index.js
```