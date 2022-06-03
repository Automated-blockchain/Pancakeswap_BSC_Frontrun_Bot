# Pancakeswap_BSC_Frontrun_Bot

The front run bot for Pancakeswap (BSC)

Pancakeswap frontrun bot follows the "target" address and trades tokens on Pancakeswap when someone purchases a big portion of the specified token. It can front run that transaction by setting higher gas fee.

## Prerequisities
Node and NPM https://nodejs.org/en/download/
Wallet with BNB for gas and token swap

## Running BOT
Update env.js and provide private key to wallet and token address you want to target.

Bot is preconfigured for Pancakeswap on BSC. Review configuration in constants.js.

Install packages:
```
$ npm install web3
$ npm install axios
$ npm install colors
$ npm install ethereumjs-tx
$ npm install abi-decoder
```

Run script:
```
$ node frontrun.js
```
