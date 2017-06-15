# aerospike 在线实验环境

## 软件简介

软件基本信息，License，所属的类别，作用，特点等。

Aerospike是一个开源的分布式数据库。Aerospike建立在“无共享”架构上，旨在可靠地存储数十亿字节的数据，具有自动故障转移，复制和跨数据中心同步。

所属类别是数据库

License:2014-2015 Aerospike，Inc

## 软件官网

http://www.aerospike.com/

## Dockerfile 使用方法

### 使用
以下将运行asd所有暴露的端口转发到主机。
```
$ docker run -d --name aerospike -p 3000:3000 -p 3001:3001 -p 3002:3002 -p 3003:3003 aerospike/aerospike-server
```
注意虽然这是获取Aerospike的最简单的方法，但并不是首选方法。要正确运行容器，请指定定义的访问地址的自定义配置

## 资源链接

- http://www.aerospike.com/chinese/
- http://blog.csdn.net/dazheng/article/details/47156653
- http://www.aerospike.com/docs/
- https://hub.docker.com/_/aerospike/
