# Send-Web3-payment-coins

Ensure you create directory in your directory.

`git clone https://github.com/aminshokripwa/Send-Web3-payment-coins.git`

## Download the packages used to create this rest API
Run the following commands to install all the necessary packages.

```
npm install --legacy-peer-deps
```

## Setting configuration

You can use Metamask plugin for your browser and use Ganache for send coin in your local

[Download Metamask](https://metamask.io/download/)
[Download Ganache](https://www.trufflesuite.com/ganache)

### Important!

Start the Ganache blockchain and (pres on the key icon) copy the private key of the desired account.

![Image of Project](/helps/01.gif)

Open MetaMask and pres on the Add network entering the RPC URL and Chain ID and Currency Symbol

![Image of Project](/helps/02.jpg)
![Image of Project](/helps/03.jpg)

Add (new user) Creat Account with private key

![Image of Project](/helps/04.jpg)

In Metamask choose recent user and network

## Running the project

`npm start`

## Use it
After insert address (new ACCOUNT ADDRESS choosed from Ganache) and the amount of coin, Press on PAY NOW, Metamask in your browser ask you question to allow your browser for send money and confirm it, If you confirm it, Coin will be sending to that address.
![Image of Project](/helps/05.jpg)

![Image of Project](/helps/06.jpg)
