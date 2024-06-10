# Browser Extension

This sub-project consists of following components:

- [Extension on Manifest V2](./mv2/README.md)
- [Extension on Manifest V3](./mv3/README.md)
- [Common code between above two versions](./common/README.md)
- [Configurations - browser, environment](./config/README.md)

## Install

To install all components:

```sh
./install.sh
```

## Build

To build all components:

```sh
./build.sh
```
By default, this builds the components for local environment.

To run locally on chrome:
After building, import the dist folder from the browser-extension project into Chrome extensions. Then, start the application in the `app` folder to access the web application.

### For beta environment

```sh
./build.sh beta
```

### For production environment

```sh
./build.sh prod
```

## Test

```sh
./test.sh
```

## Run

Follow READMEs of individual components for further guidance.
