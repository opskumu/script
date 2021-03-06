# Docker 知识梳理

## 概览

![Docker Overview](images/Overview.png)

* [Docker 官方文档](https://docs.docker.com/)

## Docker Swarm

### Docker Swarm with TLS

* Docker 官方文档
    * [Overview Swarm with TLS](https://docs.docker.com/swarm/secure-swarm-tls/)
    * [Configure Docker Swarm for TLS](https://docs.docker.com/swarm/configure-tls/)

## Docker 资源限制

* 红帽资源管理官方文档
    * [Resource Management Guide](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/7/html/Resource_Management_Guide/index.html)
* Linux Cgroup
    * [Docker基础技术：Linux CGroup](http://coolshell.cn/articles/17049.html)
        * From [酷壳 CoolShell](http://coolshell.cn)
* Linux NameSpace
    * [Docker基础技术：Linux Namespace（上）](http://coolshell.cn/articles/17010.html)
        * From [酷壳 CoolShell](http://coolshell.cn)
    * [Docker基础技术：Linux Namespace（下）](http://coolshell.cn/articles/17029.html)
        * From [酷壳 CoolShell](http://coolshell.cn)

### 实践操作

* [Docker MEM、CPU、IO 资源限制](resource-limit.md)
* [NET ?]()

## Docker 存储驱动

* Docker 官方文档
    * [Docker and the Device Mapper storage driver](https://docs.docker.com/engine/userguide/storagedriver/device-mapper-driver/)

### 实践操作

* [Docker 使用 Direct LVM devicemapper 设备](direct-lvm-devicemapper.md)
    * issue: 生产环境应该如何监控 container rootfs size ？

## Docker Distribution(Docker Registry V2)

* Docker 官方文档：
    * [Registry as a pull through cache](https://github.com/docker/distribution/blob/master/docs/mirror.md)

## Docker 网络解决方案

* [Flannel]()
* [Contiv]()
