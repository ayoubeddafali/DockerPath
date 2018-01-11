# DOCKER Files Starter 


## RUN : 

`docker run -p 27017:27017 -d --name db mongo`
`docker build -t mean .`
`docker run -p 3000:3000 -p 4200:4200 -p  35729:35729 --name mean --link db:db mean`

