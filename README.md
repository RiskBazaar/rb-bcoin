# rb-bcoin

https://github.com/bcoin-org/bcoin 

"Bcoin is an alternative implementation of the Bitcoin protocol written in node.js by Chris Jeffrey, Fedor Indutny. RiskBazaar is building on Bcoin but as of today is not contributing to Bcoin and all credit for Bcoin must go to Chris Jeffrey, Fedor Indutny"

## Intro resources

https://letstalkbitcoin.com/blog/post/lets-talk-bitcoin-319-barnacles-of-consensus

https://medium.com/purse-essays/introducing-bcoin-fdfcb22dfa34

## Uses

- Full Node
- SPV Node
- Wallet Backend (bip44 derivation)
- Mining Backend (getblocktemplate support) - not currently used by RiskBazaar
- Layer 2 Backend (lightning) - not currently used by RiskBazaar
- General Purpose Bitcoin Library - not currently used by RiskBazaar

## Set up instructions

```
$ git clone git://github.com/bcoin-org/bcoin.git
$ cd bcoin
$ npm install
$ bcoin
```

Bcoin is licensed under the MIT License.

