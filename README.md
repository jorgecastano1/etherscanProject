## Setup
1. Copy `.env.example` to `.env`
2. Add your Etherscan API key to `.env`
3. Run: `python etherscanProject`

## What is it?
A command line interface EtherScan API wrapper function that outputs
wallet address and transaction information provided an Ethereum hex wallet 
address or hex Ethereum transaction hash

## Testing Setup
Run python debug_api to ensure api key is properly configure
Run python test_env to ensure environment is working appropriately

## Recommendations
Implementing virtual environment first and then downloading required libraries
from requirements.txt in new environment 

Run: pip install -r requirements.txt