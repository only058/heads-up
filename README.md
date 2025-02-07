
# Aptos Heads Up

Aptos Heads Up is an implementation of the popular coin flip game on the Aptos blockchain. Users can participate by predicting the outcome of 10 consecutive coin flips. If the user's prediction matches the actual outcome, they receive a prize. The flip outcome is determined and provided by the module admin.

## Key Features

-   **Coin Flip Game**: Users predict the results of 10 coin flips.
    
-   **Rewards System**: If the user's prediction matches the actual results, they win a prize.
    
-   **Blockchain Integration**: Built on the Aptos blockchain for transparency and security.
    
-   **Resource Accounts**: Utilizes Aptos resource accounts to manage game logic.
    
-   **AptosCoin Support**: Rewards and transactions are managed using AptosCoin.
    

## Getting Started

### Prerequisites

-   Install Aptos CLI for interacting with the Aptos blockchain.
    
-   Set up an Aptos wallet with testnet tokens.
    

### Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/only058/heads-up.git
    cd aptos-heads-up
    ```
    
2.  Install dependencies:
    
    ```
    aptos move compile
    ```
    
3.  Deploy the module:
    
    ```
    aptos move publish --profile default
    ```
    

## Usage

1.  Start a new game session by submitting your prediction.
    
2.  The module admin will determine and provide the flip outcome.
    
3.  If your prediction matches the outcome, you receive a reward in AptosCoin.
    

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License.
