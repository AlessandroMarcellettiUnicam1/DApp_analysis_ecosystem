# DApp_analysis_ecosystem


## Set up the application

To download all the repositories inside this repo

```
git clone --recursive https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem.git
```

In the root folder of `Backend` you have to add a `.env` file like this:

```
WEB3_ALCHEMY_MAINNET_URL=https://eth-mainnet.g.alchemy.com/v2/<alchemy_api>
WEB3_ALCHEMY_SEPOLIA_URL=https://eth-sepolia.g.alchemy.com/v2/<alchemy_api>

API_KEY_ETHERSCAN=<etherscan_api>
ETHERSCAN_MAINNET_ENDPOINT=https://api.etherscan.io/api
ETHERSCAN_SEPOLIA_ENDPOINT=https://api-sepolia.etherscan.io/api

MONGODB_URL=<connection_string>
LOG_DB_NAME=backlog
```
In this case the Alchemy provider has been used, but you are free to use whatever you want for the Web3 provider.

Make sure that there is no `package-lock.json`
## How to run the application
```
docker compose up
```






