# DApp_analysis_ecosystem


## Set up the application

To download all the repositories inside this repo

```
git clone --recursive https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem.git
```
> [!IMPORTANT]
>  ### Backend
> In the root folder of `Backend` you have to create a `.env` file like this:
```
WEB3_ALCHEMY_MAINNET_URL=https://eth-mainnet.g.alchemy.com/v2/<alchemy_api>
WEB3_ALCHEMY_SEPOLIA_URL=https://eth-sepolia.g.alchemy.com/v2/<alchemy_api>

API_KEY_ETHERSCAN=<etherscan_api>
ETHERSCAN_MAINNET_ENDPOINT=https://api.etherscan.io/api
ETHERSCAN_SEPOLIA_ENDPOINT=https://api-sepolia.etherscan.io/api

MONGODB_URL=<connection_string>
LOG_DB_NAME=backlog
```
> [!NOTE]
> You have to replace the string <...> with your values.


> [!Warning]
> To work with the mongo inside the docker use this variable:
> ``` MONGODB_URL=mongodb://mongo:27017 ```
> 
> Instead, if you want to work with an external mongodb modify this variable.

In this case, the Alchemy provider has been used; however, you are free to use any provider of your choice for the Web3 provider.

> [!IMPORTANT]
>### Frontend 
>If you want to use a different address for your server, you have to change it in the `Frontend/src/api/service.js`.
>Replace the value of `serverUrl` with your value

# Before you run the application 

> [!Warning]
> ### Remove the `package-lock.json` from:
>
> `FrontEnd/package-lock.json`
>
> `Backend/package-lock.json`

> [!Warning]
> ### Remove the `package-lock.json` from:
## How to run the application
```
docker compose up
```
> [!NOTE]
> ## How to test the application
> ### Make sure you read the visualization page in the wiki first.
> [Visualization page](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Visualization-page)
> 
> To test the visualization page, use the test file located inside the repo.
> 
> `TestFile/testFile.json`
>
> 

## A brief explanation of the ecosystem is in the wiki 
### Extraction and Query page
[Extraction and query](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Extraction-and-Query)

### Visualization page
[Visualization page](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Visualization-page)

### Analysis page 
[Analysis page](https://github.com/AlessandroMarcellettiUnicam1/DApp_analysis_ecosystem/wiki/Analysis-page)





