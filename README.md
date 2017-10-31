# Parity Ethereum Private test network based on Docker Compose

You could use this node for test deployment and interacting with smart contracts for demo.   

### Run parity testnet

Clone the repository docker and run inside the project folder:  

```
$ docker-compose up -d
```

By default this will create:

* 1 Ethereum Bootstrapped container


### Test accounts are ready for use
**All accounts have 1000 Ether on balance**     

**Password:** `Password12345`

**Accounts:**  
1. `0x9e65c373a97793e8d36cb8316ecbe79940110f90`   
Private key: `5182723ba98bc10632156ad481d89a7507c6170312ae901db835a19eeaf147ad`   

2. `0x4fc95b48a473f59c83a4aaefaad2a588a865d013`
3. `0x4ca7393cf5575fdefd8402f16920a33870fc9ef0`
4. `0x800ce51198c95280f2627a330e730bc96f704178`
5. `0xf85d84c5ef6dfd25e9a2f23941a93a05b41ffd7d`
6. `0x010e49e47cbb34e67c072702ed6f4d8b273f751f`
7. `0x67efd57c71232438cb405ce8917e259b8d14ea7e` 
8. `0x4929d7de115ff73fe19fcf8ace73a2bececc9eb0`
9. `0x07a6aea0328e908140670628d67b6133c121f1c7`
10. `0x81eaf903c952447fd27b11db1604f4da6deda0ed`

You could restore account from the keystore and unlock it with a password.    
Keystore placed in `files/keystore/` directory.

***First address (`0x9e65c373a97793e8d36cb8316ecbe79940110f90`) is used for contracts deployment and this account is owner of contracts by default.***   


## Connect to private network via parity wallet with ui
1. Run ethereum private node: `docker-compose up`
2. Wallet Web UI is available via `http://docker-ip:8180` address          
 
 
## Unlock accounts via Parity
1. No need to unlock account. All accounts are unlocked by default  

