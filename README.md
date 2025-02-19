# Requirements
you need python3 version 3.7 

check 

```
python3 --version
```

if you dont have 

```
sudo apt update && sudo apt upgrade -y
sudo apt install python3 python3-pip -y
```

you need ```npm,Node.js```

check 

```
node -v
npm -v
```

if you dont have 

```
sudo apt update
sudo apt install nodejs npm -y
```

# Install

```
git clone https://github.com/papa-multi/silent-ping.git
cd silent-ping
```

```
npm install -g pm2
```

Fill your bearer-token at command here 

```
nano tokens.txt
```
   Go the website with ```CTRL+SHIFT+i``` or ```F12``` or click mouse right, see ```inspection```
  Find on web look the captured below Bearer token and copied to input at ``` tokens.txt```


![412257094-29dc0bcc-48cc-410a-bbb7-05f324ff97fd](https://github.com/user-attachments/assets/c12956c1-d2c8-4b50-aca4-2d602d83162f)

# run

```
python3 autoping.py
```


  So, close the logs with command ```CTRL+C```


 ```
pm2 start autoping.py --name silent-bot
```

No need to keep the screen open

![411502157-1782b7bc-cad2-4548-b4ad-89e1f5dc9623](https://github.com/user-attachments/assets/ecbc150d-0c24-4bd1-b521-8f04b75afc50)





# Usefull Command Logs

Status logs

```
pm2 logs silent-bot

```
Status stop/delete

```
pm2 stop silent-bot
```
```
pm2 delete silent-bot
```

Status monitor

```
pm2 monit or list
```



If you need to get notifications, use this bot

@SilentProtocolChecker_bot

