# Rock-Paper-Scissors on Aptos ()
#### This repository contains an Aptos-based implementation of the classic Rock-Paper-Scissors game with exciting new features! Players can challenge the computer, track their wins, and compete for the top spot on the leaderboard.

## Features:
* Players can choose their move (Rock, Paper, Scissors).
* The computer randomly selects its move.
* Winner is determined based on the traditional rules.
* Score tracking: Players can see their wins against the computer.
* Leaderboard: Compete with other players for the highest win count.
* Enhanced error handling and user experience improvements.
* Restart game: Players can easily start a new round without affecting their overall score.

## Dependencies
#### This project relies on the Aptos framework. Make sure you have the necessary development environment set up for Aptos development.

## Installation

#### You can either install the Aptos CLI locally or use a cloud-based development environment like Gitpod or Google Cloud Shell. In this guide, we'll show you how to set up Google Cloud Shell, but you're also welcome to use your preferred platform.

## Setting Up Development Environment on Google Cloud Shell

1. Open Google Cloud Shell to access the cloud shell editor. Once it's loaded, run the following command in the terminal to install the Aptos CLI:
```
curl -fsSL "https://aptos.dev/scripts/install_cli.py" | python3
```

2. Export Aptos CLI’s bin directory to your PATH environment variable. For example:
```
export PATH="/home/<your-username>/.local/bin:$PATH"
```

3. To verify that the Aptos CLI has been installed successfully, run the following command:
```
aptos info
```

4. Clone the repository:
```
git clone https://github.com/Raunak567/Rock_Paper_Scissors.git
```
5. Navigate to the project directory:
```
cd Rock_Paper_Scissors
```

#### Since we'll be deploying and interacting with our contract on the Aptos testnet, we need to create an account. Run the following command in your terminal and select "testnet" when prompted. Skip the private key prompt by pressing Enter, and a new account will be generated for you.
