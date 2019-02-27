# How to setup Dero Web Wallet

**Use minimum Golang version 1.11.1 to build.**

* Get and build the Dero daemon from https://git.dero.io/DeroProject/derosuite_webwallet 
* Clone this repository and copy static directory into a webroot folder and copy webroot folder along with mainnet folder.
* In derosuite folder run, GOOS=js GOARCH=wasm go build -o webroot/static/wallet.wasm cmd/webwallet/main.go
* Run Dero daemon and access webwallet using recent browser on 127.0.0.1:20206
* For SSL/TLS support, create keys folder along with mainnet folder and place server.crt and server.key. SSL/TLS only supported on DNS only.

**Dero Web Wallet runs completely in browser and requires Dero daemon only to function without any third party support or modifications. Any seed/key/details never leaves your browser.**

# Back Theme

![DERO Black theme](https://i.imgur.com/FZxtCyD.png)

# White Theme

![DERO White theme](https://i.imgur.com/pVkM9Un.png)
