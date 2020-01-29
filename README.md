# Stake Capital's Tezos Baker (HotStake) Historical Payout Record

This repository functions as a historical record of all of the payouts made by Stake Capital's Tezos baker (HotStake). Each payout is accompanied by a timestamp, indicating when the payout was completed.

Browse the [`/payouts`](https://github.com/stake-capital/tezos-payouts/tree/master/payouts) directory to see the markdown file for each completed payout. Each markdown file contains a table of all of the addresses paid and each corresponding payment amount (with a reward breakdown for each one).

## Not Revealed Addresses Will Not Get Paid Out

Please ensure that your addresses is properly revealed by following all of the steps in our Tezos staking tutorial. You can check if your addresses is properly revealed by going to the [TzStats explorer](https://tzstats.com/) and searching your address in the search field. If your address is properly revealed you will see the text "Delegator Account" in the upper left corner:

![Delegator Account Example](https://github.com/stake-capital/tezos-payouts/blob/master/delegator-account.png)

If, on the other hand your address is not properly revealed you will see the text "Basic Account" in the upper left:

![Basic Account Example](https://github.com/stake-capital/tezos-payouts/blob/master/basic-account.png)

You can confirm if your address is not properly revealed as it will be listed inside our [`not-revealed-addresses.json`](https://github.com/stake-capital/tezos-payouts/blob/master/not-revealed-addresses.json) file. Addresses listed here are blacklisted from receiving payments. Please ping us on [Telegram](https://t.me/Hot_Stake) if your address is listed and you resolve the problem.
