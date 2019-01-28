# Dev env
Recomend Nodemon.io auto reload
```
npm install -g nodemon
```
Start dev
```
nodemon app.js
```
# Recomendations
Use Postman to verify api urls
Snap Linux store:
```
sudo snap install postman
```

# Deploy 
MongoDB Install
```
sudo apt install curl
```
```
curl https://www.mongodb.org/static/pgp/server-4.0.asc | sudo apt-key add -
```
```
sudo nano /etc/apt/sources.list.d/mongodb-org-4.0.list
```

```
deb http://repo.mongodb.org/apt/debian stretch/mongodb-org/4.0 main
```

```
sudo apt update
sudo apt-get install mongodb-org
```
```
sudo systemctl enable mongod
sudo systemctl start mongod
```