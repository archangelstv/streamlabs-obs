# Streamlabs OBS

[![Build Status](https://dev.azure.com/streamlabs/Streamlabs%20OBS/_apis/build/status/stream-labs.streamlabs-obs?branchName=staging)](https://dev.azure.com/streamlabs/Streamlabs%20OBS/_build/latest?definitionId=1&branchName=staging)

Simple, powerful, and efficient live streaming software built on Electron and OBS.

![Streamlabs OBS](https://cdn.streamlabs.com/slobs/slobs-chatbox.png)

This application currently only supports 64-bit Windows.

## Dependencies

### Node.js

Node is required for installing npm packages and for running
various scripts.  We recommend the current LTS release, 8.x.x:

https://nodejs.org

### Yarn

In order to ensure you are using the correct version of each
node module, you should use the yarn package manager.
Installation instructions can be found here:

https://yarnpkg.com/en/docs/install

## Installation

Install all node modules via yarn:

```
yarn install
```

Then, compile assets with webpack:

```
yarn compile
```



