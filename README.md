
# Election - DAPP Tutorial
Build your first decentralized application, or Dapp, on the Ethereum Network with this tutorial!

Full Free Video Tutorial:**
https://youtu.be/3681ZYbDSSk

## 2019 Updated Code
https://github.com/dappuniversity/election/tree/2019_update

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites to follow along with the tutorial. See free video tutorial or a full explanation of each prerequisite.
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/dappuniversity/election`

## Step 2. Install dependencies
```
$ cd election
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance. See free video tutorial for full explanation.


## Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

If you get stuck, please reference the free video tutorial.

## DISCLOSURES:
@MaxMeeuwis used the election GitHub repository of @dappuniversity for a high school project and tweaked it in minor detail. 
As a result, a community of ex-high school students (and their parents) have begotten (increased) awareness on the topic of digital voting and the Ethereum blockchain.
Because @MaxMeeuwis never asked permission from @dappuniversity, all credits for the efforts besides the tweaking of the minor details are given to @dappuniversity,
and the associated rights belong to @dappuniversity.

