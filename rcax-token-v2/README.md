---
description: Our newly launched Polygon (ERC-20) utility token.
---

# 🟠 RCAX Token (V2)

Introducing the RCAX Token ($RCAX), the native currency behind RCAX's dApps (decentralized apps) designed exclusively for the RCA ecosystem. $RCAX can be acquired solely through the burning of Reddit Collectible Avatars via the RCAX Token smart contract, as elaborated in the sections to follow.

_**It's important to emphasize that $RCAX may not carry any intrinsic monetary value; it serves exclusively as a utility token integral to RCAX's future Web3 initiatives.**_

### Details

**Name**: RCAX\
**Ticker**: ($)RCAX\
**Token Address**: 0x875f123220024368968d9f1aB1f3F9C2f3fd190d\
**Initial Supply**: 0\
**Max Supply Cap**: 72,290,000\
**Mintable**: Yes (only by RCA burning)\
**GitHub**: [https://github.com/rca-explorer/rcax-token](https://github.com/rcax-project)\
**PolygonScan**: [https://polygonscan.com/address/0x875f123220024368968d9f1aB1f3F9C2f3fd190d](https://polygonscan.com/token/0x875f123220024368968d9f1ab1f3f9c2f3fd190d)

{% content-ref url="import-rcax-into-metamask.md" %}
[import-rcax-into-metamask.md](import-rcax-into-metamask.md)
{% endcontent-ref %}

### Mining

Participating in $RCAX token mining is a straightforward process. You can acquire $RCAX by sending any eligible Reddit Collectible Avatar to the $RCAX token address. Your sent Avatar will then be forwarded to a burn address \`0x00...00dead\` and you will automatically receive your $RCAX mining rewards. The rewards are calculated using the following principles:

**Base Reward** \
The initial base reward stands at 60 $RCAX and undergoes a halving cycle every 24 weeks.

**Reward Modifiers**\
The final mine reward will be calculated by doing \`Base Reward \* Base Reward Multiplier\`.

<table><thead><tr><th width="264">Modifier</th><th>Base Reward Multiplier</th></tr></thead><tbody><tr><td>Gen 1</td><td>24</td></tr><tr><td>Gen 2</td><td>12</td></tr><tr><td>Aww Friends<br>Meme Team<br>Drip squad<br>The Singularity</td><td>4</td></tr><tr><td>Reddit Cup 2022</td><td>0.1</td></tr><tr><td>Super Bowl LVII</td><td>0.1</td></tr><tr><td>Other</td><td>0</td></tr></tbody></table>

{% hint style="info" %}
Please note that the Avatar supply has no effect on the mine reward. All Avatars within the same generation yield the same reward.
{% endhint %}

{% hint style="info" %}
_**EXAMPLE**_: Sending a Joii Kawaii Girl (Gen 1) to the token address (0x875f123220024368968d9f1aB1f3F9C2f3fd190d) will earn you a reward of 1440 (24 \* 60) $RCAX, provided the max supply cap has not been reached and no reward halvings have occurred.
{% endhint %}

{% hint style="info" %}
_**TIP**_: You can easily send Avatars to the $RCAX token address by using https://opensea.io\
\
Just go to your wallet items and select one or multiple Avatars to transfer to 0x875f123220024368968d9f1aB1f3F9C2f3fd190d. That is all you need to do to mine $RCAX!\
\
Detailed steps can be found in the **Mine RCAX using OpenSea** page.
{% endhint %}

{% content-ref url="mine-rcax-using-opensea.md" %}
[mine-rcax-using-opensea.md](mine-rcax-using-opensea.md)
{% endcontent-ref %}

**Check Before Sending**\
You can check the current reward for your Collectible Avatar by executing the `getAvatarBurnReward` function in the token smart contract. Use the contract address of your Avatar as input. You can try this and many other public functions here: [https://polygonscan.com/token/0x875f123220024368968d9f1ab1f3f9c2f3fd190d#readProxyContract](https://polygonscan.com/token/0x875f123220024368968d9f1ab1f3f9c2f3fd190d#readProxyContract)

### Development Fund

The Development Fund is a critical part of the RCAX platform's ongoing improvement efforts. It operates by allocating an additional 15% of mining rewards to a specific wallet with the address 0xB5C42f30cEAE2032F22d364E33A5BaEfA1A043FF.

For example, if someone mines 60 $RCAX tokens, an extra 9 $RCAX tokens will be added to the Development Wallet. This wallet starts with a balance of zero and only grows through mining rewards and community donations.

The purpose of the Development Fund is to support essential aspects of the RCAX platform's growth, such as developer compensation and marketing initiatives. Initially, RCAX manages the fund, but as the project matures, it will transition to a governance model, giving the RCAX community control over its allocation.

### View Balance

You can view your balance using [https://rcax.io/wallet](https://rcax.io/wallet) or you can import the RCAX token into MetaMask using the token details above.

