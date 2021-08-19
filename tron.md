## 11. Use a Tron Wallet to Execute a Smart Contract Call

### A screenshot of the accounts you created (account list) in ckb-cli.

![account](https://github.com/skinnynoizze/nervosbounty/blob/main/ckb-accounts.png)

### A link to the Layer 1 address you funded on the Testnet Explorer.  
https://explorer.nervos.org/aggron/address/ckt1qyq0re72caj4az9wwps2ex2mdrl804kpf8hqmu5rkr

### A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

![deposit](https://github.com/skinnynoizze/nervosbounty/blob/main/depositTron.png)

### A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.

![call](https://github.com/skinnynoizze/nervosbounty/blob/main/smartcontractTron.png)

### The transaction hash from the console output (in text format).  
0x38fd9c66eeaf9ff5f4d15c17efe0b7c3ce4088578c93453108d4aab15d6d4c53

### The contract address that you called (in text format).  
0xB8c8ae11adf7D8E6B359BD8C1595A2Ff191Bfb56

### The ABI for contract you made a call on (in text format).  
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]

### Your Tron address (in text format).  
TGVmZmsN1WamuabWWgKBRVciDHvy59PyAA
