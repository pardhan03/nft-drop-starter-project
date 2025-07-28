# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

{
	"price": 0.1, // This refers to price of each NFT
	"number": 3, // Number of the NFT we want to mint
	"gatekeeper": null,
	"solTreasuryAccount": "", // This should be our own wallet address
    // When the NFT will sold the money will be transfer to the soltreasuryaccount
	"splTokenAccount": null,
	"splToken": null,
	"goLiveDate": "05 Jan 2021 00:00:00 GMT", // When the minting of the nft will start
	"endSettings": null,
	"whitelistMintSettings": null,
	"hiddenSettings": null,
	"storage": "arweave", // where we want to store the NFTs
	"ipfsInfuraProjectId": null,
	"ipfsInfuraSecret": null,
	"awsS3Bucket": null,
	"noRetainAuthority": false,
	"noMutable": false
}

REACT_APP_CANDY_MACHINE_ID=<YOUR CANDY MACHINE ID GOES HERE>
REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=https://explorer-api.devnet.solana.com