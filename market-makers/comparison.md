---
author: richardred
published_utc: 2019-08-30
---

This file provides a comparison between the competing market maker proposals, in a table of cost estimates followed by a more detailed breakdown of how the estimates were produced.

|                            | Tantra Labs                 | i2 Trading                  | Grapefruit            |
| -------------------------- | --------------------------- | --------------------------- | --------------------- |
| Liquidity (each side)      | $30k                        | $50k                        | $30k                  |
| Pairs                      | 6                           | 6                           | 4                     |
| Total liquidity (e/s)      | $180k                       | $300k                       | $120k                 |
| Spread                     | $30k Layered +/-3%          | $10k/1.5%,$30k/2%,$50k/4%   | $30k 2% (flexible)    |
| Uptime                     | 90%                         | 90%                         | 80%                   |
| Fees                       | $0k/m                       | $35k/m                      | $28k/m                |
| Inventory                  | 30k DCR                     | 30k DCR                     | 12k DCR               |
| Interest (6 months)        | $40.5k                      | $49k                        | $17k                  |
| Trading fees               | Treasury (max $10k/month)   | Treasury (max $10k/month)   | Included in price     |
| Max 6 month cost           | $100.5k                     | $319k                       | $185k                 |
| Max Monthly cost           | $17k                        | $53k                        | $31k                  |
| $ of liquidity per $ spent | $1.80 (at max trading fees) | $0.94 (at max trading fees) | $0.65 (includes fees) |
| Max setup time			 | 90 days					   | 60 days                     | 60 days               |

## Market Maker proposal cost estimates

Estimated costs are based on $30/DCR. I don't know what a good estimate of trading fees would be, but they would also be billed to the Treasury by i2 and Altonomy, the i2 proposal caps this at $20k/month but does not expect to reach that limit.

### Tantra Labs

- No trading fees, making this the cheapest offer by some distance, but calling into question whether the plan is realistic.

**Offer:**

- 0.3% BTC spread, 0.5% USD spread
- Layered offers of $30k each side up to 3% from current price
- 6 pairs
- 90% uptime

**Cost:**

No fee for the service.

**Loans:**

5k DCR/pair - 30k DCR for 6 pairs = 900k USD, at annual interest of 9% this is ~$6,750 month

**Trading fees:**

Up to $10k/month charged to Treasury

Total indicative cost for 6 months (including max 10k/month trading fees): **$100,500**

### i2 Trading

- Highest liquidity close to trading price

**Offer:**

- 0.5% BTC spread, 0.75% USD spread
- Layered depth, $10k/1.5%, $30k/2%, $50k/4%
- 6 pairs
- 90% uptime

**Cost:**

USD 35k/month = $210k for 6 months

**Loans:**

$8,200 per month (".213 BTC, 150 DCR, and 1600 USDT")

**Trading fees:**

Up to $10k/month charged to Treasury

Total indicative cost for 6 months (including max 10k/month trading fees): **$319,000**

### Grapefruit Trading

- Only proposal which does not require reimbursement of trading fees.

**Offer:**

- 4% bid to ask spread, which is equivalent to the 2% spread level (from current price) as the other proposals quote it.
- $30k each side
- 4 pairs
- 80% uptime

**Cost:**

$28k/month = $168k for 6 months

**Loans:**

$90k/pair = 12k DCR or $360k, assume monthly interest of 0.8% = $17k for 6 months

Total indicative cost for 6 months (including trading fees) : **$185,000**

## Updates

- 2019-08-30: Added Tantra offer and updated i2 offer. Altonomy withdrew their offer.
- 2019-08-11: Grapefruit's offer is framed differently (in terms of "bid to ask") to the others (in terms of the spread from mid) - so 2% bid to ask is largely equivalent to 1% spread, except that the offer could be asymetrical around the price. This [comment](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/5) explains it.
- 2019-08-09: Grapefruit have confirmed that the only loan they require is the DCR one. Added note about no layering on Grapefruit offer.
- 2019-08-09: i2 have clarified that the loan figure in their proposal covers all required loans, so that is cut in half. I am also now assuming that as Grapefruit does not mention a loan other than the DCR one that this covers their inventory requirements. Grapefruit have clarified that they would not charge trading fees to the Treasury, which sets their proposal apart from the other two because there is no additional unknown charge for trading fees to consider.
