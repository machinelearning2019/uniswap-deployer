# Uniswap Blocklet

A blocklet for uniswap. To learn more about Uniswap, please go to https://github.com/Uniswap

## Run and debug in the cloud with Gitpod

Click the "Open in Gitpod" button, Gitpod will start ABT Node and the blocklet.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/blocklet/uniswap-deployer)

## Run and debug locally

```shell
yarn global add @abtnode/cli
git clone git@github.com:blocklet/uniswap-deployer.git
cd uniswap-deployer
make install
make dep
make build
abtnode init --mode debug
abtnode start
abtnode dev
```

## License

The code is licensed under the MIT license found in the
[LICENSE](LICENSE) file.
