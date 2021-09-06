Docs coming soon.

In the meantime, you might find this helpful too:
https://hackmd.io/@levicook/HJcDneEWF




# .env properties
```
REACT_APP_CANDY_MACHINE_CONFIG="redacted"  // From .cache/temp, the program > config proprty

{"program":{"uuid":"APjkMe","config":"APhgMeJV....redacted.....7L3yApd3"}, ... }

REACT_APP_CANDY_MACHINE_ID="redacted" // the ID that you get back after a successful Candy Machine creation...example:

$ ts-node cli create_candy_machine -k ~/.config/solana/devnet.json -p 1
Done: CANDYMACHINE: H2YZ5u...redacted....aCR9CJ

REACT_APP_CANDY_START_DATE=1630422000000 // unix timestamp to start the minting process
REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=https://explorer-api.devnet.solana.com
REACT_APP_TREASURY_ADDRESS="redacted" // Wallet public key that was used when creating the candy machine through metaplex command line (upload, create candy machine)
```


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
