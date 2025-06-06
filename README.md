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
> [!Warning]
> To work with the mongo inside the docker use this variable:
> ``` MONGODB_URL=mongodb://mongo:27017 ```
> 
> Instead, if you want to work with an external mongodb modify this variable.


In this case the Alchemy provider has been used, but you are free to use whatever you want for the Web3 provider.

# Before you run the application 

> [!Warning]
> ### Remove the `package-lock.json` from:
>
> `FrontEnd/package-lock.json`
>
> `Backend/package-lock.json`

## How to run the application
```
docker compose up
```
> [!NOTE]
> ## How to test the application
> To test the visualization page, use the test file located inside the repo.
> 
> `TestFile/testFile.json`

## A brief explanation of the ecosystem is in the wiki 
### Extraction and Query page
[Extraction and query](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Extraction-and-Query)

### Visualization page
[Visualization page](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Visualization-page)

### Analysis page 
[Analysis page](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Analysis-page)





