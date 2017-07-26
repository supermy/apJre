
2017-07-26

docker build -t supermy/ap-jre  jre
docker build -t supermy/ap-jre8  -f jre/Dockerfile1.8 jre 

2016-03-18
docker run -it --rm supermy/ap-jre java -version