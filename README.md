# AvaxLottery

AvaxLottery is a decentralized lottery game built on the Avalanche (AVAX) blockchain, with the flexibility to be deployed on other compatible chains as well. Players can participate by depositing AVAX and predicting whether the price of AVAX will go up or down.

## Features

- Deposit AVAX to participate in the lottery
- Predict the price movement of AVAX (up or down)
- Automated price feed using Chainlink Oracle
- Multiple rounds of gameplay
- Winner selection based on correct predictions
- Dynamic prize pool calculation
- Profit multiplier for winners
- Owner-controlled round execution and withdrawal

## Smart Contract

The `AvaxLottery.sol` contract is written in Solidity and includes the following key components:

- Integration with Chainlink's AggregatorV3Interface for price feeds
- Structs for managing guessed persons, winners, and rounds
- Functions for depositing AVAX, executing rounds, and calculating winners
- Prize pool and profit multiplier calculations
- Automated payout to winners

## How to Play

1. Deploy the contract on the Avalanche network or any compatible EVM chain
2. Players call the `depositAvax` function with their prediction ("up" or "down") and deposit AVAX
3. The contract owner sets the starting price using `setStartedPrice`
4. When ready, the contract owner executes the round using `ExecuteRound`
5. Winners are automatically calculated, and prizes are distributed based on correct predictions

## Installation

1. Clone this repository
2. Install dependencies (if any)
3. Deploy the contract to your chosen network

## Usage

Interact with the contract using a Web3 provider or directly through a blockchain explorer like SnowTrace (for Avalanche).

## Security

Please note that this contract has not been audited. Use at your own risk.

## License

[MIT License](LICENSE)

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to send me mail yagcioglutoprak@gmail.com if you want to contribute.

## Disclaimer

This project is for educational purposes only. Please comply with your local laws and regulations regarding online gambling and lottery games.
