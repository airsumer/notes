/* TODO */
# docker
docker是一种虚拟化技术，其对进程进行==隔离封装==，属于==操作系统层的虚拟化技术==。隔离后的进程既独立于宿主，又独立于其他隔离的进程，而这种隔离的进程就叫做==容器==。
docker的主要结构为：
 ![docker architechture in linuc](https://yeasy.gitbook.io/~gitbook/image?url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fvirtualization%2Fwindowscontainers%2Fdeploy-containers%2Fmedia%2Fdocker-on-linux.png&width=768&dpr=4&quality=100&sign=18c2c53c&sv=2)

在上图中主要需要注意两个部件：
- docker engine：主要用于容器的生命周期管理，包括创建、运行和销毁容器，是宿主操作系统内核与隔离进程之间的桥梁。
- docker compose：docker compose主要用于编排分布式应用，分布式应用往往涉及多个进程，而一个进程对应一个容器，因此docker compose便用于管理这些分布式的进程，
