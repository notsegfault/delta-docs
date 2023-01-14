# Delta Vesting Schedule

Delta has a vesting mechanism built into its token that is triggered on transfer. This vesting period is based on a block number schedule. When a transfer occurs, 10% of Delta is unlocked while 90% remains locked. The locked Delta is used by the system to help create a new partially locked type of liquidity called Open Vesting Liquidity (OVL).

The main principles of Delta’s Vesting schedule are the following:

* Delta transfers, start a 14 Day vesting schedule
* Delta transferred during an active vesting schedule cancels that vesting schedule
* Locked Delta from interrupted vesting schedules get distributed to the Deep Farming Vault

To make sure you have a good understanding on how Delta and its vesting schedule works, we visualized the processes that happen during a transfer of the token.

### Initial purchase of Delta: <a href="#initial-purchase-of-delta" id="initial-purchase-of-delta"></a>

<figure><img src="../.gitbook/assets/Untitled design (1).png" alt=""><figcaption></figcaption></figure>

Each Delta token houses the information of a vesting schedule. When Delta is transferred this vesting schedule is activated. In this example the user purchases Delta from the Uniswap Bonding Curve. This transfer activates the internal vesting schedule for the purchased tokens.

### Delta’s Vesting Schedule activates <a href="#deltas-vesting-schedule-activates" id="deltas-vesting-schedule-activates"></a>

{% hint style="warning" %}
The vesting schedule is based on a block number schedule which is roughly 14 days long.
{% endhint %}

When a user purchases Delta, 10% of the total token balance is sent to the user’s wallet, while the remaining 90% is locked in the Delta Vesting Contract. The locked Delta is unlocked linearly over the next 14 days.

Throughout this period the wallet will receive more and more Delta tokens until the initial purchase is available in the User’s wallet.

<figure><img src="../.gitbook/assets/Screenshot 2023-01-12 102231.png" alt=""><figcaption></figcaption></figure>

**Example:**

> _User A buys 100 Delta on Sushiswap. The wallet receives 10 Delta while the rest of the purchase is locked. During the next 14 days his wallet will receive the remaining tokens which unlock linearly. On the second day, the Delta inside User A’s wallet has grown from 10 Delta to 16 Delta. This process will continue until all the initially purchased tokens are received by the wallet. On day 14 User A’s wallet holds 100 Delta._

### Canceling the Vesting Schedule <a href="#canceling-the-vesting-schedule" id="canceling-the-vesting-schedule"></a>

{% hint style="danger" %}
A token transfer cancels the vesting schedule and the remaining locked tokens get distributed to the Vault as staking rewards.
{% endhint %}

**Example:**

> _On day 7, User A decides to sell their 50 Delta tokens while the vesting schedule is still active. This token transfer cancels the vesting schedule which sends the locked Delta to the Deep Farming Vault._

The Deep Farming Vault collects all locked Delta from vesting schedule interruptions. Users are incentivized to stake rLP and Delta tokens in the vault by receiving Delta as rewards.

<figure><img src="../.gitbook/assets/photo_2021-04-01_20-28-53.jpg" alt=""><figcaption></figcaption></figure>

## OVL in the ecosystem <a href="#2919" id="2919"></a>

The Open Vesting Liquidity (OVL), which is created by Delta’s vesting schedule and secured by the Deep Farming Vault is an effective tool to expand the size of our liquidity.

This liquidity can be directed wherever it’s needed. During a time of uncertainty, it can assist in minimizing premiums and overall stabilizing the system.

_​_
