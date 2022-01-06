# Tournament Pool created on top of aave

Any user can create a tournament pool, by investing zero or more ETH and asking participants to depost the fees in the same pool.

1. Create .env file in the root directory and use the exports from sample.env.txt. Make sure to change the variables as needed. Most of them are self explainatory.

2. Run the script to deploy the factory contract to the kovan network. Make sure the account has sufficient ETH in it.

```
brownie run scripts/deploy.py --network kovan
```

Todo: Create a system of withdrawal where all the participants of the event are refunded their initial invested amount and the interest owned during the time of the event is credited to the winner of the tournament.
