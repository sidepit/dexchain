# dexchain
dexchain: a bitcoin sidechain decentralized exchange 

### Purpose
* dexchain is for traders to hedge bitcoin/usd by selling short futures contracts 
* dexchain is for speculator to leverage Bitcoin by going long futures contracts 
* dexchain is for market-making bots looking for alpha 
* dexchain is meant to generate *Fair Price Discovery* as a public good, to be used by p2p DEXs like Bisq, or otc desks 

### Why Dexchain 
Since MtGox went down, almost 10 years ago, Bitcoiners have been dreaming of a Decentralized Exchange solution to enable censorship resistant buying and selling of bitcoin without a central authority.   

### What’s wrong with Bisq?
Nothing! In fact, we expect Bisq and other non-custodial or escrow services to be an integral part of the end-to-end solution. However, all these require a price to be agreed on. Today this price comes from looking at centralized exchanges such as Coinbase. Dexchain fixes this, by providing decentralized price discovery. 

### How is DexChain different 
Previous attempts at Bitcoin DEXs concentrated solely on the non-custodial aspect of exchange. Atomic swaps for example, are perfect for this. However, in order to achieve a free market price in real time, limit order books and matching engines with finality are required. 

* Dexchain is different by focusing solely on the **Price Discovery** aspect of exchange. With focus on price discovery, everything else takes a back seat. 
* Dexchain is not focused on non-custodial p2p atomic swaps. 
* Dexchain is focused on the price for those non-custodial p2p atomic swaps.  

### Main hurdles 
* peg-in / peg-out - ability to go from Bitcoin to Dexchain and back again, solved with *Bitcoin Peg Trust Module*
* MEV / front-running of on-chain Limit Order Books - solved with *Sidepit* and *Pay to Front-run* 
* Anchoring on-chain Bitcoin/USd futures price to reality on the ground - solved with `Probabilistic Altruistic Delivery` 
* KYC / AML / MTL / Legalities associated with *final mile" p2p USD cash to bitcoin - solved with `The Dex Experiment`

### Components 
* Bitcoin Peg Trust Module 
* Distributed limit order book 
* Front-running resistance via *Pay to Front-run* 
* Peer to Peer Delivery via *The Dex Experiment* 

## The Dex Experiment 
Testing the hypothesis that Dexchain can deliver true end-to-end price discovery on Bitcoin/USD trading pairs, without a price oracle. 

### What is it? 
Experiment will be a controlled ~6 month first run of the Dexchain proof-of-concept. 

1. Dex-In - moving Bitcoin to Dex sidechain 
2. Trading DEX-Bitcoin/USD Futures contracts 
3. Clearing profits-and-losses into Dex-Accounts 
4. Settling PNL into Bitcoin 
5. Delivery of Bitcoin for USD 

### Purpose 
Running it as an experipent, enables scientific gathering of data without the regulator hurdles of full blown public service. Just like controlled experients on illegal drugs, to test the possible medical benefits, without the hurdles of the war on drugs, The Dex Experiment will test the public benefits of dentralized Exchange without the hurdles of Legal tender, KYC, AML, Securities laws. 

Main pupose of The Dex Experiment is to enable and test the *Probabilistic Altruistic Delivery* hypothesis 

## Probabilistic Altruistic Delivery
A decentralized on-chain system cannot force actual USD to be delivered for Bitcoin and visa-versa. Other exchanges, such as the CME, use what is called `Cash Delivery`. Cash delivery requires an external price of Bitcoin/USD to peg the final settlement price of each futures contract. 

### The Delivery Problem 
Dexchain cant claim to be *generating* price discovery, if it replies on external price with cash delivery. 
Dexchain cant claim to be a DEX if it requires a centralized custidian to *force* delivery. 

### What about atomic swaps? 
Atomic swaps solve for non-custodial by not having a *forced" matching engine. One side, can always back out, even after a price is negotiated. 
Forced matching is a basic requiment of price discovery and on-chain limit order book matching enegines. 

### Forced matching with price discovery vs non-custodial 
Dexchain choses forced matching for price discovery, but is still able to achive almost full non-custodial trading by staying `on-chain`. 

### The Final Mile Trust via Altruistic Delivery 
* Bitcoiners may choiose to volenteer to deliver on their futures contract positions by either delivering USD for short positions or Bitcoin for long positions. 
* This requires longs and shorts to match and agree to deliver. 
* This now becomes the things we have been doing for years, a simple p2p swap of bitcoin for USD, like bitcoin-otc, or localbitcoin or bisq, etc.. 
* However, on-chain attestation of such a delivery is not possible, and it requires the assumtion of *altruistic delivery* 

The probability that going long or short bitcoin/USD futures will enable you to ultimatley deliver is what ultimatley ensures a price-peg to the reality of the $BCTUSD price. 

## Bitcoin Notaries - delivery of last resort 
* Thousands of local non technical plebs, bitcoiners, and common people are eager to get educated on bitcoin, earn some Sats, and be part of this revolution 
* Ultimatly swaping of Bitcoin for USD is an in-person face to face interaction, which requires longs and shorts seeking delivery to pysically be in the same region 

We propose a simple on-chain attestation of delivery process though social trust of so called `Bitcoin Notaries`
1. Notaries will be a decentralized self governing group of regional individuals
2. Altruistic Longs and Shorts may choose a Notery to facilitate low value ($100) final mile delivery 

### The barista comparitive 
When purchasing coffee with Lighning bitcoin at point-of-sale, one would pay with LN, and then trust that the barista will in-fact deliver on her promise of delivering the Coffee. So to with Notaries, you pay the notary USD and trust that she will deliver the bitcoin and visa-versa. 

*Atomic swap of Bitcoin to USD is just as inpossible as an Atomic swap of Bitcoin for coffee. Final mile trust required.*  

### Rational Design and Game Theory 
* A notery that goes through the self-identification process as Bitcoin Notery by going through special education programs with detailed techniques and specialed portable full-node hardware and software, is in it for the Sats as well as altruistaltic in completing the process that 














