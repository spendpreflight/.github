# SpendPreflight

Trust and verification tools for stablecoin payments.

About to pay? Call **preflight_payment** before signing an x402 payment, then enforce allow/hold/block within your existing authorization. ERC-8478 binding verification is a separate tool. Selling via x402? Start with free Lint and monitoring.

[Website](https://spendpreflight.com/) · [Tools](https://spendpreflight.com/tools/) · [Three runnable examples](https://github.com/spendpreflight/examples) · [SDK](https://github.com/spendpreflight/spendpreflight-js)

## Dated ERC-8004 payment identity

SpendPreflight's payout wallet (0xBf4164e07552e4c1b1B1597E72C7acAA3F0a1c58) is verifiably bound to its ERC-8004 identity on Base, agent #1151628. Registered November 2, 2026 Pacific (November 3 UTC); the live self-check returned verified-wallet on 2026-11-03T13:18:52.000Z at Base block 53461275.

[Registration transaction on BaseScan](https://basescan.org/tx/0x93bb25e3d17c92a3c7e2392586c9cbbe9c3fcaa5ea826b40274ab9c33174f118) · [Dated live self-check: signed result and evidence](https://spendpreflight.com/tools/payee-binding/self-check-2026-11-03.json). Dated live observation, not continuous monitoring, reputation, delivery, safety or permission to pay.

The ERC-8478 draft author’s October 28, 2026 Robinhood Chain census found 5 matching payment addresses among 5,575 agents returning x402 payment requirements (fewer than 0.1%), from 20,046 registered agents. Almost all mismatches came from one legitimate shared-treasury operator. This is a dated, single-chain observation, not an ecosystem-wide rate, ranking or evidence of fraud. [Pinned census source](https://github.com/ethereum/ERCs/blob/8077443251fb6adc6c22afac6de258900d26ca8e/ERCS/erc-8478.md).
