<div align="center">
  <a href="https://www.immutable.com">
    <img width="150" src="https://assets-global.website-files.com/5f7eec37ff782e797edabe11/5f8d36771ffcf8c91b03e7f4_dark.svg">
  </a>
  <br>
  <br>
</div>

---

# Create sell orders in bulk

This repo will help you create sell orders in bulk.

## Steps

### 1. Install libraries

```sh
npm install
```

### 2. Update `.env` file

Please enter values for the following fields in the `.env` file:

* `OWNER_ACCOUNT_PRIVATE_KEY`: Private key of the wallet which owns all the minted NFTs that you are trying to bulk list
* `COLLECTION_CONTRACT_ADDRESS`: Collection address (0x....)
* `COLLECTION_PROJECT_ID`: Use this link to find - https://api.ropsten.x.immutable.com/v1/collections/<COLLECTION_CONTRACT_ADDRESS>
* `DEPLOYER_ETH_WALLET`: Wallet address of Cubix test wallet (on which contract is deployed)


### 3. Run the bulk sell order command
```sh
# CLI 
npm run sell-order -- -f <from_private_key> -n <token_address> -i <token_id> -a <sale_amount>  -b <bulk sell order create> 


# Example
npm run sell-order -- -f <please_enter_your_own_private_key> -n 0x461d6816e4cf76ff09be3793c637a094c6ec7fd4 -i 1 -a 10000000000000000 -b 3
```