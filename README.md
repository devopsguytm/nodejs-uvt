# nodejs-uvt

a new modification was required 

To  clone this repo :

`git clone https://github.com/bogdanobogeanu/nodejs-uvt.git`

Then change folder to nodejs-uvt:

`cd nodejs-uvt`

To build the nodeJs application with Docker :

`docker build -t mynodejs:1.0.0 .`

To run the nodeJs application with Docker as a daemon :

`docker run --name mynodejs -d -p 8080:8080 -it mynodejs:1.0.0`

To check that application is working :

`curl localhost:8080/nodejs` 

To check the running containers :

`docker ps -a`

To stop the container 

`docker stop mynodejs`

To remove the container 

`docker rm mynodejs`
