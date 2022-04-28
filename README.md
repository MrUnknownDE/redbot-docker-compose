# Redbot + Docker = LOVE


Here is a quick guide on how to install Redbot in a few quick steps.

**1. Install Docker and Docker-Compose**
```
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh
curl -SL https://github.com/docker/compose/releases/download/v2.4.1/docker-compose-linux-x86_64 -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
```

**2. Download this Repo or Release** 
`wget https://github.com/MrUnknownDE/redbot-docker-compose/releases/download/v1.0/RedDocker.zip`

**3. Unpacking** 
`unzip v1.0.zip`

**4. Edit docker-compose.yml**
![](https://trash.mrunknown.de/qUcA9/CeRitEza80.png/raw)


**5. Edit the Core.json**
![](https://trash.mrunknown.de/qUcA9/xUkINOYu37.png/raw)
*The bot owner is automatically replaced in the file with the inserted ID in docker-compose.yml.*

**6. Bot start**
`docker-compose up` ~ Can you start the bot for the first time and see if it shows many errors at startup.
`docker-compose up -d` ~ If the bot is started in the background.
`docker-compose down` ~ Stop the bot 

## Troubleshooting
If the bot does not automatically connect to the Lavalink instance, you need to do the following on the Discord server: 
![](https://trash.mrunknown.de/qUcA9/TUqUKumu20.png/raw)