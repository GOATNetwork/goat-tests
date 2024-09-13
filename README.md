# goat-tests

## Deposit

## v0

p2wsh

```
<evmAddress> OP_DROP <relayerPubkey> OP_CHECKSIG
```

### v1

p2wpkh + OP_RETURNS

```
OP_RETURNS [<prefix> || <evmAddress>]
```

prefix

- regtest `GTT0`
- testnet/signet: `GTV1`
- mainnet: `GTV2`
