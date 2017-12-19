# bloctalk
A decentralized chat application to interact anonymously with those around you

## Development
Install basic node packages with

```npm install```

Next, install the truffle development framework (http://truffleframework.com/)

```npm install -g truffle```

Truffle comes with a useful development console that gives you easy access to all of the tools it provides. To launch the truffle development console

```truffle develop```

In the development console, compile and migrate the smart contracts 

```
compile
migrate
```

### Installing and Configuring MetaMask
The easiest way to interact with our dapp in a browser is through MetaMask, an extension for Chrome and Firefox.

Install MetaMask in your browser.

Once installed, you'll see the MetaMask fox icon next to your address bar. Click the icon and you'll see this screen appear:

http://truffleframework.com/tutorials/images/pet-shop/metamask-privacy.png

Click Accept to accept the Privacy Notice.

http://truffleframework.com/tutorials/images/pet-shop/metamask-terms.png

Then you'll see the Terms of Use. Read them, scrolling to the bottom, and then click Accept there too.

http://truffleframework.com/tutorials/images/pet-shop/metamask-terms.png

Now you'll see the initial MetaMask screen. Click Import Existing DEN.

http://truffleframework.com/tutorials/images/pet-shop/metamask-initial.png

In the box marked Wallet Seed, enter the mnemonic that was displayed when launching Truffle Develop:

```candy maple cake sugar pudding cream honey rich smooth crumble sweet treat```

Enter a password below that and click OK.

http://truffleframework.com/tutorials/images/pet-shop/metamask-seed.png

Now we need to connect MetaMask to the blockchain created by Truffle Develop. Click the menu that shows "Main Network" and select Custom RPC.

In the box titled "New RPC URL" enter http://localhost:9545 and click Save.

http://truffleframework.com/tutorials/images/pet-shop/metamask-customrpc.png

The network name at the top will switch to say "Private Network".

Click the left-pointing arrow next to "Settings" to close out of the page and return to the Accounts page.

Each account created by Truffle Develop is given 100 ether. You'll notice it's slightly less on the first account because some gas was used when the contract itself was deployed.

http://truffleframework.com/tutorials/images/pet-shop/metamask-account1.png

### Launching the application 

Run the liteserver development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.

```
// Serves the front-end on http://localhost:3000
npm run dev
```

