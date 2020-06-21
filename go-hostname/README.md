# GO-HOSTNAME #

This Go project for practice AWS Cloudformation and will be built in Docker image for storing in Amazon Elastic Container Registry (ECR)

## Setup

* Setup Golang <https://golang.org/>
* Setup Docker <https://www.docker.io/>
* Setup Account in Amazon Web Services <https://aws.amazon.com/>

## Build Image
Make image :
```
$ docker build -t momo89/go-hostname .
```

## Push to Docker Hub
Login to Docker :
```
$ docker login
```
Push to Docker Hub :
```
$ docker push momo89/go-hostname:latest
```

## Note
momo89 is my account, please change the account if you want to use your own


## License

MIT