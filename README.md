# Optimizely Node SDK
[![Build Status](https://travis-ci.org/optimizely/node-sdk.svg?branch=master)](https://travis-ci.org/optimizely/node-sdk)
[![Coverage Status](https://coveralls.io/repos/github/optimizely/node-sdk/badge.svg?branch=master&t=pegN7y)](https://coveralls.io/github/optimizely/node-sdk?branch=master)
[![Known Vulnerabilities](https://snyk.io/test/github/optimizely/node-sdk/badge.svg)](https://snyk.io/test/github/optimizely/node-sdk)

This repository houses the Node SDK for Optimizely X Full Stack.

## Upgrading to 2.0
We have combined both the [JavaScript](https://github.com/optimizely/javascript-sdk) and the Node SDK repos and packages into one for version 2.0 and forward. In order to use the Feature Management APIs, please refer to the new [combined repository](https://github.com/optimizely/javascript-sdk/tree/master/packages/optimizely-sdk).

## Getting Started

### Installing the SDK

The SDK is available through [npm](https://npmjs.com/package/optimizely-server-sdk). To install:

```
npm install optimizely-server-sdk --save
```

### Using the SDK
See the Optimizely X Full Stack testing [developer documentation](http://developers.optimizely.com/server/reference/index.html) to learn how to set up your first Node project and use the SDK.

## Development

### Installing dependencies

```npm install```

### Unit tests

You can run all unit tests with:
```
npm test
```

### Benchmarking tests

You can run benchmarking tests with:
```
npm run profile-test
```

### Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md).
