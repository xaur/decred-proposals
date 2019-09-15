---
author: bee
published_utc: 2019-08-22
updated_utc: 2019-09-15
---

This is a compilation of arguments, concerns and questions about market making proposals.

* pros and cons: not too controversial arguments in favor and against the idea
* concerns: uncertainties and issues where opinions have diverged
* Q & A: answers to common questions, often from proposal owners

## Pros

### Pro: Strengthen SoV and MoE properties

Better liquidity helps Decred's [positioning](https://github.com/decredcommunity/pr/blob/release/foundational-messaging.md) as store of value and medium of exchange.

> Liquidity is a pressing issue and it's a lacuna in DCR's proposition as a SoV. There's no SoV without liquidity. If I told you: you can keep gold in my vault, but you'll need to pay me 15-20% if you want it out quickly... Would you store the gold in my vault? It's really simple to explain this value proposition. (@Praxis on [2019-08-08](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156529052611305mfsjk:decred.org))

> A coin targeting the store of value (SoV) market needs to reduce entry and exit friction as much as possible in order to build market confidence. Likewise, greater market stability will be conducive to more broad usage of DCR as a medium of exchange (MoE). (@jz on [2019-08-10](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd))

> Another driving factor in our pursuit was the fact that an asset positioned to capture the SoV market needs liquidity. If an asset isn't investable, I.e. liquid enough for investors to move in/out of, it can't compete with other SoV contenders in the market. If you look back at Chris Burniske's work on the institutional investors case for BTC, he notes that inevitability is one of the hall marks of any asset, and as such, we must prioritize DCR's liquidity if we expect it to be an SoV. This issue is particularly exacerbated by the fact the DCR has such a high stake rate. (@max\_bronstein on [2019-08-12](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/29))

### Pro: Better experience for people selling and buying for DCR

A more practical example of MoE use case:

> Imagine you want to sell me your used car for $5k and I offer to pay you in DCR. If I pay you with DCR using the last print as the price and your immediately selling that DCR would result in you receiving $4.5k that would not be a great offer. Having a MM there to absorb your sell order very close to the last trade price significantly enhances the user experience, and you get your $5k. (@jz on [2019-08-10](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd))

### Pro: Better liquidity for contractors

Special case of the above, but is worth an explicit mention.

> I sell decred every month to pay my bills and can attest to the fact that you'll see slippage of between 1-5%, even with just a few thousand dollars (@lukebp on [2019-08-07](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156521486110122VVuTY:decred.org))

### Pro: Attract more investors

> In traditional markets, investors / traders generally favor assets with good liquidity. Assets that have poor liquidity are discounted due to iliquidity. (@enchanted\_broccoli on [2019-08-07](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156519089713141yprlR:matrix.org))

> It reduces the barriers for opening and closing decred positions. Nobody wants to sit on Binance for hours sniping bids just to buy $10k of dcr. This inconvience is enough to discourage people from buying and holding dcr. (@lukebp on [2019-08-08](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156528505111123gtEUw:decred.org))

> jz: Think of it this way; a MM is going to do for the price chart of Decred what the new sdiff algo did for the ticket price chart. It won't suspend market forces, it will smooth them and improve UX.  
> jz: Oscillation scares people.  
> checkmatey_: it comes down to confidence. How confident can you be that at any time when you need to get on/off, you wont get burned by slippage  
> jz: Exactly. All money is about _confidence_. (chat on [2019-08-10](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156545679913393mNRKs:decred.org))

> The need for an MM quickly arose as I began speaking with a number of institutional investors here in Silicon Valley. While Decred isn't yet a household name, most researchers who spent time looking into the project were quite intrigued and were quickly interested in becoming stakeholders. Time and time again, I heard issues around DCR's liquidity. The inability to acquire a large position wasn't the main deterrent, but rather the inability to get out of a position once acquired as well as what illiquidity said about market sentiment. Investors know many times markets are forced to contract, and when they do, the most illiquid assets behave poorly. Not because of fundamentals, but purely because the market can't absorb the selling pressure. Similarly, investors have to weigh current liquidity in their research as a measure of sentiment and demand. (@max\_bronstein on [2019-08-12](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/29))

> With the increased liquidity and volumes, the asset will become available to a new class of investors, particularly institutional investors with strict liquidity requirements in their holdings. Where today, even if these investors had an interest in Decred, would be barred or limited in the size of holding due to the lack of liquidity available today. (@jyashouafar on [2019-08-13](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/36))

> while active the MM will make for a more orderly market and encourage people who would have otherwise not taken a DCR position to feel comfortable dipping their toes in the water.  
> ...  
> Part of the problem is nobody want to be the person that makes the price rise sharply. A MM helps to smooth this process. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/64))

### Pro: Facilitate new listings and make Decred more visible

> With higher volume numbers, more people will see DCR and some exchanges might consider listing DCR on their platform. (@grapefruittrading on [2019-08-09](https://www.reddit.com/r/decred/comments/cnmc0o/market_making_proposal_grapefruit_trading/ewffhwv/))

> One of the first questions I'm usually asked when negotiating exchange listings is "do you have a market maker?", followed by "will you hire one?", exchanges don't like listing assets that have no pulse. (@jz on [2019-08-14](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156574882117342AbrKV:decred.org))

### Pro: Protect from delistings

Some exchanges [delist](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156580825517926esBUo:decred.org) assets that don't have X volume in Y time. In case MM happens to increase trading volume, it will be an extra protection from delisting.

### Pro: Stabilize the market

Stabilize here means smoothen the price swings, not control (pump or suppress) the price.

> Not matter how much DCR price has changed, we will always be there (as we signed the contract). We can be the last guy you can find in the market to trade with. We provide liquidity and provide our protect to stabilize the market (@runchen of Altonomy on [2019-08-08](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/14))

### Pro: Experiment to try

There have been debates about how much poor liquidity is responsible for Decred's low rank and slow adoption. Getting a trial of good liquidity may answer this question. If we buy good liquidity and nothing changes, the problem was elsewhere. If so, we can not renew the contract.

Counterarguments:

> people are saying "it is an experiment", but the proposals are not set-up with the scope, timeline, or cost structure of an experiment (@betterfuture on [2019-08-11](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/19))

See also [Can we start small...?](#can-we-start-small-and-ramp-up-the-expense-later) about scaling down cost.

### Pro: Industry first transparency

> I'm particularly excited about how we're going to take what's usually a process conducted behind smoke filled rooms, and opening it up to a transparent manner that's decided by stakeholders (@max\_bronstein on [2019-08-02](https://matrix.to/#/!MgQoetFiyjrHAywokv:decred.org/$15647801425402KFLJg:decred.org))

## Cons

### Con: It is expensive

MM cost [varies](https://github.com/RichardRed0x/politeia-digest/blob/master/issue-020.md) between $31-47K per month, or $185-283K for 6 months.

> Not counting the loaned collateral, these proposals tend to have an average monthly cost of roughly 10% of the current treasury inflow. If DCR prices were to dip back down to price levels seen earlier this year, that could quickly become 20% of the current treasury inflow. (@solar on [2019-08-11](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/16))

> I do not still understand why the urgent need to make market at such high cost to long term health of treasury while not even being sure if it will work. also either we are going to do this only for 6 months and hope that other will pick up the tab from there, which they are welcome to do right now or we will keep doing this forever at $600k/year, which is insane. (@sambiohazard on [2019-08-20](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15663149652129YIrJZ:decred.org))

### Con: No guarantees, it may not work

> it's a spaghetti launch - it's not at all clear it will have a positive effect, but you can't know until you do it (@jy-p on [2019-08-15](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156589816719413SfIct:decred.org))

### Con: Coins should not pay for MM

In traditional markets the common practice is for _exchanges_ to pay for MM because exchanges are best positioned to audit MM's results.

> If all top coins in cryptospace hiring them doesnt mean its the right way to go. Communities of those coins never being asked what ppl think about hiring them. (@rickshaw on [2019-08-15](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/41))

Counterarguments and comments:

> MM is so common in the equity market, even Apple and Google have their market makers providing liquidity to their stakeholders. (@runchen of Altonomy on [2019-08-09](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/18))

> In almost all cases BTC and other large cap coins have had market making. In some cases it was funded by the foundation and in others it was funded by the exchange. We have seen it both ways. (@grapefruittrading on [2019-08-09](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$1565377390653439tTuzU:matrix.org))

> \[Exchanges should\] but the reality is exchanges have the power and don't care about low volume coins. I suspect every coin in the top 20 by market cap has MMs operating. (@jz on [2019-08-19](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/66))

> > Is there a known story where a coin got a significantly long-term benefit from hiring an MM?
> 
> Most coins would not ever admit to engaging a MM. We have very little data for comps. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/64))

A related idea is that even if the coin pays, it [should not](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15662825861717XfvmO:decred.org) come from its treasury but instead should be funded by large holders or miners.

Counterarguments:

* Decred doesn't have a large central entity "holder" with ICO money or huge premine that it can throw at MMs. At the same time, honest responsible holders and miners do not always self-organize and act quickly. (@bee on [2019-08-20](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15663050871865zIJqn:decred.org))

## Concerns

### Concern: MM liquidity is not organic

Summary: there are two things that can be inorganic - liquidity and volume. Some people mix up the two. Most agree that inorganic/faked volume is bad. Opinions vary whether liquidity provided by MM is organic or not.

For reference, liquidity is simply open orders while volume is born when those orders are consumed and the trade is executed.

> it is creating inorganic liquidity, which is not created by any new users, holders, or stakers. I, personally, would like to see a more "grassroots" approach to liquidity, allowing it to organically increase as more and more people learn about the incredible value inherent in Decred's design. (@fort3hlulz on [2019-08-08](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/10))

Counterarguments:

> We frequently provide OTC quotes in DCR. Our proposal would bring some of this liquidity to exchanges. It's by no means inorganic! DCR has had years to develop liquidity naturally, and currently on-exchange liquidity is low. For that reason, we were asked to develop a plan for increasing it. (@grapefruittrading on [2019-08-08](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/14))

> DCR liqiudity from a proper market maker is as "inorganic" as liquidity in a currency exchange office. Without it, you need to wait and/or actively find people willing to exchange your USD for EUR. Exchange office maintains buffers of both currencies and allows you to instantly convert from one to another. Market makers place new buy and sell orders but do not consume existing orders. They "make" orders, not "take". (@bee on [2019-08-18](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/31))

> degeri: If we go the MM route we might never grow an "organic" liquid market.  
> jz: Bad news; it's never going to happen by itself, we're 3 years in and one of the least liquid coins. Not great for SoV or MoE.  
> jy-p: it's not inorganic, it's standing limit orders that can be matched against by ppl entering and exiting a position. if they were matching against their own orders (wash trading), that would certainly be inorganic, but that is not what is under discussion (chat on [2019-08-09](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156537647112429goDVY:decred.org))

### Concern: Unethical practices

The concern is that market makers engage in unethical activities like wash trading to fake the volume, spoofing (quick placement and removal of orders), pump and dump, etc.

Counterarguments:

> I totally understand there is natural apprehension to market makers, especially in crypto given some of their previous practices, but I want to assure you we only engaged top tier firms with strong track records and a lot of skin in the game. (@max\_bronstein on [2019-08-02](https://matrix.to/#/!MgQoetFiyjrHAywokv:decred.org/$15647802945405aYWkA:decred.org))

See also: [What are success metrics?](#what-are-success-metrics)

### Concern: Paid MM may attract attention of regulators

... or even increase the security-ness of DCR

Counterarguments:

> every major crypto project engages MMs and we've never seen it called out as an issue (@jz on [2019-08-11](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/14))

> in traditional market, providing liquidity at the early stage of a financial product, even at cost, is a common practice to incentivize trading and further liquidity. This is often done by the exchange itself. (@runchen of Altonomy on [2019-08-14](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/35))

> Those concerns do not apply to non-securities. Decred is not likely to ever be considered a security. (@jz on [2019-08-19](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/66))

Discussions:

* [2019-08-05](https://www.reddit.com/r/decred/comments/cm2uw1/decred_only_needs_one_market_maker/ew1jp6y/): subsidizing MM action will lower Decred's "regulatory compliance score", on the other hand SEC has bigger fish to fry atm and by the time they get to Decred the Treasury may be (more) decentralized
* [2019-08-09](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/25): this concern only applies to securities and there are no clear regulatory guidelines
* [2019-08-10](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/5): MMs will only provide maker liquidity; whether DCR is a security

For an index of "regulatory uncertainty" discussions see [this issue](https://github.com/decredcommunity/issues/issues/133).

### Concern: Why MMs can't prove their value upfront, like everybody else?

> Why can't MMs come to the table with the same 'fight club' mentality that characterizes the rest of the Decred contractor community and prove they can add value before asking for professional comp levels? (@betterfuture on [2019-08-11](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/19))

### Concern: MM may crash the price

@emiliomann [noticed](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156537421912308BkveG:decred.org) that the day when i2 Trading [has begun](https://twitter.com/RudyBouwman/status/1105945015333933057) OTC trading of DGB (Mar 13, 2019) was also the first day of a large prolonged sell-off. During ~1 month prior to that the price has rallied from ~260 to ~360 satoshis, but after the peak (coincided with the announcement) it reversed into a multi-month slide down to ~90 sat as of Aug 21. It must be noted that many altcoins experienced a downtrend against BTC during the same period, and that in terms of USD the dynamic looks less dramatic.

> I suppose the bet being made here for the average DCR holder is whether the current illiquidity is preventing more potential buyers from entering the market or preventing more potential sellers from exiting. (@scooter\_d on [2019-08-10](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$1565456063985982kjCCC:matrix.org))

### Concern: This will only benefit the whales

This also covers a common question: "Why not just use OTC?"

> Spending a huge amount of treasury funds to enable whales to more easily enter (and, importantly, exit) their positions... it almost feels reminiscent of the nation state. Spending big reserves of cash, which should be used for the good of the project, on a service which will only impact the wealthy minority and will have no/minimal benefit for the poor masses. and attempts to justify this by claiming [trickle-down economics](https://en.wikipedia.org/wiki/Trickle-down_economics) will end up benefitting the poor indirectly... just makes it feel even more nation state-y (@jholdstock on [2019-08-10](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156542928313028fOfKB:decred.org))

Counterarguments:

> A MM doesn't magically create an exit for whales, if we don't grow volume/mkt cap in addition to fixing liquidity whales are never getting off their positions if that's their intent. (@jz on [2019-08-10](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156545668913387IQHzZ:decred.org))

> it's incorrect to characterize this as "subsidizing whales". We're talking about an amount of depth that would amount to a rounding error for a large player were they to accumulate a DCR position. This will really have more impact for small traders and those wishing to use DCR in transactions. For bigger players that build positions over time it will help to smooth the oscillations that we often see in the market. (@jz on [2019-08-11](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/17))

> > Though I am concerned about the price, I would argue that this does not only target whales. Whales will blow through the MM walls; while small holders will be able to benefit from them completely and avoid slippage. (ryanzim)
> 
> you are right on this one. Large trades happen OTC, which we do RFQ with institutional investors. MM is more tailored to benefit retail investors. (@runchen of Altonomy on [2019-08-14](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/34))

> > If we are talking about institutional players, why not provide this liquidity via OTC instead? I guess OTCs have less custody risk than retail exchanges? Do institutional investors use retail exchanges at all?
> 
> DCR is actually well traded OTC but MM would have less impact there, large players transact in size and the types of support we're talking about would be a rounding error on a typical OTC trade. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/64))

> > Isn't it good that the big boys are not entering? Isn't it better to have DCR distributed across lots and lots of small fish?
> 
> Amusingly enough the groups that have been most vocal about engaging a MM are larger players who are mostly done buying and want the market to be less scary for small players to enter and exit. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/64))

### Concern: This will onboard wrong people

The [concern](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/73) is that if an investor has studied Decred but got turned away by poor liquidity, he doesn't care much about Decred's mission and values and will likely be a bad stakeholder.

Counterarguments:

* Better liquidity [helps all](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/82), not just speculators.
* Side note: comforting those who have liquidity as top priority is a bad selling point for MM.

> jz: If you were just judging which coins you should take a close look at based on market dynamics, you'd pretty much never end up taking the DCR dive. ([2019-08-26](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15668513928511oqPAT:decred.org))  
> raedah: Thicker books definitely give off the appearance of stronger activity, similar to market cap.  
> bee: people judging coins based on market dynamics - why burn money for them?  
> raedah: As I see it, liquidity begets liquidity refers to the psychological and confidence aspect of the market. I agree with you that it doesn't equal a fundamentally different result for coin acquisition, but being that markets themselves are psychologically driven, we cant ignore the mass perception which clearly does drive the market. Most outside investors will have a much smaller number of data points to go on when they decide to take their first dip into dcr, compared to the amount of data points decred old timers have. Bull markets themselves are the result of this psychology. Holders getting involved with decred based on strong market dynamics will beget more holders researching decred as well, creating a virtuous circle. ([2019-08-27](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156693328510476ySLDu:decred.org))  
> max\_bronstein: Think about all of the knowledge we had to acquire before truly understanding why Decred is such a unique project and why DCR stands a chance to become a globally-scaled, non sovereign SoV. Having a healthier market just reduces that barrier to entry.

## Q & A

### Why does it cost so much?

Onboarding fee:

> setting up market making strategy is far from an easy task. Since DCR has been trading across various exchanges and we have to set different accounts and handle various exchange exceptions. There are tons of different exceptions you may encounter if you are familiar with these exhcanges. It is quite a burden for our team to have everything running smoothly 24/7, and that's why we charge onboarding fee. (@runchen of Altonomy on [2019-08-09](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/19))

Monthly fee:

> The expensive part is the fact that you are potentially incurring small losses and exchange fees. The bids/asks are all spread out in an automated manner. (@jz on [2019-08-19](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/66))

### Does MM make profit?

> If it were profitable someone would _already_ be doing it. (@jz on [2019-08-06](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15651272678513OeVzY:decred.org))

> The DCR market is so illiquid and trades so little that making markets for it, and providing the kind of depth that we are offering will most likely result in trading losses. (@i2trading on [2019-08-07](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15651885699101HYJcG:decred.org))

> Intuitively, we can make profits with our market making strategies by buying low from one client and selling high to another client because our high frequency strategy can make decisions within milliseconds, much faster than normal people especially when market moves a lot. However, the profit we gain is generated from the market, which means, we take profits from you, from the Decred community. The more profits we gain, the more money you guys lose. (@runchen of Altonomy on [2019-08-08](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/7))

> > In case the MM manages to make profit during his activity, will it go back to Treasury or make a discount for the next month?
> 
> Great question, we can negotiate this but since I'm not willing to share in potential losses they may incur it's probably not acceptable for them to share profit. They will not be making a market with the intention of having net profits though. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/63))

### Can we start small and ramp up the expense later?

> Since we have no start up costs, we are trying to have a fixed monthly cost. For us reducing the number of pairs will of course reduce the amount of monitoring, complexity, and risk for us. But it will also reduce the amount of liquidity in the market. Costs per month would go down from an interest perspective if you reduced the pairs. As a DCR stakeholder ourselves, we were extremely thoughtful about how many pairs to provide and on which exchanges.  Our goal is the same as yours.  The currenty liquidity issue is unnerving.  Reducing the number of crosses could result in a slightly lower price, but it wouldn't really be worth it. (@i2trading on [2019-08-08](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156527367010708ernvV:decred.org))

> Yes but we need to balance that with something that can actually be effective and is worth doing for the service provider. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/65))

### How MM handles large market buys and sells?

> I think of a trade that is over $1m, our bots would absolutely improve liquidity for the trader. Depending on how much more trading happens on exchange once the program begins, its possible that the trader would be able to comfortably execute this order entirely on exchange. I would however recommend that a trade of that size be executed OTC for the best overall experience. Our desk is willing to inventory risk of that size, and therefore the trader would end up with a very good price and less market risk. We have routinely done trades of this size, and our clients were happy with the outcome. (@i2trading on [2019-08-08](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/14))

> While none of the current proposals would allow someone to enter/exit positions of greater than $1M USD in one click, it would still greatly help the situation. Generally when large players want to put on a position, they use advanced execution algorithms. Even in the most liquid of assets (think Apple stock), positions are not generally entered/exited in one fell swoop. The most basic of these are TWAP (Time Weighted Average Price) and VWAP (Volume weighted average price). Most hedge funds have a team of PhDs working solely on reducing slippage. By increasing the liquidity available, these algorithms will be able to perform significantly better to reduce slippage form a target price which could be nough to sway a potential investor. (@grapefruittrading on [2019-08-08](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/6))

### How MM handles big market movements?

> richardred: I was wondering about the significance of the uptime too, seems like a big difference between 100% and 90% if it means MM will be sitting out 10% of the time when things get rough.  
> jy-p: it strikes me as giving them leeway to turn off their bots when the market gets really directional, to be sure they don't get run over  
> max\_bronstein: this is precisely correct. and it's better for the project. If an MM is caught offsides, they end up holding a bunch of excess inventory which they will try and sell off most likely  
> jy-p: yep. they're not there to stabilize or otherwise control the market so much as add depth so ppl can get on and off the dcr ride (chat on [2019-08-09](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156538185512711OSiGO:decred.org))

> MMs will need to manage risk in a way that protects them from major price swings.
> 
> > How MMs handle bull runs? Bear runs? e.g. if their DCR sell side is fully bought out and the price never falls back (it will mean a ton of DCR was sold cheaply). Conversely, if the BTC buy side is fully sold into and the price crashes without recovery.
> 
> They need to buy it back and it would come out of the fees they're charging us if they get put in this position. Essentially they could lose money doing their job. (@jz on [2019-08-19](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/66))

### Can MM run out of inventory?

> not likely, the Market making strategy will rebalance itself. \[in the case of an extreme movement in price\] yes possible but as long as there are price takers on the opposite direction and within our risk level, we can balance it back. So far we have not run into any issues like this. Our stress tested model also justifies this. (@runchen of Altonomy on [2019-08-14](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/32))

> This is not a concern - we manage inventory by consistently rebalancing when we become overly weighted one way from the price moving one direction. The community should not have to worry about this issue. (@i2trading on [2019-08-13](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/48))

> If our offers on every exchange are swept, we would buy that quantity of DCR back elsewhere from other market participants. While we may run out of DCR inventory temporarily, we would quickly replenish our DCR supply so that we may fulfill our quoting obligations. We may temporarily run out of DCR during a big price move or if another market participant aggressively lifted our DCR offers. Aside from that, we don't foresee any scenario in which we would temporarily lack DCR inventory. We will adjust our markets according to our position. If we have no net DCR position, we would likely make our market symmetric around what we deem to be the fair DCR value. If we are short DCR from other trading activity, perhaps we would adjust our quotes so that our bid is closer to spot than our offer, to encourage other market participants to sell us DCR. Ultimately we alone bear the risk of losing money from adverse price movements. (@grapefruittrading on [2019-08-20](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/35))

### How losses from exceptional events are handled?

> * Trading losses to be borne by i2 Trading.
> * Exchange hacks/external operational losses borne by lender. (@i2trading on [2019-08-07](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9))

> Grapefruit Trading has no liability on any amount of loaned DCR that is lost in the event that the above exchanges loses or absconds with them (hack, exit scam, etc). (@grapefruittrading on [2019-08-07](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b))

> The lender bears the risk for the coins lent and the MM bears it for price moves. (@jz on [2019-08-19](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/66))

### Why these markets were chosen, can we control them?

> The pairs we plan to provide liquidity for will be Binance DCR/BTC, Bittrex DCR/USDT, Bittrex DCR/BTC, OkCoin DCR/USD, though these pairs can be changed should the relevant Decred parties deem it in the network's best interest (e.g., a new exchange listing). (@grapefruittrading on [2019-08-07](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b))

> We specifically chose these pairs to round out the liquidity globally. Trading begets more trading. Ultimately, if there are deep books everywhere retail DCR participants will benefit the most. That being said, if there is overwhelming support for fewer pairs, we are open to it. (@i2trading on [2019-08-08](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/12))

> The crosses/exchanges that have been selected have been chosen for strategic reasons. (...) We also need flexibility so if we get any major listings during the 6 month engagement we can switch to operating where we feel it would have the greatest impact. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/63))

### What are success metrics?

> All of the proposals have KPIs attached to them, this is how the community will judge their performance. Commons KPIs include:
> 
> 1. $ amount needed to clear X% on either bid/ask. What this means is that an investor could lets say purchase/sell $30,000 USD without moving the price up or down
> 2. % spread between the first bid/asks, meaning first buy order and first sell order on the books
> 3. % uptime of market making software, essentially, how often is the system actually on the books
> 
> In the case that the community wants to add certain KPIs, that can be done before these proposals go live and after the 6 month term is up. I suspect the value of the MMs will be pretty apparent after the first 6 month term. Theoretically, the holder base should grow *IF* liquidity was a problem as we expected. If holder numbers don't grow, liquidity wasn't the issue.
> 
> Overall, the goal of a market maker is to make it easy for buyers and sellers to transact with little slippage. By no means are they attempting to move the price in one direction, we explicitly only engaged firms with strong reputations and strong past performance. (@max\_bronstein on [2019-08-04](https://matrix.to/#/!MgQoetFiyjrHAywokv:decred.org/$15648896736066fvsxu:decred.org))

> One of the first things we made clear to the team was that we would not be able to guarantee any volume numbers unlike some of our Asian counterparts. We are based in the US and are a wholly owned subsidiary of a traditional finance firm. As such, we do not engage in wash trading or any activities that are frowned upon by the CFTC. We will only guarantee width/size/uptime. (@grapefruittrading on [2019-08-08](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/6))

> Tighter spreads, lower price volatility, and ideally higher volume. I think i2 estimated to hit $20k/mo in exchange fees they would need to be doing $20M of volume. That would be a resounding success in my view. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/65))

> > Will someone try to monitor the trades and analyze if MM was the real problem, and not the general lack of interest and market awareness (as suggested in [this comment](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/20))?
> 
> Proving causality is always hard, I can just imagine price rallying or falling and people assuming MM is amazing or the devil. Metrics for success have to do with spreads, slippage, and total volume traded. (@jz on [2019-08-18](https://proposals.decred.org/proposals/30822c16533890abc6e243eb6d12264b207c3923c14af42cd9b883e71c7003cd/comments/65))

[CoinMarketBook](https://coinmarketbook.cc/) argues "Market cap is a lie. Buy support tells the true story". As of 2019-08-19, DCR is #95 in that rating with only $260K buy support within 10% distance from highest bid price. For context: BTC has $360M, ETH $55M, LTC $23M, XMR $9.5M, DASH $5.7M, DOGE $4.6M.

### What about uptime?

> i2trading: Uptime simply refers to the total amount of time we will be in the market making two sided markets. Exchanges are not always completely functional and so if an exchange goes down we will be unable to vend quotes. Secondly, our systems will require periodic maintenance. During that time we would need the flexibility to turn off quoting. The reason for this could be any of the following: reconcile transactions, rebalance our positions, tweak our algo inputs, troubleshoot errors.  
> jz: people were concerned that you guys would just be turning off the bots regularly when there's volatility.  
> i2trading: Oh yeah, that's not the reason of not being up all the time.  We will strive to be up as close to 100% as possible though. (chat on [2019-08-20](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$15663344732901jyXOe:decred.org))

### How will MM report?

> We will provide reports on the total Decred volume (not just our trading) in all the markets we are participating in. Over time, this should demonstrate the increase in DCR trading, which could be valuable to the community. (@i2trading on [2019-08-08](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/14))

> We will be happy to provide a quarterly reporting statement of all the trades we conducted, and how much liquidity we added to the market. We think this is a good idea. (@i2trading on [2019-08-08](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/10))

> We will provide transparent reporting of how much we have traded along with metrics at the end of each month. (@i2trading on [2019-08-20](https://proposals.decred.org/proposals/2eb7ddb29f151691ba14ac8c54d53f6692c1f5e8fe06244edf7d3c33fb440bd9/comments/52))

> we can provide a monthly report (@grapefruittrading on [2019-08-08](https://proposals.decred.org/proposals/4becbe00bd5ae93312426a8cf5eeef78050f5b8b8430b45f3ea54ca89213f82b/comments/13))

### How can we verify MM's activity?

> We trade through API. The account itself is completely transparent to the team. Team will have login to view everything. We have nothing to hide. (@runchen of Altonomy on [2019-08-14](https://proposals.decred.org/proposals/772d083fef79fa2e443d8424b353deadc3af69c8d8764e473cb200f98f356c60/comments/38))

> user39390: may be a read-only api key access to verify trading activity of MM  
> i2trading: I think we would be open to this as long as it stayed in the hands of a key DCR rep and nobody else. There is risk for us if a bad actor was able to gain access. (chat on [2019-08-08](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156527909310923oaewi:decred.org))

### Why the RFP came after the specific offers?

> jz: Because we didn't think a RFP was necessary (we were wrong).  
> jz: The intent of the RFP actually wasn't to solicit proposals (misnomer I guess) it was to gauge stakeholder buy-in.  
> davecgh: Based on what was said in this channel, there was no intetion of having one originally  
> davecgh: However, due to (the perception of) a lot of negativity, jz decided to put up the RFP to even see if it was worth continuing. (chat on [2019-08-30](https://matrix.to/#/!MIGqWXfLFBwhipPKYL:decred.org/$156718665015196AxXWr:decred.org))
