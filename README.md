# Cryptocurrency circulating, available and total supplies

This is a project meant to keep track of crypto coin supply data and in a normalized format, hoping to generate community interest and involvement.

The end goal is to have a more transparent and up to date source than what's out there on the web right now.

As such, please help out by submitting a pull request with your favorite coin(s) to track.

# Contributing

1. Fork the project
2. Work on integrating your favorite coins
3. Create a pull request back to the original project

Please submit ATOMIC EDITS, one pull request per one coin, do not mix them.

# How to run all coins available

1. Clone or download the repository
2. Run `npm install`
3. Run `node supplies.js`

# How to run an individual coin

1. Clone or download the repository
2. Run `npm install`
3. Run `node supplies.js bitcoin.js`

# Sample output

```
cardano.js { c: 31112484646, t: 31112484646, m: 45000000000 }
neo.js { c: 65000000, t: 100000000, m: 100000000 }
litecoin.js { c: 55805983.23335135, t: 55805983.23335135, m: 84000000 }
bitcoin.js { c: 16937825, t: 21000000 }
ripple.js { c: 99992401961.25706, t: 99992434971, m: 100000000000 }
ethereum.js { c: 98424406.45 }
```
