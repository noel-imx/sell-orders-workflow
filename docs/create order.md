# Create sell orders in bulk

This repo will help you create sell orders in bulk. There are some pre-requisites:

1. You must have the private key for the wallet that owns the minted NFTs

## Steps

### 1. Install libraries

```sh
npm install
```

### 2. Update `.env` file

Update the following fields in the `.env` file:

* `OWNER_ACCOUNT_PRIVATE_KEY`:
* `COLLECTION_CONTRACT_ADDRESS`:
* `COLLECTION_PROJECT_ID`:
* `DEPLOYER_ETH_WALLET`:
* `COLLECTION_PROJECT_ID`:

### x. Run the bulk sell order command
```sh
npm run sell-order -- -f d4c564b533f0de2c1123734185fcfb014c8663df8d93325200c01c934494c06e -n 0x461d6816e4cf76ff09be3793c637a094c6ec7fd4 -i 1 -a 10000000000000000 -b 3
```

