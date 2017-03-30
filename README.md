# blockchain for adtech

An alternative to the opaque openRTB based programmatic advertising marketplace.

## 1. Background 

The programmatic advertising marketplace is opaque, inefficient, and does not enjoy the trust of the media buyers. Reports show how fraud, ad misplacement and misreporting are widespread issues in the current openRTB based marketplace. Based on very rough modelling, we find that online advertising technology is responsible for a single digit percentile of the global energy footprint. 

Our first contribution in this field will be to clearly outline an alternative model for programmatic advertising, where on a decentralized platfrom transactions are performed without possibility of fraud, misreporting or 3rd-party interference. We present a marketplace where by its very design, all participants embrace 100% transparency.

Our second contribution is to prove that using a pseudo-blockchain based marketplace model, in addition to being authentic, transactions can be performed with a small fraction of the energy that it woudld take to perform the same transactions under typical conditions im the openRTB marketplace.  


## 2. Solution

The solution consist of three primary functions: 

1) facilitate for programmatic advertising transactions (as openRTB now)
2) enrich each transction with meta-data (e.g. "fraud score") 
3) reduce energy overhead of typical blockchain without losing value  

## 3. Marketplace interactions

1) internet users interact with websites 
2) advertising exchanges interact with websites 
3) trading desks interact with ad exchanges
4) media budget holders interact with trading desks

### 3.1 Outline of an ad placement

Note that we've concisedered the DSP and trading desk both under "trading desks". 

- internet user goes to a webpage
- the webpage source code includes ad tags
- the ad tags have the function of connecting the user with exchange 
- once the exchange receives the connection it creates an auction 
- trading desks compete against each other for the bid
- once the exchange knows it sends an ad to be placed on the webpage
- the user sees the ad

### 3.2 Ad placement related moneyflow

- the exchange pays to the publisher 
- the trading desk pays to the exchange
- the media buyer pays to the trading desk 

### 3.3 Ad placement related disclosure

- Is it a human (user-agent, ip address, referrer, network)
- Is the content contextually relevant 
- Is the page appropriate environment for brands
