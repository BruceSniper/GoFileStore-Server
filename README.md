# 基于golang实现的一种分布式云存储服务
![GitHub last commit](https://img.shields.io/github/last-commit/brucesniper/GoFileStore-Server)
## 技术栈
* Golang
* Redis
* Mysql
* RabbitMQ
* Ceph
* gRPC
* k8s
* 阿里云OSS

## 关于需要手动安装的库

```
go get github.com/garyburd/redigo/redis
go get github.com/go-sql-driver/mysql
go get github.com/garyburd/redigo/redis
go get github.com/json-iterator/go
go get github.com/aliyun/aliyun-oss-go-sdk/oss
go get gopkg.in/amz.v1/aws
go get gopkg.in/amz.v1/s3
go get github.com/streadway/amqp
```