# Sasona

A decentralised payment network for AI agents: protected payments, and chargebacks when a purchase does not deliver.

## The coin is live on Solana mainnet

SASONA launched on 20 October 2026. **The only real SASONA is this contract address:**

```
8xH5RFEkSyneYBhCZh5gi2svgdyrDCREW9SxCfKuYgFd
```

Other people opened pools with fake coins using the same name. Only the address counts. Do not search for it by name.

**Check it yourself.** Open the address on a Solana explorer:
- the mint authority and the freeze authority are both none, so nobody can make more or freeze a wallet
- the name, ticker and logo cannot be changed
- the supply is at most 1,000,000,000, made at launch, and nobody can add to it
- the liquidity added to the pool at launch is locked for good
- the three locks release every hour over a year and cannot be cancelled

Or run [`sasona-coin`](https://github.com/sasona-network/sasona-coin)'s checker, which reads these from the chain.

Every address is listed on [sasona.ai/sasona-coin](https://sasona.ai/sasona-coin).

## The network

The coin is live. The network's contract is not built yet, and the network is not open.

The repositories below, apart from `sasona-coin`, hold an earlier design. It was built on Solana devnet and has since been superseded. They are kept as a record.

| Repository | What's in it |
|---|---|
| [`sasona-coin`](https://github.com/sasona-network/sasona-coin) | Check the SASONA coin from the chain |
| [`roadmap`](https://github.com/sasona-network/roadmap) | The first design's plan, and a proof for each part built on devnet |
| [`sasona-protocol`](https://github.com/sasona-network/sasona-protocol) | The first design's rules |
| [`sasona-program`](https://github.com/sasona-network/sasona-program) | The first design's devnet contract |
| [`sasona-node`](https://github.com/sasona-network/sasona-node) | The first design's member software |
| [`sasona-sdk`](https://github.com/sasona-network/sasona-sdk) | The first design's client |

Site: [sasona.ai](https://sasona.ai). On X: [@SasonaNetwork](https://x.com/SasonaNetwork).

Nothing here is a recommendation to buy SASONA. If you buy it, you could lose all of your money.
