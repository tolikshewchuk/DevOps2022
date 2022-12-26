Results
---
#### Firstly, I developed Dockerfile. For the base image, used Alpine Linux.
![im1](https://github.com/tolikshewchuk/DevOps2022/blob/main/Docker/images/1.png)

#### Index.html file, which will replace the basic one.
![im2](https://github.com/tolikshewchuk/DevOps2022/blob/main/Docker/images/2.png)

#### Then? I build it? using command
```
docker build Docker/ -t webserver:v1
```
#### Runed it, by command:
```
docker run -d --name MyServ -P webserver:v1
```
#### And then found out which port my server uses, by command:
```
docker ps
```
![im3](https://github.com/tolikshewchuk/DevOps2022/blob/main/Docker/images/3.png)

#### Further, went to the server using the port and IP-address, and checked its availability

![im4](https://github.com/tolikshewchuk/DevOps2022/blob/main/Docker/images/4.png)
