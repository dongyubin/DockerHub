# DockerHub 国内加速镜像列表

## DockerHub是什么

Docker Hub是 Docker 提供的一项服务，用于与您的团队查找和共享容器映像。 它是世界上最大的容器映像存储库，其中包含一系列内容源，包括容器社区开发人员，开源项目和独立软件供应商（ISV），它们在容器中构建和分发其代码。

![国内DockerHub镜像加速](https://b2.wwkejishe.top/WP-CDN-02/2022/202208041141287.webp)

## DockerHub镜像加速器为啥不能拉取访问了？

6月6日，[上海交大的 Docker Hub 镜像加速器](https://mirrors.ustc.edu.cn/help/dockerhub.html)宣布因监管要求被下架。[具体可看此通知](https://web.archive.org/web/20240606081039/https://sjtug.org/post/mirror-news/2024-06-06-takedown-dockerhub/)

![上海交大通知](https://b2.wwkejishe.top/WP-CDN-02/2024/202406082147076.webp)

## DockerHub国内镜像源列表

此列表只收录无需限定条件的DockerHub镜像源，感谢这些公益服务者。

**2024年10月9日 亲测可用**

| DockerHub镜像仓库                                            | 镜像加速器地址           |
| ------------------------------------------------------------ | ------------------------ |
| [镜像使用说明](https://www.geekery.cn/free-service/docker-hub-mirror.html)： 支持docker命令行账户登录，支持推送到dockerhub账户。 | `https://hub.geekery.cn` |
| [Docker Proxy 镜像加速](https://dockerpull.com/)（[来源地址](https://linux.do/t/topic/114345)） | `https://dockerpull.com`             |
| [镜像加速说明](https://docker.1panel.dev/)                   | `https://docker.1panel.dev`          |
| [Docker Hub Container Image Library](https://docker.fxxk.dedyn.io/) | `https://docker.fxxk.dedyn.io`       |
| [Dockerhub镜像加速说明](https://docker.xn--6oq72ry9d5zx.cn/) | `https://docker.xn--6oq72ry9d5zx.cn` |
| [Dockerhub镜像加速说明](https://docker.zhai.cm/)             | `https://docker.zhai.cm`             |
| [Dockerhub镜像加速说明](https://a.ussh.net/)                 | `https://a.ussh.net`                 |
| [AtomHub 可信镜像仓库平台 ](https://atomhub.openatom.cn/)（只包含基础镜像，共336个） | `https://atomhub.openatom.cn`        |
| [DaoCloud 镜像站](https://github.com/DaoCloud/public-image-mirror) | `https://docker.m.daocloud.io`       |
| 已失效DockerHub镜像仓库                                      |                                      |
| [docker-registry-mirrors](https://github.com/kubesre/docker-registry-mirrors): 支持 Docker Hub, GitHub, Google, k8s, Quay, Microsoft 等镜像仓库. | ~~dhub.kubesre.xyz~~                 |
| ~~[镜像使用说明](https://dislabaiot.xyz/)~~                  | ~~https://dislabaiot.xyz~~           |
| ~~[Dockerhub镜像加速说明](https://docker.wget.at/)~~         | ~~https://docker.wget.at~~           |
| ~~[DockerHub 镜像加速代理](https://docker.anyhub.us.kg/)~~   | ~~https://docker.anyhub.us.kg~~      |
| ~~[DockerHub 镜像加速代理](https://hub.gog.email/)~~         | ~~https://hub.gog.email~~            |
| ~~[镜像使用说明](https://ginger20240704.asia/)~~             | ~~`https://ginger20240704.asia`~~    |
| ~~[镜像使用说明](https://lynn520.xyz/)~~                     | ~~`https://lynn520.xyz`~~            |
| ~~[镜像使用说明](https://docker.mrxn.net/)~~                 | ~~`https://docker.mrxn.net`~~        |
| ~~[镜像使用说明](https://dockerhub.icu/)~~                   | ~~`https://dockerhub.icu`~~          |
|                                                              | ~~`hub.rat.dev`~~                    |
|                                                              | ~~`docker.wanpeng.top`~~             |
| ~~[镜像使用说明](https://doublezonline.cloud/)~~             | ~~`https://doublezonline.cloud`~~    |
| ~~[镜像使用说明](https://docker.awsl9527.cn/)~~              | ~~https://docker.awsl9527.cn~~       |
| ~~[Docker镜像加速站](https://hub.uuuadc.top/)~~（因流量太大，作者已关停） | ~~https://hub.uuuadc.top~~           |
| ~~[Docker镜像加速站](https://docker.ckyl.me/)~~              | ~~https://docker.ckyl.me~~           |
| ~~[镜像使用说明](https://docker.hpcloud.cloud/)~~            | ~~https://docker.hpcloud.cloud~~     |
|                                                              | ~~docker.1panel.live~~               |
|                                                              | ~~https://dockerhub.jobcher.com~~    |
|                                                              | ~~https://docker.chenby.cn~~         |


### 使用教程

1. 为了加速镜像拉取，使用以下命令设置**registry mirror**

> 支持系统：Ubuntu 16.04+、Debian 8+、CentOS 7+

```sh
sudo mkdir -p /etc/docker
sudo tee /etc/docker/daemon.json <<EOF
{
    "registry-mirrors": [
        "https://docker.anyhub.us.kg",
        "https://dockerhub.icu",
        "https://docker.awsl9527.cn"
    ]
}
EOF
sudo systemctl daemon-reload
sudo systemctl restart docker
```

2. 使用DockerHub Proxy，以下以 `hub.uuuadc.top` 为例：可以根据列表自行替换

```sh
docker pull hub.uuuadc.top/library/mysql:5.7
```

说明：library是一个特殊的命名空间，它代表的是官方镜像。如果是某个用户的镜像就把library替换为镜像的用户名

## 国内DockerHub镜像加速器还有哪些？

- [国内的 Docker Hub 镜像加速器](https://gist.github.com/y0ngb1n/7e8f16af3242c7815e7ca2f0833d3ea6?permalink_comment_id=5068535)：由国内教育机构与各大云服务商提供的镜像加速服务

- [建木Hub-镜像库](https://image.jianmuhub.com/)：v2友建立的服务，需要注册登录后使用

- [镜像加速说明](https://do.nark.eu.org/)：由Linux.do [青柠](https://linux.do/u/qning/summary) 制作 [都在蹭CF搭建dockerhub镜像代理，基于论坛看到的一个代码糊了个前端](https://linux.do/t/topic/107726/8)

- Docker Hub：`https://docker.hlyun.org`
  npm：`https://npm.hlyun.org`
  Github：`https://github.hlyun.org`
  来源 [npm、docker hub、Github镜像](https://linux.do/t/topic/108473) 
  
- DockerHub：`https://dockerhub.icu`    来源：[镜像使用说明](https://dockerhub.icu/)

- 其他

    ```sh
    gcr.io   >>>>>   gcr.chenby.cn
    quay.io   >>>>>   quay.chenby.cn
    ghcr.io   >>>>>   ghcr.chenby.cn
    docker.io   >>>>>   docker.chenby.cn
    k8s.gcr.io   >>>>>   k8s.chenby.cn
    registry.k8s.io   >>>>>   k8s.chenby.cn
    ```

## 如何自建DockerHub

### 部署在CloudFlare上的服务

- [自建Docker Hub加速镜像](https://blog.lty520.faith/%E5%8D%9A%E6%96%87/%E8%87%AA%E5%BB%BAdocker-hub%E5%8A%A0%E9%80%9F%E9%95%9C%E5%83%8F/#%e6%96%b9%e6%a1%88%e4%b8%80%e4%ba%8c%e6%95%b4%e5%90%88)：通过 Nginx 和 Cloudflare Worker 两种方案以及两种方案的组合方案自建Docker hub加速镜像来解决这个问题
- [利用 Cloudflare Workers 自建 Docker 镜像](https://singee.atlassian.net/wiki/spaces/MAIN/pages/5079084/Cloudflare+Workers+Docker)
- [cmliu/CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io): 这个项目是一个基于 Cloudflare Workers 的 Docker 镜像代理工具。它能够中转对 Docker 官方镜像仓库的请求，解决一些访问限制和加速访问的问题。
- [ciiiii/cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy):docker 注册表代理在 cloudflare Worker 上运行。

### 其他

- [NoCLin/LightMirrors](https://github.com/NoCLin/LightMirrors) 是一个开源的缓存镜像站服务，用于加速软件包下载和镜像拉取。 目前支持**DockerHub**、PyPI、PyTorch、NPM等镜像缓存服务。 当前项目仍处于早期阶段。
- [自建Docker Hub镜像服务](https://www.yooo.ltd/2024/06/08/self-host-docker-hub-mirror/)：文本使用[CNCF Distribution](https://distribution.github.io/distribution)的registry项目，只需要运行一个Docker容器，就可以自建Docker Hub镜像服务。
- [brighill/registry-mirror](https://github.com/brighill/registry-mirror)：: 自建简易Docker镜像加速&缓存服务（gcr.io、quay.io、nvcr.io、docker.io）
- [bboysoulcn/registry-mirror](https://github.com/bboysoulcn/registry-mirror)：包含Dockerhub、gcr、ghcr、k8sgcr、quay、registryk8s
- [kubesre/docker-registry-mirrors](https://github.com/kubesre/docker-registry-mirrors)：多平台容器镜像代理服务,支持 Docker Hub, GitHub, Google, k8s, Quay, Microsoft 等镜像仓库.
