# Anunna Pool Tutorial

## 1.Register

​	Send your **user name** and your **AR address** to : unamedalias@protonmail.com ,you will get feedback

​	

## 2.Preparation

​	

|      OS      |                          Weave Data                          | Register                                                  |
| :----------: | :----------------------------------------------------------: | --------------------------------------------------------- |
| Ubuntu 20.04 | visit   https://github.com/ArweaveTeam/arweave/releases/tag/N.2.4.1.0     - *chunk_storage* folder | send us your name and address , we will bind your address |



## 3. GET & RUN  Miner

### 	Linux

```shell
#Only support ubuntu 20 ,ubuntu 18 is on the way 
 wget -O AnunnaMiner.tar.gz http://47.108.105.120:9000/ar/miner?version=20 
 tar -xzf AnunnaMiner.tar.gz
 cd ./AnunnaMiner
 #your will see Config.json
 vim Config.json
 #Adjust the number of threads based on your CPU
 #config your address registered or The miner will not work
 #config your chunked weave data path
 ./AnunnaMiner.py
 
 #you can run mutil AnunnaMiner.py if your rigs are in high performance mod
```

Config.json

```json
{
        "threads": 26, #Adjust the number of threads based on your CPU
        "reward_addr": "your_ar_addr", #config your address registered or The miner will not work
        "chunk_path": "/home/arweave/chunk_storage"  #config your chunked weave data path
}
```



### 	Windows

```
Coming soon......
```



## 4.Pool stat

visit http://47.108.105.120:9090, then login with your user name and password

search your address，You will see your hash in pool and balance 



