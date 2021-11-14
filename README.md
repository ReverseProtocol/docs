---
description: An introduction to the protocol
cover: .gitbook/assets/Group 3445 (2).png
coverY: 0
---

# Introduction

{% hint style="info" %}
As of October 27, 2021, this Documentation should be considered v0.1.1
{% endhint %}

The Reverse Protocol is a unique, OHM-Esque yield generating and treasury strategies protocol built on the Harmony Blockchain. Reverse introduces game-theory-inspired products which aim to ensure the long-term sustainability of the protocol, namely: bonding pools, decentralized treasury management, composable and double-layered single-staking through sRVRS (a derivative of Reverse’s native token RVRS), and rebased APYs for liquidity providers.

The protocol's treasury mints RVRS tokens on each block, the majority of which are distributed through bonding pools, single-asset auto-compounding staking, and liquidity incentives.&#x20;

Reverse's participants may leverage their own liquidity or single assets** **or give these up to the protocol's treasuries by entering bonding pools for a much higher yield in RVRS tokens, although users would be forfeiting their underlying assets, these allow the protocol's Governance to control its own liquidity while burning a percentage of it, offsetting token inflation and locking permanent liquidity. Thus, users willing to bet on the protocol's growth can benefit by leveraging auto-compounding balances and higher ROI while benefiting the protocol.

Contrary to other Defi platforms, Reverse is built to dynamically manage its Governance token emissions to sustain high, reliable yields for its liquidity providers and stakers. Once APYs fall below a certain threshold, they will be rebased to ensure sustainable yield. That is, assuming `P = APYs falling below a set treshold`, and `Q = An emission rebase,`

$$
P ⇒ Q
$$

This regular adjustment, in addition to bonding pools, single-asset staking, and a decentralized treasury controlling most of the governance token's liquidity, is designed to create a similar effect to the popular Olympus (OHM), Wonderland (TIME). or Klima DAO (KLIMA) Protocols. However, Reverse should not be considered a “reserve currency” project like such.

### Reverseum Treasury

Forfeited assets are accumulated in the Reverseum Treasury for the protocol's benefit. The liquidity and single assets will be actively managed to maximize their efficiency by the protocol's Governance. An example of this process would be as follows:

1. A protocol's user proposes a strategy in which 10% of the treasury assets are deployed on UST staking on [Anchor Protocol](https://anchorprotocol.com) and using the yield generated to support RVRS tokens through buybacks and burns.
2. A discussion is generated and if the sentiment is positive, a fair and decentralized Governance proposal based on [Snapshot strategies](https://github.com/snapshot-labs) will take place.
3. If the proposal passes, the assets of the treasury will be deployed accordingly, following the strategy of the previously made proposal.
