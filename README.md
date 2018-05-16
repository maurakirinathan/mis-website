# Mis website

## Intro

this site is develop for mis student plan to study masters degree from home 

#### dockerized

site is dockerized. we can simply run it with docker

````
docker build --tag site/mis:0.1 .


````
### Run docker
in here ${PWD}:/var/www/html maps current working directory as a volumen to /var/www/html directory. also taking mysql database host as a env variable

````
docker run -p 81:80  site/mis:0.1
````