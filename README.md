# shiny-server BIBBOX application

This container can be installed as [BIBBOX APP](https://bibbox.readthedocs.io/en/latest/ "BIBBOX App Store") or standalone. 

After the docker installation follow these [instructions](INSTALL-APP.md).

## Standalone Installation 

Clone the github repository. If necessary change the ports in the environment file `.env` and the volume mounts in `docker-compose.yml`.

```
git clone https://github.com/bibbox/app-shiny-server
cd app-shiny-server
docker network create bibbox-default-network
docker-compose up -d
```

The main App can be opened and set up at:
```
http://localhost:3838
```

## Install within BIBBOX

Visit the BIBBOX page and find the App by its name in the store. Click on the symbol and select install. Then fill the parameters below and name your App, click install again.

## Docker Images used
  - [rocker/shiny](https://hub.docker.com/r/rocker/shiny) 


 
## Install Environment Variables

  
The default values for the standalone installation are:

  
## Mounted Volumes
### rocker/shiny Conatiner
  - *./data/shinyapps/:/srv/shiny-server/*
  - *./data/shinylog/:/var/log/shiny-server/*

