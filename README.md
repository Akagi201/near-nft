# near-nft

## Build Contract

```sh
make contract
```

## Deploy and Init Contract

```sh
near create-account nearnft.akagi201.testnet --masterAccount akagi201.testnet
make deploy-contract
near call nearnft.akagi201.testnet new_default_meta '{"owner_id": "nearnft.akagi201.testnet"}' --accountId nearnft.akagi201.testnet
```

## Build frontend

```sh
make frontend
```

## Deploy frontend

```sh
make deploy-frontend
```

## Start local frontend

```sh
make start-frontend
```
