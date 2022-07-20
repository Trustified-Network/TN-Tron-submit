## Trustified Network is a platform to Sell Digital Services Globally and Accept Crypto Payments without paying Hefty Commissions.

## Inspiration

“Trust” is a key factor for successful transactions between parties. To ensure trust, we involve third party freelancing platforms or middlemen and pay hefty commissions which highly affect the overall profit margins of parties involved in a transaction.


## What it does

Trustified.network is a smart contract assured Escrow Agreement and Payment platform which helps individuals and businesses to grow globally and increase profit margins in four simple steps:

1) List Products, Services, or subscription packages.
2) Create Escrow agreements with personalized terms as per customers.
3) Send/Receive crypto payments in a reliable and secure way without paying hefty commissions to third parties. 


# Tronbox  

https://github.com/Trustified-Network/TN-Tron-submit/blob/master/tronbox.js


```javascript

require("dotenv").config({ path: "./.env" });

const privateKey = process.env.REACT_APP_PRIVATE_KEY;
const address = process.env.REACT_APP_ADDRESS;
const address2 = process.env.REACT_APP_ADDRESS2;

module.exports = {
    networks: {
        compilers: {
            solc: {
                version: '0.8.0'
            }
        },
        development: {
            from: address,
            privateKey: privateKey,
            consume_user_resource_percent: 30,
            fee_limit: 100000000,
            fullNode: "https://api.shasta.trongrid.io",
            solidityNode: "https://api.shasta.trongrid.io", 
            network_id: "*"
        },
        production: {
            from: address2,
            privateKey: privateKey,
            consume_user_resource_percent: 30,
            fee_limit: 100000000,
            fullNode: "https://api.shasta.trongrid.io",
            solidityNode: "https://api.shasta.trongrid.io", 
            network_id: "*"
        },
    },
    solc: {
        optimizer: {
            enabled: false,
            runs: 200
        },
    }
};

```

# TRON Network

```javascript

const TRON = {
    chainId: "0xC383",
    chainName: "shasta",
    rpcUrls: ["https://api.shasta.trongrid.io/jsonrpc"],
    nativeCurrency: {
        name: "shasta",
        symbol: "TRX",
        decimals: 16,
    },
    blockExplorerUrls: ["https://shasta.tronscan.org"],
} 
export { TRON };  

```

# Contract Address => TWu3fad53z8RAqbQvsRndDvQYfPJhipp8L



# Homepage 
![Screenshot 2022-07-20 at 11 10 06 AM](https://user-images.githubusercontent.com/3678906/179905712-93c2ce0d-0a93-46bf-9802-295eb72add71.png)

# Escrow Agreement
![Screenshot 2022-07-20 at 11 10 28 AM](https://user-images.githubusercontent.com/3678906/179905762-0cae4b87-97a2-4fbe-bcf9-4732c262a41d.png) 

# Crypto Payment
![Screenshot 2022-07-20 at 11 10 42 AM](https://user-images.githubusercontent.com/3678906/179905784-b95ea6cc-67ac-4844-b5c5-31e7b81a2a61.png)

# Product/Services
![Screenshot 2022-07-20 at 11 10 56 AM](https://user-images.githubusercontent.com/3678906/179905829-c7e3340d-224f-4824-93dd-c2dd49d2042e.png) 

# Invoice 
![Screenshot 2022-07-20 at 11 11 07 AM](https://user-images.githubusercontent.com/3678906/179905906-7b518820-e119-4de9-ad9f-4379b0224426.png)  

# Invoice Details
![Screenshot 2022-07-20 at 11 11 20 AM](https://user-images.githubusercontent.com/3678906/179905956-200ea423-8f98-4de9-a601-be9fd0b70450.png) 

# Fiat-on-Ramp
![Screenshot 2022-07-20 at 11 12 17 AM](https://user-images.githubusercontent.com/3678906/179906002-fd59a82a-9e19-4010-a665-6c1defba483d.png)
