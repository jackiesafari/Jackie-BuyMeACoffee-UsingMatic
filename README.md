# :coffee: Buy Me A Coffee (Using MATIC) 
Buy Me a Coffee dApp is a gateway to building on Ethereum and providing a real use case in the blockchain. This is the front-end portion of the dapp but there is another repo to check out the smart contract side. 

In this dApp you will be able to send money for coffee to a creator with a memo attached. 

## :turtle: Getting Started

### Time to clone a repo
- Go to the top of the repository and click on the button "Code"
- A dropdown will appear and copy the URL shown
- Open your terminal
- In your terminal go to your desired location or type `cd desktop` and press enter
- Then type `git clone` and paste the URL 
- Press Enter to create your local clone

## Next Steps

In your terminal type

`npm install` to install dependencies

Next, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

Everything you need is inside `pages/index.js`.

To customize the website to load info from your own contract, change the following:

- Update `contractAddress` in `pages/index.js` to your own BuyMeACoffee contract on the Mumbai testnet.
- Update `utils/BuyMeACoffee.json` to match the json artifact for your contract after compilation.
- Update the name and footer text in `pages/index.js` to your own name and info.

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
