<a href="https://bccstudio.biz/"><img align="right" src="src\assets\logo.png" height="80px" /></a>
# BCC DAO Client


## Quick start

Install with `yarn` and launch the app with `yarn start`. By default, the app is configured to connect to the Ethereum Rinkeby testnet.

For connecting to other chains / deployments, a few useful npm scripts are provided:

- Ethereum Mainnet: `yarn start:mainnet` will launch the app, configured to connect to the Ethereum mainnet
- Local development: `yarn start:local` will launch the app, configured to connect to our local development environment. It will also use the local IPFS daemon, if it detects one exists. 
**Note**: Windows users may need to install the [windows-build-tools](https://www.npmjs.com/package/windows-build-tools) before installing this project's dependencies.

