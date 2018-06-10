coldog
====
Offline wallet solution for [mchain](https://github.com/pjc0247/mchain).<br>

__You can__
* Create a new wallet
* Transfer coins
* Deploy a contract
* Execute a contract method

__even your PC is offline__



Usage
----
__Create a new wallet__
```
coldog create -o wallet.json
```

__Transfer coins__
```
coldog transfer -i wallet.json -o tx.json -r RECEIVER_ADDRESS -v 1000
```


__Broadcast (Must be online)__
```
coldog broadcast -i tx.json
```
