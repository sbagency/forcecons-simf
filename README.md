# forcecons-simf
simf is a fork of [distributed consensus simulation](https://github.com/web3scout/forcecons-sim) with advanced consensus rules.

simf simulation https://web3scout.github.io/forcecons-simf/

### consensus rules
- nodes broadcast blocks (bk)
- nodes broadcast blocks confirmations (bk_ok)
- nodes accept blocks when 1/2 confirmations received
- nodes don't accept old blocks (< last block number)
