Implementation of contracts for [ERC-4337](https://eips.ethereum.org/EIPS/eip-4337) account abstraction via alternative mempool.

# Setup

```
npm i --force
```

(dependencies cannot be fixed right now)

Leave the terminal running with:

```
npx hardhat node
```

Then, on a second terminal:

```
cd frontend && npm i
npm start
```

Navigate to `localhost:3000` and connect your wallet. The metamask network must be configured to a local hardhat.

# Resources

[Vitalik's post on account abstraction without Ethereum protocol changes](https://medium.com/infinitism/erc-4337-account-abstraction-without-ethereum-protocol-changes-d75c9d94dc4a)

[Discord server](http://discord.gg/fbDyENb6Y9)

[Bundler reference implementation](https://github.com/eth-infinitism/bundler)

[Bundler specification test suite](https://github.com/eth-infinitism/bundler-spec-tests)
