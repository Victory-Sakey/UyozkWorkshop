# Workshop 1 

Deployment Link (Transaction ID) : at1wu6dyrc6c0fjue7l67zqqrsmp2fyh3hgd4pxd6ayt9qgf6m3jqps3wqnd4 

Preview:
![Screenshot 2024-08-23 172346](https://github.com/user-attachments/assets/25c0986b-7d40-45e9-b0f3-84f51b1b029f)

Description:
`leo run main 3u32 2u32 --network testnet`
Where main =》transition function name, `3u32 2u32` is the inputs and network is specified `testnet`


# Workshop 2 

Deployment Link (Transaction ID) : at1m38ju7dy0llwqynh5zxpmm7r2e69yuyxuwgqa6yjzg0nkx8qy5xq3n708g

Preview:
![Screenshot 2024-08-23 173728](https://github.com/user-attachments/assets/2b94946d-3fdc-4a3f-aa35-4012282d9702)

Description:
1st Command : `leo run mint <type_aleo_address> <type_amount>u64`

2nd command: `leo run transfer "<Token_Record>" <to_address> <amount>u64`

We were able to use the generated record from 1st command to input into the second command's first input (remember) and then our to address and amount 
`generated private key in your .env needs to be change to that of your Leo wallet private key`
Records are used to store user/data components. To view a record, you need a view key which you need to share only to trusted parties, View key doesn't compromised Leo wallet but can lead to someone monitoring your data/asset


# Workshop 3 

Deployment Link (Transaction ID) : at1y8mx9u744ne6rvzhayu0fx5v3l6fqfnahnvrqv5t4qnenyjxqvzsd0tu55 

Preview:
![Screenshot 2024-08-23 174318](https://github.com/user-attachments/assets/2bcb7143-553f-4b63-81f0-c0ab27272918)

Description:
`leo run combine_hash_owner_receiver <type_your_address> <type_friend_address>`
This has only 2 inputs where first input is owner address (self.caller) and second input is the  receiver address
