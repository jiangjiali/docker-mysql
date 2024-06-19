# 构建镜像
Mysql v8.0.37

| 镜像名                  | Status        |
| ----------------------- |:-------------:|
| jiangjiali/mysql v8.0.37 | ![CI (Linux)](https://github.com/jiangjiali/docker-mysql/workflows/DockerImageCI/badge.svg) |

## 添加权限
git update-index --chmod=+x docker-entrypoint.sh

## 添加环境变量
* secrets.DOCKER_HUB_USER
* secrets.DOCKER_HUB_PWD