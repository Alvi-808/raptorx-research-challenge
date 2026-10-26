# External sources (web), and the on-chain facts behind this entry

## JUP burn history
- 3B JUP burn (announced at Catstanbul, January 2025; total supply 10B to ~7B): https://blockworks.com/analytics/jupiter/jupiter-jup-token/jupiter-jup-burned , https://www.tokenpost.com/news/investing/37022 , https://defillama.com/unlocks/jupiter
- Litterbox burn of ~134.5M JUP (2025-11-25): DefiLlama unlocks note (https://defillama.com/unlocks/jupiter); Jupiter docs say the trust has burned ~134M: https://docs.jup.ag/user-docs/more/jup-token/transparency
- Note: our questions avoid the burn month; on-chain total supply 6,861,485,892.58 (verification/jup-supply-rpc.json) is the evidence used.
- Six CARDS Streamflow escrows funded from the vault on 2026-09-28 (Squads VaultTransactionExecute + Streamflow Create), current balances: 96cJVtxcPYeJ5doebfV3RqJMB1xg1d1tRAAiDAsZ2do4 82,656,750; EEaezt3o... / Av47AL9p... / 4xkDss3j... 64,288,583.33 each; 5VFZaWwN... and 7S8Jmd6L... 16,698,335 each (funded 18,368,166.67). Total about 308.9M.

## Jupiter Net-Zero Emissions vote (February 2026)
- https://www.kucoin.com/news/flash/jupiter-votes-to-reduce-jup-net-release-to-zero-jupuary-airdrop-delayed-indefinitely
- https://bitcoinethereumnews.com/finance/jupiter-dao-backs-net-zero-emissions-plan-with-75-vote-postpones-jupuary-and-halts-new-supply/
- https://crypto-economy.com/whale-voting-power-drives-zero-emissions-initiative-to-81-approval-in-jupiter-dao/ (voting weight vs wallet count split)

## Unlock schedules
- CARDS ~59.26M on 2026-10-29: https://tokenomist.ai/collector-crypt/unlock-events , https://www.kucoin.com/news/flash/3-token-unlocks-to-watch-in-final-week-of-october-2026
- KMNO monthly core-contributor tranche ~229,166,667 (next 2026-10-30, amount inferred from schedule): https://app.tokenomics.com/tokenomics/kamino/unlocks , https://tokenomist.ai/kamino/updates

## On-chain facts verified directly (Solana mainnet RPC, 2026-10-26)
- JUP getTokenSupply: 6,861,485,892.582047
- Litterbox (6tZT9AUcQn4iHMH79YZEXSy55kDLQ4VbA3PMtfLVNsFX) JUP: 177,519,690.32
- CARDS mint: mintAuthority null, freezeAuthority null (verification/cards-mint.json)
- CARDS vault token account DgiH81DoENYixj8cKj2u79nJXbve5C1q3z6ZLJrhT9eD, owner 3PnVBrb4wPLFLW38oaYR7dA6HSfKpawxHGESPj5kF1QB: 1,088,261,037.170097 CARDS
- Tx 4apHXwLmStsAPQfvEpJP9XuxVb5BXi931CBW9CE4xr3iF7zYjQDCXhmwRaDKpXd9CHh838311FTuQLLBrV2ZaW3t (2026-10-22 01:14 UTC): Squads VaultTransactionExecute, two Streamflow Cancel, vault +16,698,336.67 CARDS
- Escrows 4xkDss3j27G9JNqDnyhrzFkwfsQHFfi5FC31UfnHxog7, Av47AL9pfDcUN9m4iLfdbeyZWbmhFWHJSPeEse5MzyZz, EEaezt3okKxvrxVNxyhsZyLcYotYokievV6MA2B572ea: 64,288,583.33 CARDS each, self-authority token accounts, first tx 2026-09-28 = Squads VaultTransactionExecute + Streamflow Create
- DefiLlama Jupiter holders revenue (verification/llama-jup-holders-rev.json): 24h 40,113.5; 7d 354,351.63; 30d 2,066,529.68
