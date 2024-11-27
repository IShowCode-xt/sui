# sui
move1 test1
https://fullnode.testnet.sui.io

curl --location --request POST 'https://faucet.testnet.sui.io/gas' \ 
--header 'Content-Type: application/json' \
--data-raw '{
    "FixedAmountRequest": {
        "recipient": "0x3cadba31c03166e53d2ab7969ae72553ad1950af6d7e6536cfc91493c14edffb"
    }
}'
