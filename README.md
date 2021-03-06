<br />
<p align="center">
  <h3 align="center">Yearn Style Strategy</h3>

  <p align="center">
    The contract(s) in this project essentially aim to replicate what yearn finance has done in terms of optimizing yield by allowing you to deposit your funds into a vault and moving the funds between protocols to the highest yield generating protocol whenever someone interacts with one of the contracts.
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

### Built With

- [Solidity](https://soliditylang.org/)
- [Hardhat](https://hardhat.org/)
- [TypeScript](https://typescriptlang.org/)
- [Tenderly](https://tenderly.co/)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/0xdavinchee/uniswap-interaction.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
   <!-- USAGE EXAMPLES -->
3. Create a `.env` file and add the two following values:

- `INFURA_API_KEY`: You can get this from https://infura.io by signing up for a free account.
- `RINKEBY_PRIVATE_KEY` (if you want to deploy to testnet).
- `ALCHEMY_MAINNET_URL`: You can get this from https://alchemyapi.io by signing up for a free account.

## Usage

To compile: `npx hardhat compile`.

To run tests: `npx hardhat test`.

Run `npx hardhat node` to start up a local node.

Open up another terminal window and run `npx hardhat deploy --network localhost` to deploy your project to localhost. You can similarly deploy to other networks like so: `npx hardhat deploy --network <NETWORK>`.

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.

<!-- CONTACT -->

## Contact

[@0xdavinchee](https://twitter.com/@0xdavinchee) - 0xdavinchee@gmail.com

Project Link: [https://github.com/0xdavinchee/uniswap-interaction](https://github.com/0xdavinchee/uniswap-interaction)
