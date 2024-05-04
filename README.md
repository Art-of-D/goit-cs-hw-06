## Python website to send messages to MongoDB

It will create compose container on your computer by Docker and you will get access to your website by http://localhost/ or http://localhost:80

---

### To start

1. Download archive and unzip it.
2. Navigate to new folder in terminal or other CLI
3. Use next command ~ docker compose up -d
4. After start you will get something like that:

```
   [+] Running 3/3
   ⠿ Network goit-cs-hw-06_default Created 0.0s
   ⠿ Container goit-cs-hw-06-mongodb-1 Healthy 5.9s
   ⠿ Container goit-cs-hw-06-app-1 Started
```

5. Go in your browser to http://localhost/ or http://localhost:80

### Routes

It has only 3 paths:

- / - main page
- /error - 404 page
- /message - page with possibility to sent message to db

### For this project you need to do:

- install Docker
- your CLI
- your Web browser
