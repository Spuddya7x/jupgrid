## Jupgrid: Decentralized Grid Trading Bot Version 0.1.0 Alpha

![GitHub last commit](https://img.shields.io/github/last-commit/spuddya7x/jupgrid) ![GitHub issues](https://img.shields.io/github/issues/spuddya7x/jupgrid) ![GitHub number of milestones](https://img.shields.io/github/milestones/all/spuddya7x/jupgrid) ![GitHub stars](https://img.shields.io/github/stars/spuddya7x/jupgrid?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/spuddya7x?style=social)](https://twitter.com/spuddya7x)

Jupgrid is a cutting-edge, fully decentralized cryptocurrency grid trading bot designed to operate on the Jupiter Limit Order Book. It runs locally on your machine, offering a secure and personal way to automate a grid trading bot. This bot only places 1 buy and 1 sell order at a time, meaning you can be more capital efficient!

Use of this bot/script is at your own risk. Use of this bot/script can lead to loss of funds, so please exercise proper due diligence and DYOR before continuing.

## Table of Contents

- [Features](#features-)
- [Installation](#installation-)
- [Usage](#usage-)
- [Configuration](#configuration-)
- [Contributing](#contributing-)
- [License](#license-)

## Features ✨

-   **Fully Decentralized Trading:** Operates on the Jupiter Limit Order Book, ensuring full control over your trading data and strategy.
    [Jupiter Limit Order Book](https://jup.ag/limit/SOL-USDC)
-   **Local Operation:** Runs on your own machine, or a VPS, providing an additional layer of security and privacy.
-   **Simple Grid Strategy:** Places one buy order and one sell order based on user-defined parameters, optimizing for market conditions, whilst being capital efficient.
-   **Easy Setup:** Comes with a straightforward installation and setup process, including auto-creation of necessary user files.
-   **User Prompted Parameters:** Dynamically prompts the user for trading parameters, allowing for flexible and responsive trading setups.

## Installation 🔧

Download the source code by cloning it:

```bash
git clone https://github.com/SpuddyA7X/jupgrid
npm install
```

## Usage 🚀

1. **Initial Setup:** Run Jupgrid for the first time to create the necessary user configuration files:

```bash
    node .
```

This will generate a `.env` file where you will fill in your secure data.

2. **Configuration:** Open the `.env` file in a text editor and input your Phantom wallet Private Key, and the URL to your RPC.

3. **Run Jupgrid:** Start Jupgrid again with `node .` to launch the bot. Upon startup, you will be prompted to enter the following parameters:

    - Token A:
    - Token B:
    - Size (In Token A):
	- Spread (% difference from current market price to orders):

Jupgrid will then place one buy and one sell order based on the parameters you have set.

## Configuration ⚙️

The `.env` file will need to contain your Phantom Wallet Private Key and URL to your RPC connection. Ensure you fill it out before running the bot for the second time:

-   `RPC_URL`=YourRPCURLHere
-   `PRIVATE_KEY`=YourPrivateKeyHere

There will also be a `userData.json` file created. This will contain data on the parameters you set during setup.

## Contributing 🤝

We welcome contributions from everyone! To contribute:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Create a new Pull Request
6. ❤️

#### Follow me on Twitter: [@SpuddyA7X](https://twitter.com/SpuddyA7X) for more updates.

## License 📄

This project is licensed under the MIT License - see the `LICENSE` file for details.
