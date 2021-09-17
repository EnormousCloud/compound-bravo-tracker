# compound-bravo-tracker

### Events to track
```
event ProposalCreated(uint id, address proposer, address[] targets, uint[] values, string[] signatures, bytes[] calldatas, uint startBlock, uint endBlock, string description);
event VoteCast(address indexed voter, uint proposalId, uint8 support, uint votes, string reason);
event ProposalCanceled(uint256 id);
event ProposalQueued(uint256 id, uint eta);
event ProposalExecuted(uint256 id);
event VotingDelaySet(uint oldVotingDelay, uint newVotingDelay);
event VotingPeriodSet(uint oldVotingPeriod, uint newVotingPeriod);
event NewImplementation(address oldImplementation, address newImplementation);
event ProposalThresholdSet(uint oldProposalThreshold, uint newProposalThreshold);
event NewPendingAdmin(address oldPendingAdmin, address newPendingAdmin);
event NewAdmin(address oldAdmin, address newAdmin);
```

### DAO, using compound governance:
```
Nouns DAO:  0x6f3e6272a167e8accb32072d08e0957f9c79223d
YUAN:       0x6d5556b3cbd13375faa08831588005900a966c60
GTC :       0xdbd27635a534a3d3169ef0498beb56fb9c937489
Marlin:     0x777992c2e4edf704e49680468a9299c6679e37f6
YAM:        0x2da253835967d6e721c6c077157f9c9742934aea
Inverse:    0x35d9f4953748b318f18c30634ba299b237eedfff
Contribute: 0x8e6f20f7e6a0b56e4fa01076347583203bf28cb3
VELO:       0xa1d8800ae2f4794f2910cfcd835831faae69cea0
Compound:   0xc0da02939e1441f497fd74f78ce7decb17b66529
TLTF:       0xa01f257c20fa5c094917bf2c755de517839b8ee4
Dopex(?):   0x91d9c2b5cf81d55a5f2ecc0fc84e62f9cd2cefd6
```    


#### License
MIT
