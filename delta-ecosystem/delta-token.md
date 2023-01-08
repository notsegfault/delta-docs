# Delta Token

The Delta token has a built in [vesting mechanism](delta-vesting-schedule.md) which is triggered on transfer. This vesting period is based on a block number schedule. When a transfer occurs, 10% of Delta is transferred while 90% remains locked, linearly unlocking over the next 14 days. Vesting schedules can be interrupted which lead to the immature Delta being distributed to the [Deep Farming Vault](../deep-farming-vault.md).

## Delta Tokenomics <a href="#b988" id="b988"></a>

{% hint style="success" %}
**Total supply:** 45,000,000 DELTA (Fixed Supply, minting not possible)
{% endhint %}

### Delta in the ecosystem <a href="#delta-in-the-ecosystem" id="delta-in-the-ecosystem"></a>

Users have the option to purchase and trade Delta on Sushiswap or stake Delta to earn yield in the Deep Farming Vault.

#### Trade Delta on Sushiswap <a href="#trade-delta-on-sushiswap" id="trade-delta-on-sushiswap"></a>

* [**Sushiswap pool**](https://app.sushi.com/swap?inputCurrency=0x9ea3b5b4ec044b70375236a281986106457b20ef\&chainId=1)****
* **Delta Token:** 0x9EA3b5b4EC044b70375236A281986106457b20EF

### Delta in the Deep Farming Vault <a href="#delta-in-the-deep-farming-vault" id="delta-in-the-deep-farming-vault"></a>

The vault has different states for Delta, each state affects the token in a unique way.

* Mature Delta
* Immature Delta
* Staked Delta
* Permanently Locked Delta
* Claimable Delta

**Mature Delta:** The wallet section displays the amount of mature Delta in the users wallet. This depends on the vesting schedule and early transfer can result in the loss of immature Delta.

**Immature Delta:** After Delta has been purchased a 14 day vesting schedule is activated. Immature Delta is the amount of tokens which are currently vesting. In case of a premature transfer these tokens will be lost.

**Staked Delta:** The total amount of Delta which is currently staked in the Deep Farming Vault, earning yield from vesting schedule interruptions.

#### **Permanently Locked Delta:** <a href="#permanently-locked-delta" id="permanently-locked-delta"></a>

Delta which is permanently locked in the Deep Farming Vault, will earn yield forever. It is used to maintain Multipliers and increase the overall yield generation while reducing the circulating supply of the token. You can permanently lock Delta in the Deep Farming Vault to maintain your [Booster](../deep-farming-vault.md#booster).

**Claimable Delta:** Delta rewards are displayed as claimable Delta. These rewards can be used to increase/maintain your [Booster](../deep-farming-vault.md#booster) or be withdrawn using a withdrawal contract.

​

#### Staking Delta in the Deep Farming Vault <a href="#staking-delta-in-the-deep-farming-vault" id="staking-delta-in-the-deep-farming-vault"></a>

Users can stake Delta in the Deep Farming Vault to receive yield from Delta vesting schedule interruptions. Staking Delta has additional Multipliers which can be activated by permanently locking Delta in the Deep Farming Vault. Read more about it [here](../guides/staking-delta.md).
