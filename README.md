
Force development tree

Force is a PoS-based cryptocurrency.

FOR is dependent upon libsecp256k1 by sipa, the sources for which can be found here:
https://github.com/bitcoin/secp256k1

Total POW: 50,000 Blocks
POW Reward: 1500 FOR per Block
POS Reward: 1500 FOR (HiPOS) to block 50k after this 
Block Spacing: 30 Seconds
Diff Retarget: 10 Blocks
Maturity: 20 Blocks
Stake Minimum Age: 24 Hours

40 MegaByte Maximum Block Size (40X Bitcoin Core)

Port: 37246
RPC Port: 37245

Magic Bytes: 0xf1 0xac 0xa1 0xc7

FOR includes an Address Index feature, based on the address index API (searchrawtransactions RPC command) implemented in Bitcoin Core but modified implementation to work with the FOR codebase (PoS coins maintain a txindex by default for instance).

Initialize the Address Index By Running with -reindexaddr Command Line Argument.  It may take 10-15 minutes to build the initial index.


