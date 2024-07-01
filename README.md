# Verdikta

Verdikta is an open-source blockchain project designed to execute AI software in a decentralized, trustless manner to answer questions about data and incorporate the results into smart contracts. By leveraging Chainlink nodes, AI analysis, and the VRB token, Verdikta aims to minimize fees and enhance the reliability of smart contract resolutions.

## Directory Structure

Here's a brief description of each folder in the Verdikta project:

### .github/
Contains GitHub-specific files for managing issues, pull requests, and continuous integration workflows.
- `ISSUE_TEMPLATE/`: Templates for bug reports and feature requests.
- `workflows/`: CI workflow configuration files.

### docs/
Holds all the project documentation, including whitepapers, guides, and templates.
- `whitepaper/`: The Verdikta whitepaper detailing the project's goals, technology, and approach.
- `guides/`: Guides for getting started, using the token, setting up oracles, and understanding the consensus mechanism.
- `templates/`: Templates for smart contracts and Chainlink nodes.
- `README.md`: Overview of the documentation.

### contracts/
Contains the smart contracts and their tests.
- `VRBToken.sol`: The ERC-20 token contract for VRB.
- `VRBTokenBridge.sol`: The contract for bridging VRB tokens to the L2 Base.
- `OracleInterface.sol`: Interface contract for oracles.
- `AIResolutionSystem.sol`: The AI resolution system contract.
- `templates/`: Example smart contracts and oracles.
- `tests/`: Test scripts for the smart contracts.

### chainlink/
Includes files related to Chainlink nodes and their interactions with AI APIs, IPFS, GitHub, and blockchains.
- `nodes/`: Configuration and scripts for individual Chainlink nodes.
- `interaction/`: Code for interacting with AI APIs, IPFS, GitHub, and blockchains.
- `consensus/`: Implementation of the MxN consensus mechanism with weighted voting.
- `scripts/`: Scripts for setting up and managing Chainlink nodes.

### airdrop/
Scripts and files related to the VRB token airdrop.
- `airdrop_script.js`: Script for executing the airdrop.
- `airdrop_list.csv`: List of recipients for the airdrop.
- `airdrop_results/`: Results of the airdrop process.

### market/
Scripts for setting up liquidity pools and managing VRB tokens on exchanges.
- `uniswap/`: Scripts for setting up and managing Uniswap pools.
- `other_exchanges/`: Scripts for setting up and managing pools on other exchanges.

### scripts/
Shell scripts for deploying contracts and running tests.
- `deploy_contracts.sh`: Script to deploy smart contracts.
- `run_tests.sh`: Script to run tests.
- `deploy_oracles.sh`: Script to deploy oracles.

### src/
Source code for interacting with AI, IPFS, GitHub, and blockchains.
- `ai_interaction/`: Code for formatting AI queries, parsing responses, and weighting results.
- `ipfs_interaction/`: Code for uploading to and retrieving from IPFS.
- `github_interaction/`: Code for interacting with GitHub.
- `blockchain_interaction/`: Code for interacting with blockchains.

### tests/
Unit and integration tests.
- `integration/`: Integration tests for AI, IPFS, and Chainlink interactions.
- `unit/`: Unit tests for individual components.

### package.json
Node.js project file with dependencies and scripts.

### README.md
Overview of the Verdikta project, including a description of the directory structure.

### LICENSE
Open-source license for the project.

## Getting Started

To get started with Verdikta, please refer to the guides in the `docs/guides/` directory. These guides will help you set up your development environment, deploy smart contracts, interact with Chainlink nodes, and more.

## Contributing

We welcome contributions from the community. Please see the `CONTRIBUTING.md` file in the `docs/` directory for more information on how to contribute to the project.

## License

This project is licensed under the [MIT License](LICENSE).

---

For detailed instructions and further information, please refer to the documentation in the `docs/` directory. If you have any questions or need assistance, feel free to open an issue or contact us through our community channels.
