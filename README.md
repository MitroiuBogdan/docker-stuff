#docker commands:

docker run -starts a containter
docker run -p XXXX:XXXX -assign ports and start a container
docker images -shows images
docker ps -a -shows contatiners
docker ps -shows containters that is running
docker rm -remove a container
docker rmi -remove an image
docker run -p 7000:3000 -v ${PWD}:/var/www -w '/var/www' node npm start 
