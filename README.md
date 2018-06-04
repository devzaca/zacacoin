![ZacaCoin](./A.svg)

## Zaca Coin
Zaca is a PoS and masternode privacy focused cryptocurrency with lighting fast payment confirmations. ​

Zaca empowers the way we use crypto by its innovative privacy features and impeccable block size of 40 mb, which easily accommodates millions of transactions effortlessly.
​
The Intergrated wallet technology provides users with E2E messaging, Stealth Mixer, and Stealth Addresses. Zaca provides more than enough anonymity in addition to being an income source with our Masternodes PoS functionality.

## Links
 - Website: https://www.zacacoin.com/
 - Discord: https://discord.gg/jApu4cG
 - ANN: https://bitcointalk.org/index.php?topic=2988037.0
 - Telegram:

## Specifications

 - Block Spacing: 60 Seconds
 - Diff Retarget: 4 Blocks
 - Maturity: 30 Blocks
 - Stake Minimum Age: 1 Hours
 - 40 MegaByte Maximum Block Size (40X Bitcoin Core)
 - PoS Proof of stake begins: 1440 block
 - Minimum Stake: 0.01 Zaca
 - Port: 7777
 - RPC Port: 6666

Zaca includes an Address Index feature, based on the address index API (`searchrawtransactions` RPC command) implemented in Bitcoin Core but modified implementation to work with the ZACA codebase (PoS coins maintain a txindex by default for instance).

Initialize the address index by running the `-reindexaddr` command line argument. It may take 10-15 minutes to build the initial index.

## Dependencies

Zaca is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1


## Masternode Installation and Guidance

Masternode installation can be acheived on a Ubuntu VPS and using a local PC wallet to store and stake your coins away from the masternode VPS. 

### Manual Installation
Manual step by step installation instructions can be found at: https://medium.com/@click2install.moore/definitive-guide-to-setting-up-a-zacacoin-masternode-319d7c99d419

### Automated Installation
A fully automated installation script for a Ubuntu VPS can be found at: https://github.com/click2install/zacacoin

