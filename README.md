# 介绍
这个仓库是为了方便docker部署[polarismesh/polaris-server](https://hub.docker.com/r/polarismesh/polaris-server)
# 注意事项
该镜像是为了方便直接启动polaris-server而无需挂载配置文件以及能够暴露端口给宿主机进行测试，因此改使用的配置文件均拷贝于对应版本的GitHu仓库，未做任何修改。
基于以上，改镜像不应该用于生产环境。

# 已构建的镜像

[DockerHub]([huyuanxin/polaris-server-with-config - Docker Image | Docker Hub](https://hub.docker.com/r/huyuanxin/polaris-server-with-config))