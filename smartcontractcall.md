# 3. Issue a Smart Contract Call to the Deployed Smart Contract


1. A screenshot of the console output immediately after you have successfully issued a smart contract call.
![call](https://github.com/skinnynoizze/nervosbounty/blob/main/smartcontractcall.png)
2. The transaction hash from the console output (in text format).
0x4be3e1550557573af30e17c64f8a1769bd8ccb03a6cad11065dedfbc19b3b3a0
3. The contract address that you called (in text format).
0xB8c8ae11adf7D8E6B359BD8C1595A2Ff191Bfb56
4. The ABI for contract you made a call on (in text format).
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
