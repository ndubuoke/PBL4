# PBL4

## Step 1: Install NodeJs
Node.js is a JavaScript runtime built on Chrome’s V8 JavaScript engine. 
Node.js is used in this tutorial to set up the Express routes and AngularJS controllers.

Update Ubuntu
```
sudo apt update
```

Upgrade Ubuntu
```
sudo apt upgrade
```

Add certificates
```
certificates

curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
```
![Screenshot from 2023-03-15 08-44-02](https://user-images.githubusercontent.com/84657461/225240632-83aad40e-1ecb-457e-9db3-513dd3996291.png)

Install NodeJS
```
sudo apt install -y nodejs
```
---
## Step 2: Install MongoDB
MongoDB stores data in flexible, JSON-like documents. Fields in a database can vary from document to document and data structure can be changed over time. For our example application, we are adding book records to MongoDB that contain book name, isbn number, author, and number of pages.
mages/WebConsole.gif
