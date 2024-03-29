# Docker Development Environment

一个个人使用的 Docker 开发环境，目前包含：

* MySQL 8.0.34
* Redis 7.2.0
* Nexus 3.62.0

## MySQL

* username: `root`
* password: `root`

## Redis

* port: 6379

## Nexus

* port: 8081

## Nginx Proxy Manager

端口：

* 80
* 81
* 443

## MinIO

* 9000
* 9090

## Gitea

* 3000
* 222

## WordPress

## YouTrack

 端口：`8080`
 
 需要将 `youtrack` 目录授权：

 ```shell
chown -R 13001:13001 <path to youtrack directory>
 ```

 ## Dozzle

 > Dozzle 是一款开源的 Docker 日志查看工具，它提供了一个简单而直观的 Web 界面，可以方便地查看运行中的 Docker 容器的实时日志。轻量、快速、易用，不需要对 Docker 容器进行任何配置或修改。

端口: `8080`

## Dockge

> Dockge 是一个款开源的 Docker Compose 图形化管理工具

端口: `5001`
