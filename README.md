# rise-in-solidity-bootcamp-september-competition-final-case
This project is a final case of Rise In Solidity & BNB Chain Development Bootcamp September competition.
Welcome to the JourneyGo!

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Future Ideas](#future-ideas)
- [Getting Started](#getting-started)
    - [Installation](#installation)
- [Run Project](#run-project)
- [Contributing](#contributing)

## Overview

The **JourneyGo DApp** provides to the users can create journey to their travel routes and other users can join his journey. App has its own token called with Journey Token ($JNG). $JNG created with ERC20 standarts. User can buy JNG in app and use them for journeys. You can analyze contract on BSC Testnet: https://testnet.bscscan.com/address/0xd9eC60392312b047Bef2DDC1eD78cB49C490faF3

## Features

- Buy token from contract.
- Pay for journeys with token.
- Create journey without any fee (Gas fees excluded).
- 10% of journey cost will be burned after journey confirmed.
- 15% of journey cost will be distributed among journey passengers (driver is included).
- 15% of journey cost will be taken from contract and rest of all balance will transferred to the driver.
- All journey details saved in database until journey confirmed. After journey confirmed only passengers can see their journeys.

## Future Ideas
- If journey date has passed journey will be deleted automatically.
- Passengers can leave from journey.
- Passengers can make offer to the driver. (e.g. Passenger pays more than journey cost and start journey quickly)
- Tokens can be transferred between users.
- Drivers can cancel or update their journeys.

## Getting Started
1. Add BSC Testnet to your Metamask wallet. You can see guide in: https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain
2. Make sure you have enough BNB for buy token. You can get test BNB from here: https://testnet.bnbchain.org/faucet-smart
3. Follow the steps inside the projects to set up the whole project locally and lets hit the road with this awesome web3 app.

### Installation
#### !!!Warning!!!
To get submodules with project repo follow the code below. Or you can use Github Desktop app to clone repo automatically (Highly recommended).
1. Clone the repository:

```bash
  git clone --recurse-submodules https://github.com/melihgunduz/rise-in-solidity-bnb-chain-development-bootcamp-september-competition-final-case.git
```

2. Navigate to the project directory:

```bash
  cd rise-in-solidity-bnb-chain-development-bootcamp-september-competition-final-case
```
3. Navigate to which project you want to work. Then read their README.md for installation.

```bash
  cd frontend
```
```bash
  cd backend
```
```bash
  cd smart-contract
```

## Run Project
1. Run server in backend project.
2. Run app in frontend project.
3. Smart contract already deployed in BSC Testnet, it works. Smart Contract has given in overview section.

## Contributing

Contributions to this project are welcome! To contribute:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make changes and test thoroughly.
4. Commit with clear and concise messages.
5. Push changes to your fork.
6. Submit a pull request describing your changes.
