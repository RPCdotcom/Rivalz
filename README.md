# Rivalz Node Setup
Rivalz Node Setup / Cli / Ubuntu Server


Server : 
Hetzner : bit.ly/hetznerlink
Contabo : https://bit.ly/contabourl

Update : 
Copy
sudo apt-get update && sudo apt-get upgrade -y

Install Curl : 

sudo apt install -y curl
Node.js 20 

curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```console
sudo apt install -y nodejs
```console
node --version
```
Install Screen  ( Optional ) : 
```console
apt-get install screen -y
```
Screen ( Optional ) : 
```console
screen -S rivalz
```
Install Rivalz : 
```console
npm i -g rivalz-node-cli
```

You can see these - No problem
If you want to know the serial number of your disk : 

```console
sudo lshw -class disk
```
Run rClient : 
```console
rivalz run
```
Your Connected Rivalz Wallet Adress : 
CPU Core 
RAM 
Disk Type
Disk Serial Number ( if you dont know - enter ) 
Enter disk size, you want to allow the client use


Result : 

Attention !
After setting up your node, do not forget to press the validate button on the site!
https://rivalz.ai/dashboard/node-validate


Rivalz Update ?
I got a message that the client CLI has a new version. How do I update it?

```console
rivalz update-version

```console
rivalz run
```

How do I update the client's information ?
```console
rivalz update
```
Other Commands : 
```console
rivalz -h
```

Screen Commands : 
Logout Scren : 

CTRL A + D

Screen List : 

```console
screen -ls
```
Entering the Screen :

```console
screen -r screenname
```
Delete Screen : 

```console
screen -X -S screenpidnumber.screenname quit
```
WEB : https://rpcdot.com/
Services : https://services.rpcdot.com/
X : https://x.com/rpcdot

