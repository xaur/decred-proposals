# Analysis of Decred DEX proposal

Personal collection of pros and cons for the [RFP: Decred Decentralized Exchange Infrastructure
](https://proposals.decred.org/proposals/5431da8ff4eda8cdbf8f4f2e08566ffa573464b97ef6d6bae78e749f27800d3a).

@bee: I tried to give it a fair judgement but not claiming any neutrality. Contributions are welcome: I'll do my best to look from different perspectives and accept any changes I find reasonable.

## Pros

### Pro: Increase personal security and reduce anxiety

Your keys = your Decred.

This contributes to "sleep better at night" factor, also noted in "anxiety reduction theory" by Murad Mahmudov. Usually you have a dilemma: "own your asset" OR "trust your asset to a 3rd party but have it tradeable". Non-custodial exchange allows both to really own an asset and trade to it. Non-custodial exchange is a safer place to host your assets, compared to a traditional exchange. If this fundamental factor is recognized, it can be a driving force for liquidity migration to this DEX.

### Pro: Increase and improve liquidity

> otc trading has been big for dcr since late 2017 / early 2018  
> which is why you don't see a deep order book  
> it's a blessing and a curse: ppl can get filled for big buy and sell orders, but b/c that occurs privately at an otc desk, the public perception is that there is "no volume"  
> if enough ppl participate on a dex, the otc players will be incentivized to participate  
> it's a chicken and egg kind of situation. (@jy-p on [2019-02-05](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$154937274229123DZgcR:decred.org))

> If the MM gets cleaned out by someone else's bots, they have no reason to continue making the market and will quit. If we build a system that uses pseudorandom order matching, this substantially reduces the threat of being gamed by others' bots, which lowers the risks and stresses associated with being a MM. Lowering the barriers to being a MM will lead to a deeper order book and help decentralize our liquidity, versus paying one or a few MMs to perform this task for us. (@jy-p on [2019-02-06](https://proposals.decred.org/proposals/5431da8ff4eda8cdbf8f4f2e08566ffa573464b97ef6d6bae78e749f27800d3a/comments/15))

Besides just increasing liquidity, the DEX also improves the quality of liquidity by virtue of verifiable orders.

> ... a DEX will bring a degree of resilience to the Decred market that can not be replicated even by increasing the volume of DCR traded by one or more orders of magnitude on traditional exchanges.  
> ...  
> Having DCR trade on a decentralized exchange which eliminates counterparty risk from the equation will bring a different type of liquidity and depth to the market that I believe very few coins actually have.  
> ...  
> having the ability to exit a position is even more important than the process by which you acquire it. Any investor worth their salt will want to be able to get an idea of what their position is actually worth. E.g., if you wake up at 3 AM and decide to sell, how much slippage will there be and can the market absorb your size? This is where the order book starts to become important. Even in the case of coins that do very healthy amounts of volume, it is quite evident that a great deal of the bids or asks can disappear at a moments notice when they appear at risk of getting a fill (@jz on [2019-02-18](https://proposals.decred.org/proposals/5431da8ff4eda8cdbf8f4f2e08566ffa573464b97ef6d6bae78e749f27800d3a/comments/47))

See also the overlapping "Increase accessibility".

Counter:

* whales won't leave large amount of liquidity on DEX because staking or locking in LN is more attractive ([chat](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$154937244629117fHAOV:decred.org))
  * but same can be said about traditional exchange, while DEX is safer for whales than regular exchange

### Pro: Increase accessibility

Non-custodial DEX may attract parties who stopped trading and left traditional exchanges due to:

* a wave of mass KYC enforcement, some people are allergic to KYC tentacles
* security concerns, after all the hacks
* privacy concerns, after all the data breaches
* custody concerns, after all the cases of frozen funds and delayed withdrawals/deposits

Additionally, the DEX can serve people whose trading options are very limited, e.g. residents of countries sanctioned by countries that host popular exchanges.

> I am finding it more and more difficult to buy crypto w/o KYC and this has rendered many coins totally illiquid and worthless for me. I think it will be a great way to ensure that decred always remain available to those who need it most, i.e. people in countries that are having hyperinflation or banning things outright. this will give me a chance once again to accumulate more DCR even if the UX is not the best. (@sambiohazard on [2019-02-07](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$1549545680754qobLW:decred.org))

### Pro: Server and client are held accountable

Since client-server messages are signed, it is possible to publicly demonstrate misbehavior by servers and clients. This is an unmatched level of accountability compared to traditional exchanges, where it would be very hard to prove if the server e.g. silently removes (censors) a specific order.

### Pro: Attract talent and demonstrate the ethos of Decred (yet again)

> Projects like these help Decred attract talent. Typically, the people that are the best at what they do aren't driven solely by money. They want to work on interesting projects that they believe in with other talented individuals.  
> Launching a DEX that has no trading fees, no requirement to buy a 3rd party token (including Decred), and that cuts out all middlemen is a clear demonstration of the ethos that Decred was founded on. It helps us get our name out there and attract the type of people that believe in the same mission that we do. (@lukebp on [2018-06-05](https://matrix.to/#/!NKtIRqGOEGaZvSQkKl:decred.org/$152821240516427WYZhh:decred.org))

### Pro: Test collaboration capabilities of the ecosystem

> I think this will be a good test for the ecosystem. To see if we really are capable of banding together and collaborating to create ecosystem tools without a direct financial benefit. (@joshuam on [2018-06-06](https://matrix.to/#/!zxBsqZRxjbQoLqJRwe:decred.org/$152824331216779yTpkq:decred.org))

### Pro: Indirectly increase network security by reducing amount held on exchanges

> Where the dex is most exciting to me (in addition to challenging gatekeepers), is in reducing the threat central exchanges pose on our governance.  
> Fortunately for the most part our stakeholders seem to be wise enough to take responsibility for their on assets. It'd become worrying if we began to see large amounts of DCR begin to pool on an exchange though (@joshuam on [2018-06-06](https://matrix.to/#/!zxBsqZRxjbQoLqJRwe:decred.org/$152824410516780VOPio:decred.org))

> mark: My best guess is that about 38% of all SC is on Bittrex. When I took a most recent snapshot, there were 11 accounts all with almost identical amounts - about 1.22 to 1.23 billion SC - totalling ~13.5 billion SC (out of ~35.3 billion in circulation). The account behavior all looks very similar, they all seem to be online and constantly de-fragging the wallets. I know at least one of them is Bittrex. They look so similar my gut is that they all are. I have pretty mixed feelings about those results.  
> jy-p: this has very little to do with dex, afaict  
> mark: Ah, you were talking about the influence of exchanges in coin communities. The fact that an exchange holds such a high percent I think is one such influence. A functional dex would likely bring that percentage down ([2018-06-01](https://matrix.to/#/!MfifnUCLrfSeRkMDwZ:decred.org/$153045057530145dbOPY:decred.org))

### Pro: Indirectly increase privacy of Decred chain

Exchanges cooperate with blockchain analysis companies. As a worst case I would expect they sell data of their customers and load it into blockchain analysis companies, enriching their datasets.

> I would say that 80 percent of transactions that occur on these cryptocurrency ledgers have a counterparty that is a third party service (Jonathan Levin, Cofounder and COO of Chainalysis in [Unchained 62](https://unchainedpodcast.com/how-chainalysis-helps-solve-crimes-jonathan-levin-tells-all-ep-62/))

Every transaction that involves a centralized entity contributes data points to an overall degradation of privacy of a given blockchain. Don't think they only look at Bitcoin, they track multiple chains now.

If it becomes possible to trade without feeding surveillance, that would be a boost to an overall privacy of the chain.

(triggered by @karamble's [message](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$1549516985493pQmpJ:decred.org))

### Pro: Facilitate transparent cross-coin LN payments

> > Is there a foreseeable role for lightning to play in the decred dex?
> 
> Once the onchain DEX is online and we have a decentralized mechanism for price discovery, this could be fed into the routing decisions of LN nodes in a multi-coin LN, allowing transparent cross-coin payments.
> 
> One hypothetical way to realize this would be to have channels marked as cross-chain with a swap fee expressed as a % from the average price of the last DEX epoch and nodes use this information for routing decisions based on the max fee for a given payment. (@matheusd on [2019-08-08](https://proposals.decred.org/proposals/417607aaedff2942ff3701cdb4eff76637eca4ed7f7ba816e5c0bd2e971602e1/comments/5))

### Pro: This is bold

> Approving this proposal would signal that stakeholders want to see the project making bold moves that advance the whole space. (@richardred in [investinblockchain.com](https://www.investinblockchain.com/is-decred-dcr-building-decentralized-exchange/) article)

## Cons and risks

### Con: Decred should not pay for DEX alone

By definition, DEX means swaps with other coins. Why wouldn't they share the expenses? Another possibly interested set of parties are exchanges.

Verifiable volume and activity is a huge long-term benefit for the credibility of the whole space. Decent actors should be very interested in this.

I suggest to do word spreading and negotiations work first, at least try. It could be a fund where Decred's Treasury is one of many participants with smaller amounts. If successful it can be huge.

> Not a fan of 100% funding by decred. Could we setup a proposal that obligated matching funds up to $2.5 million? Then have a coordinated fundraising effort? Other projects and private parties could contribute to it. (@decoy on [2018-06-05](https://matrix.to/#/!zxBsqZRxjbQoLqJRwe:decred.org/$152824233116773zUiKu:decred.org))

Counter:

* The biggest gain will come from trading with BTC, but BTC is unlikely to cooperate with an altcoin.
* Coordination cost, "too many cooks in the kitchen", can turn out a waste of time and energy. ([politeia](https://proposals.decred.org/proposals/5431da8ff4eda8cdbf8f4f2e08566ffa573464b97ef6d6bae78e749f27800d3a/comments/21))

### Con: Expenses and Treasury

As of Feb 2019, Decred spends around ~$200K/month, DCR/USD is ~$15 and the Treasury is under $10M. If DCR goes to $5 this DEX alone would be a huge burden. I'm not seeing any sign of market recovery and would prepare for the worst.

If more parties joined in the expense this would be less of a problem, or no problem at all.

Counter:

* RFP by itself does not bind to expense. People seem to overlook this important detail. A second vote to approve a specific contractor's proposal will be necessary. It is possible that all such proposals will be voted down and no expense will be made. Therefore it is safe to proceed with the RFP to see what proposals will come, look at their plans, budgets and teams behind them.
* There will be no large upfront payment.
* "Upper end cost of USD 1M was not intended to indicate that would be likely cost of the work, merely that we should not entertain proposals to build it for any amount greater than that." (@jy-p on [politeia](https://proposals.decred.org/proposals/5431da8ff4eda8cdbf8f4f2e08566ffa573464b97ef6d6bae78e749f27800d3a/comments/15))
* Second version of the proposal reduced the upper bound to USD 250,000.

### Con: It may slow down the development

Counter:

> The intent is for an external team to take up the mantle and build it, so it won't have any bearing on the current c0 roadmap. The important thing to keep in mind is that the goal of Decred is to have a bunch of independent teams on working on different things. (@davecgh on [2018-06-06](https://matrix.to/#/!zxBsqZRxjbQoLqJRwe:decred.org/$152824144816749bQKqt:decred.org))

Question is to what extent current developers may be pulled away indirectly, by discussions and reviews.

### Con: It won't directly benefit Decred/stakeholders/Treasury

Noting this argument for completeness as it is often made and it actually spurred this analysis.

Whether the DEX will benefit Decred depends on its adoption, which is an unknown. The risk is certainly present.

Counter (taking the phrase out of context, but it applies to "this DEX is risky" argument):

> if i let ppl fud me into not taking risks, we wouldn't have this wonderful decred (@jy-p on [2019-02-08](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15496067642935kMrXk:decred.org))

## Challenges

### Partial fills

Non trivial to implement, may cause high on-chain fees.

### Incentives to re-launch server to collect fees

> One thing about the signup fee structure; due to its very nature, it doesn't incentivise keeping a server up. i.e. there's actually incentive to start a server, get a bunch of signups, then fold after a year or so, and restart on a different domain, claiming to be a different administrator, and keep running a string of short-lived servers. Every time you restart, you get an income boost vs. a trickle of income from new signups when running a popular server. (@ryanzim on [2018-06-05](https://matrix.to/#/!MgQoetFiyjrHAywokv:decred.org/$152821928616528OdHhk:decred.org))

How about charging good old monthly subscription fees? Sounds simpler than charging different reg fee based on server rating. And the incentive is easier to grasp for server operators.

