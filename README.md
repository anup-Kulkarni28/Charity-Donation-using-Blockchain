SecureFund : Crowdfunding Platform Powered by Ethereum Blockchain

The Platform is live on sepolia Test Network and available to use at : [securefund.vercel.app](https://securefund.vercel.app/)

## Problem Statement and Necessity

Crowdfunding is one of the most popular ways to raise funds for any project, cause or for helping any individual in need. With the onset of Covid we have seen a rise in Crowdfunding activities across the globe which includes small campaigns to help people get oxygen and medical help to large funds such as PM Cares.

The major problems with the Current Crowdfunding Platforms that we wanted to solve were :

- Security : As the funds become larger, they need to be heavily secure, although stringent measures such as symmetric encryption are in place to make e-payment safe and secure,it is still vulnerable to hacking. Blockchain — which has never been compromised yet — can provide that level of security.
- Transparency and Anti-Fraud : We have seen, and continue to see a lot of crowdfunding scams happening around. There is no way to see where the funds are being used. We wanted to make the entire flow of funds transparent at every stage, so that there is no possibility of the money being misused.
- Global contribution : With some of the platforms being country specific, it becomes hard for people from other countries to contribute to various campaigns. Using blockchain anyone in the world can contribute to the campaign. Transactions are quick and convenient.

We were highly inspired by the CryptoRelief initiative ([www.cryptorelief.in](https://www.cryptorelief.in)) which raised ~1 billion dollars for Covid Relief in India from the entire global community, in a highly transparent manner.

## Detailed Report and PPT

- A Detailed Report of the Project can be [found here](https://docs.google.com/document/d/1_CdJ5pEimTrejDSBnq9Ze6kz2BcKJ6qtiikqWs0rglc/edit?usp=sharing)
- A Presentation on the Application can be [found here](https://docs.google.com/presentation/d/1-Nbg5tn2UkqDerkinF6yQGOlX1KVBztw/edit#slide=id.p1)

## Screenshots

#### Home Page :

![img1](https://user-images.githubusercontent.com/88583086/194039100-f70771a5-4ad8-4f72-88bd-31c31ddec155.jpg)

### Campaign Page :

![img2](https://user-images.githubusercontent.com/88583086/194039639-a8a5cacf-a779-4564-b215-3d5e5fa92a25.jpg)

### Create Campaign Page :

![img3](https://user-images.githubusercontent.com/88583086/194039263-2f5c1d50-9a6a-432a-93f9-3ff6e1df619f.jpg)

### Withdrawal Request Page :

![img4](https://user-images.githubusercontent.com/88583086/194039676-aef71a6a-cdc8-465a-a752-25f214c7642a.jpg)

## Tech Stack

- Next JS
- Chakra UI
- Solidity
- Web3.js

## To run the application locally

- Fork the Project
- run `yarn install` to install all the dependencies
- run `yarn dev` to run the application locally

## Prerequisites to create Campaign and Contribute

1. Install **Metamask** as Google Chrome Extension and Create an account.
2. Request Ether by sharing your ethereum address in social media <br>(`https://faucet.sepolia.io/)`
3. Get 0.01 ether free by giving the ethereum address <br>`(http://sepolia-faucet.com/)`

## To Deploy your own Contract

1. Create an account in [https://infura.io](https://infura.io/)
2. Create .env file in Ethereum directory and add these line to it.
   > mnemonic = 'Your mnemonic code' <br>
   > link = 'Your infura end point link '
3. Do the Changes that you want to do inside the Solidity File
4. Compile the Contract
   `node compile.js`
5. Deploy Contract by going into smart-contract Directory and run.
   `node deploy.js`

   Copy the contract deploy address and replace it in factory.js file.

6. Replace your "infura end point link" in web3.js file

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
