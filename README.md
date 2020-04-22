# Active MQ DockerFile

- 이미지 생성
docker build -t acvitemq:5.15.9 ./ 

- docker 컨테이너 실행
docker run -d -p 8161:8161 --name activemq activemq:5.15.9

 

