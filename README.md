# bloctalk
A decentralized chat application to interact anonymously with those around you

## Development
Install the truffle development framework (http://truffleframework.com/)

```npm install -g truffle```

Truffle comes with a useful development console that gives you easy access to all of the tools it provides. To launch the truffle development console

```truffle develop```

In the development console, compile and migrate the smart contracts 

```
compile
migrate
```

Run the liteserver development server (outside the development console) for front-end hot reloading. Smart contract changes must be manually recompiled and migrated.

```
// Serves the front-end on http://localhost:3000
npm run dev
```
