## clone the projetc

git clone

## set DB URL in environment
insert your DBURL in variable on the file variables.env

## start serverless offline 
    sls offline start --skipCacheInvalidation

try insert some note using POST request in   [![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=Serverless%20%2B%20MongoDB&uri=https%3A%2F%2Fgithub.com%2FDaniiloLacerda%2FserverlessWithMongoExample%2Fblob%2Fmaster%2FInsomnia.json)

## deploy serverless
    sls deploy
