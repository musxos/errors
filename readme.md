# My erros!

```
const contractRead = useContractRead({
        address: '0xA0Cd9364dF8095aBAA2980dc779D5349bB63C289',
        abi: [
            {
                "inputs": [
                    {
                        "internalType": "address",
                        "name": "_owner",
                        "type": "address"
                    }
                ],
                "name": "getNFTBalance",
                "outputs": [
                    {
                        "internalType": "uint256",
                        "name": "",
                        "type": "uint256"
                    }
                ],
                "stateMutability": "view",
                "type": "function"
            },
        ],
        functionName: 'getNFTBalance',
        args: ['0x95d48e177eA89B7d1c21A64A614eeDD795c6B4f5'],
        enabled: enabled,
        onSuccess(data) {
            console.log(data);
        },
    })
```

![image](https://github.com/musxos/errors/assets/34295148/546c65a5-9fe0-4933-a207-260465d7b9f1)
