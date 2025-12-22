Contracts folder (design notes)

Recommended structure
- contracts/
  - CoreToken.sol (ERC20 + governance hooks)
  - Cell_*.sol (modular cell contracts)
  - Governance.sol (proposal + voting + timelock)
  - OracleAdapter.sol (Chainlink adapter + aggregation)

Suggested toolchain
- Solidity (0.8.x)
- Hardhat for development, testing, and deployment
- Ethers.js for scripts and off-chain interactions

Next steps
- Add a minimal Hardhat scaffold and an example Cell contract
- Implement OracleAdapter with mock Chainlink feeds for testing
- Write unit and economic simulation tests
