# StakingContrac.sol
This is a Solidity contract code for a staking rewards system. It allows users to stake tokens of a specific type, and receive rewards in another token type. 

The rewards amount, duration, and rate are determined by the contract owner. The owner can also notify the contract of the reward amount. The contract calculates the rewards based on the amount of tokens staked, the duration of the rewards, and the reward rate set by the owner. 

Users can check their rewards, and withdraw their staked tokens or rewards at any time. 

The contract includes a number of security checks, such as ensuring the reward rate is greater than 0 and the reward amount does not exceed the balance of the contract.
