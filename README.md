# Opensea BULK Script #

This is repository has been cloned and modified a little bit to fit to our needs
The original repo is [OpenSeaScript](https://github.com/EmanuelCampos/opensea-script.git)


## :computer: About the project

This project was made to mint so many NFTs to the opensea using puppeteer and dappeteer.

![Script Running](flow.gif)

## How To Run

First run `yarn install` to install the packages:

``` bash
yarn install
```

Now configure your `script.ts` with your data

```env
const collectionName = "Your Colleciton Name"

const collectionURL = `https://opensea.io/collection/${collectionName}/assets/create`

const openseaDescription = `Your description here`

const lockedContent = `Locked content text here`

const secretPhase = `here is your secret phase dont share it`

```

Run the command to run the script

```bash
yarn es ./src/script.ts
```


## Authors

| [<img src="https://avatars2.githubusercontent.com/u/16262455?s=115&v=3"><br><sub>@EmanuelCampos</sub>](https://github.com/EmanuelCampos) |
| :------------------------------------------------------------------------------------------------------------------------------: |


yarn es ./src/script.ts

yarn add @chainsafe/dappeteer puppeteer esbuild esbuild-register
yarn install
yarn
npm install --global yarn

