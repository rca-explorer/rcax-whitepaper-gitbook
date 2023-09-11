---
description: Our newly launched Polygon (ERC-20) utility token.
---

# 🟠 RCAX Token

Introducing the RCAX Token ($RCAX), the native currency behind RCAX's forthcoming Web3 tools and games designed exclusively for the RCA ecosystem. $RCAX can be acquired solely through the burning of Reddit Collectible Avatars from generations 1 to 4 via the RCAX Token smart contract, as elaborated in the sections to follow.

_**It's important to emphasize that $RCAX may not carry any intrinsic monetary value; it serves exclusively as a utility token integral to RCAX's future Web3 initiatives.**_

### Details

**Name**: RCAX Token\
**Ticker**: ($)RCAX\
**Token Address**: 0xC99BD85BA824De949cf088375225E3FdCDB6696C\
**Max Supply**: 72,290,000\
**Initial Supply**: 0\
**Mintable**: Yes (only by RCA burning)\
**GitHub**: [https://github.com/rca-explorer/rcax-token](https://github.com/rca-explorer/rcax-token)\
**PolygonScan**: [https://polygonscan.com/address/0xC99BD85BA824De949cf088375225E3FdCDB6696C](https://polygonscan.com/address/0xC99BD85BA824De949cf088375225E3FdCDB6696C)\
\
_While the maximum supply is set at 72,290,000, it's important to note that the actual circulating supply is expected to be significantly lower since it is only a hard cap._

{% content-ref url="import-rcax-into-metamask.md" %}
[import-rcax-into-metamask.md](import-rcax-into-metamask.md)
{% endcontent-ref %}

### Mining

Participating in $RCAX token mining is a straightforward process. You can acquire $RCAX by sending any Reddit Collectible Avatar belonging to generations 1 through 4 to the $RCAX token address. Your rewards are calculated using the following principles:

**Base Reward** \
The initial base reward stands at 120 $RCAX and undergoes a halving cycle every 4 weeks until it has halved 13 times, after which the base reward will be 0 $RCAX.

**Reward Modifiers**

<table><thead><tr><th width="127">Modifier</th><th>Base Reward Multiplier</th></tr></thead><tbody><tr><td>Gen 1</td><td>24</td></tr><tr><td>Gen 2</td><td>12</td></tr><tr><td>Gen 3</td><td>6</td></tr><tr><td>Gen 4</td><td>1</td></tr><tr><td>Other</td><td>0</td></tr></tbody></table>

{% hint style="info" %}
Please note that the Avatar supply has no effect on the mine reward. All Avatars within the same generation yield the same reward.
{% endhint %}

{% hint style="info" %}
_**EXAMPLE**_: Sending a Joii Kawaii Girl (Gen 1) to the token address (0xC99BD85BA824De949cf088375225E3FdCDB6696C) will earn you a reward of 2880 (24 \* 120) $RCAX, provided the max supply cap has not been reached and no reward halvings have occurred.
{% endhint %}

{% hint style="info" %}
_**TIP**_: You can easily send Avatars to the $RCAX token address by using https://opensea.io\
\
Just go to your wallet items and select one or multiple Avatars to transfer to 0xC99BD85BA824De949cf088375225E3FdCDB6696C. That is all you need to do to mine $RCAX!\
\
Detailed steps can be found in the **Mine RCAX using OpenSea** page.
{% endhint %}

{% content-ref url="mine-rcax-using-opensea.md" %}
[mine-rcax-using-opensea.md](mine-rcax-using-opensea.md)
{% endcontent-ref %}

**Check Before Sending**\
You can check the current reward for your Collectible Avatar by executing the `getAvatarBurnReward` function in the token smart contract. Use the contract address of your Avatar as input. You can try this and many other public functions here: [https://polygonscan.com/address/0xC99BD85BA824De949cf088375225E3FdCDB6696C#readProxyContract](https://polygonscan.com/address/0xC99BD85BA824De949cf088375225E3FdCDB6696C#readProxyContract)

### Development Fund

The Development Fund is a critical part of the RCAX platform's ongoing improvement efforts. It operates by allocating an additional 10% of mining rewards to a specific wallet with the address 0xB5C42f30cEAE2032F22d364E33A5BaEfA1A043FF.

For example, if someone mines 120 $RCAX tokens, an extra 12 $RCAX tokens will be added to the Development Wallet. This wallet starts with a balance of zero and only grows through mining rewards and community donations.

The purpose of the Development Fund is to support essential aspects of the RCAX platform's growth, such as developer compensation and marketing initiatives. Initially, RCAX manages the fund, but as the project matures, it will transition to a governance model, giving the RCAX community control over its allocation.

### View Balance

You can view your balance using https://rcax.io/wallet or you can import the RCAX token into MetaMask using the token details above.

### Governance

Given the nascent stage of our project, RCAX currently maintains full control over the proxy contract. This grants RCAX the authority to replace the target contract within the proxy at any given moment, introducing a significant degree of authority that requires careful management, transparency, and responsibility.

There are several compelling reasons for this approach to RCAX's initial launch:

1. Early Stage Exploration: With the project just having entered the public domain, new perspectives and scrutiny are inevitable. Individuals examining our tokenomics and smart contract implementation may identify novel ideas, potential risks, or bugs. It is crucial that we can promptly address any emerging issues without the need for protracted hard fork procedures.
2. Community Governance as the Endgame: It is essential to emphasize that our ultimate objective is to evolve RCAX into a community-governed token. However, launching as a community-driven token from the outset presents certain challenges. During the initial stages of a project, the distribution of voting power tokens in the community governance model tends to be uneven. Larger token holders, often referred to as "whales," could exert disproportionate influence over governance decisions. This disparity may hinder the establishment of a truly democratic decision-making process.

In summary, while RCAX currently retains control over the proxy contract, this approach is viewed as a pragmatic means to address potential issues promptly and efficiently. The project's long-term vision remains centered on fostering community governance, with measures in place to address early-stage challenges and ensure fair participation for all token holders.
