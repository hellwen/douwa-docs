
# 部署Swarm

豆蛙使用YAML的Pipeline（流程）可以进行简单的[Swarm](https://docs.docker.com/engine/swarm/)部署。

你需要做下列的事情：

1. 一个`docker-stack.yml`文件定义Swarm Stack的部署
1. 运行Docker Swarm的服务器
1. 将Docker Swarm服务器的SSH key添加到豆蛙上


获取SSH_KEY
```
SSH_KEY=$(cat ~/.ssh/my_ssh_key_file | tr '\n' ',')
```
