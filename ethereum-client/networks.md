---
description: Networks currently supported by Nethermind Client
---

# Networks

By default Nethermind launches with mainnet network configuration, but it is possible to sync other networks by adding a command line switch:

```
--config [NETWORK_NAME]
```

Network name can be any of the following

* mainnet
* goerli
* sepolia
* gnosis
* poacore
* energyweb
* volta
* kovan (only fast sync and may fail if pWASM transactions appear)

### Mainnet

This is the main Ethereum network. It can be run using config below and this is default setting - mainnet will run if `--config` is not specified as well.

```
Nethermind.Runner --config mainnet
```

{% embed url="https://ethstats.net/" %}

### Görli (goerli)

This is a Clique-PoA based testnet supported by all major clients. It has 15 seconds between blocks that are sealed by Goerli validators.

```
Nethermind.Runner --config goerli
```

{% embed url="https://stats.goerli.net/" %}

{% embed url="https://gitter.im/goerli/testnet" %}

