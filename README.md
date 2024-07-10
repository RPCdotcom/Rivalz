# Rivalz Node Setup
Rivalz Node Setup / Cli / Ubuntu Server

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/3811b7cf-1689-47fd-a888-201b23caae9c)


# Server : 
Hetzner : https://bit.ly/hetznerlink
Contabo : https://bit.ly/contabourl

Update : 
```console
sudo apt-get update && sudo apt-get upgrade -y
```

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/9d073202-d259-4cd0-b776-db9e5ebe2103)


Install Curl : 
```console
sudo apt install -y curl
```

Node.js 20 


```console
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
```

```console
sudo apt install -y nodejs
```

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

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/e49d381c-1d42-4949-a4b5-7cbb333f7a13)

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/a123ec25-47c4-43b2-bcda-f164823dbdc8)

You can see these - No problem

If you want to know the serial number of your disk : 

```console
sudo lshw -class disk
```

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/cf8ec7c6-60ca-4f6b-abd5-1290d24772d1)


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

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/1f3aad29-7d79-4c70-890a-04b159d2c435)


Result : 

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/c0e35c53-3430-4b33-ab66-be463335caf6)


Attention !
After setting up your node, do not forget to press the validate button on the site!
https://rivalz.ai/dashboard/node-validate

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/30d4d92e-8b2f-46b2-b046-f24e6e05111b)



Rivalz Update ?
I got a message that the client CLI has a new version. How do I update it?

```console
rivalz update-version
```

```console
rivalz run
```

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/a32db3a7-c631-47e8-8388-979f311e093c)


How do I update the client's information ?
```console
rivalz update
```

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/28f97fd2-07f4-478c-b330-f683378f887e)


Other Commands : 
```console
rivalz -h
```

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/9fe1f69c-9ffa-4639-9d49-9a48b47f5e49)


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
# WEB : https://rpcdot.com/
# Services : https://services.rpcdot.com/
# X : https://x.com/rpcdot

![image](https://github.com/RPCdotcom/Rivalz/assets/141464235/b8fdb6a4-0a49-4f7b-9d80-d6c558c0e713)


