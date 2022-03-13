# hellowhale
   
## Build the conatiner 

docker build -t hello-whale .


## Run test the container 

docker run --name hello-whale -p 80:80 -d hello-whale
