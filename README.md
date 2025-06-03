# DockerHub 国内加速镜像列表

[国内可用Docker镜像源加速器/DockerHub镜像汇总](https://www.wangdu.site/course/2109.html)（博客版及时更新）

## DockerHub是什么

Docker Hub是 Docker 提供的一项服务，用于与您的团队查找和共享容器映像。 它是世界上最大的容器映像存储库，其中包含一系列内容源，包括容器社区开发人员，开源项目和独立软件供应商（ISV），它们在容器中构建和分发其代码。

![国内DockerHub镜像加速](https://b2.wwkejishe.top/WP-CDN-02/2022/202208041141287.webp)

## DockerHub镜像加速器为啥不能拉取访问了？

6月6日，[上海交大的 Docker Hub 镜像加速器](https://mirrors.ustc.edu.cn/help/dockerhub.html)宣布因监管要求被下架。[具体可看此通知](https://web.archive.org/web/20240606081039/https://sjtug.org/post/mirror-news/2024-06-06-takedown-dockerhub/)

![上海交大通知](https://b2.wwkejishe.top/WP-CDN-02/2024/202406082147076.webp)

## Dockerhub官网

官方网站：[https://hub.docker.com/](https://hub.docker.com/)

## DockerHub国内镜像加速源列表

国内使用 Docker 的朋友们，可能都遇到过配置镜像源来加速镜像拉取的操作。然而，最近几个月发现许多曾经常用的国内镜像站（包括各种云服务商和高校镜像站）已经无法使用。

此列表只收录目前可用的 DockerHub 镜像站和镜像加速地址，感谢这些公益服务者。

> 请注意！有些镜像站仅提供基础镜像或白名单镜像，如果某个加速地址无法拉取到所需的镜像，可以尝试切换到其他地址。有些代理站点是热心网友自费搭建的，请务必合理使用。

**2025年6月3日 亲测国内现在还能用的 Docker 镜像**

| DockerHub镜像仓库                                            | 镜像加速器地址                            |
| ------------------------------------------------------------ | ----------------------------------------- |
|                                                              | `https://docker.1panel.live/`             |
| [毫秒镜像](https://1ms.run/)                                 | `docker.1ms.run`                          |
| [Docker Hub Search](https://docker.mybacc.com/)              | `docker.mybacc.com`                       |
| [Docker Hub Search](https://dytt.online/)                    | `https://dytt.online`                     |
| [Docker Hub Search](https://lispy.org/)                      | `https://lispy.org`                       |
| [Docker Hub Search](https://docker.xiaogenban1993.com/)      | `docker.xiaogenban1993.com`               |
| [Docker Hub Search](https://docker.yomansunter.com/)         | `docker.yomansunter.com`                  |
| [Docker Hub Search](https://aicarbon.xyz/)                   | `aicarbon.xyz`                            |
| [Docker Hub Search](https://666860.xyz/)                     | `666860.xyz`                              |
| [Dockerhub镜像加速说明](https://a.ussh.net/)                 | `https://a.ussh.net`                      |
|                                                              | `hub.littlediary.cn`                      |
|                                                              | `hub.rat.dev`                             |
| [DaoCloud 镜像站](https://github.com/DaoCloud/public-image-mirror) | `https://docker.m.daocloud.io`            |
| [Docker Proxy 镜像加速](https://dockerproxy.net/)            | `dockerproxy.net`                         |
| [xdark.top](https://xdark.top/)（需赞助拉取）                |                                           |
| [腾讯云](https://cloud.tencent.com/document/product/457/9113)（只支持内网访问，不支持外网域名访问加速。[轻量应用服务器 安装 Docker 并配置镜像加速源](https://cloud.tencent.com/document/product/1207/45596)） | `https://mirror.ccs.tencentyun.com`       |
| [阿里云](https://cr.console.aliyun.com/)（需登录，系统分配） | `https://<your_code>.mirror.aliyuncs.com` |

### 已失效DockerHub加速镜像仓库

| DockerHub镜像仓库                                            | 镜像加速器地址                                               |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [docker-registry-mirrors](https://github.com/kubesre/docker-registry-mirrors): 支持 Docker Hub, GitHub, Google, k8s, Quay, Microsoft 等镜像仓库. | ~~dhub.kubesre.xyz~~                                         |
| [Docker Proxy 镜像加速](https://dockerpull.org/)（[来源地址](https://linux.do/t/topic/114345)） | ~~`https://dockerpull.org`（在12/27被GFW封锁）/ `cjie.eu.org`（暂时备用）~~ |
| ~~[镜像使用说明](https://dislabaiot.xyz/)~~                  | ~~https://dislabaiot.xyz~~                                   |
| ~~[镜像加速说明](https://docker.1panel.dev/)~~               | ~~https://docker.1panel.dev~~                                |
| ~~[镜像加速说明](https://docker.foreverlink.love/)~~         | ~~https://docker.foreverlink.love~~                          |
| ~~[Dockerhub镜像加速说明](https://docker.wget.at/)~~         | ~~https://docker.wget.at~~                                   |
| ~~[DockerHub 镜像加速代理](https://docker.anyhub.us.kg/)~~   | ~~https://docker.anyhub.us.kg~~                              |
| ~~[DockerHub 镜像加速代理](https://hub.gog.email/)~~         | ~~https://hub.gog.email~~                                    |
| ~~[Dockerhub镜像加速说明](https://docker.5z5f.com/)~~        | ~~https://docker.5z5f.com~~                                  |
| ~~[Dockerhub镜像加速说明](https://docker.xn--6oq72ry9d5zx.cn/)~~ | ~~https://docker.xn--6oq72ry9d5zx.cn~~                       |
| ~~[Docker Layer ICU 镜像加速](https://cloudlayer.icu/)~~     | ~~https://docker.cloudlayer.icu~~                            |
| ~~[镜像使用说明](https://ginger20240704.asia/)~~             | ~~`https://ginger20240704.asia`~~                            |
| ~~[镜像使用说明](https://lynn520.xyz/)~~                     | ~~`https://lynn520.xyz`~~                                    |
| ~~[镜像使用说明](https://docker.mrxn.net/)~~                 | ~~`https://docker.mrxn.net`~~                                |
| ~~[镜像使用说明](https://dockerhub.icu/)~~                   | ~~`https://dockerhub.icu`~~                                  |
|                                                              | ~~`hub.rat.dev`~~                                            |
|                                                              | ~~hub.crdz.gq~~                                              |
|                                                              | ~~docker.unsee.tech~~                                        |
|                                                              | ~~registry.dockermirror.com~~                                |
|                                                              | ~~`docker.wanpeng.top`~~                                     |
| ~~[镜像使用说明](https://doublezonline.cloud/)~~             | ~~`https://doublezonline.cloud`~~                            |
| ~~[镜像使用说明](https://docker.awsl9527.cn/)~~              | ~~https://docker.awsl9527.cn~~                               |
| ~~[Docker镜像加速站](https://hub.uuuadc.top/)~~（因流量太大，作者已关停） | ~~https://hub.uuuadc.top~~                                   |
| ~~[Docker镜像加速站](https://docker.ckyl.me/)~~              | ~~https://docker.ckyl.me~~                                   |
| ~~[镜像使用说明](https://docker.hpcloud.cloud/)~~            | ~~https://docker.hpcloud.cloud~~                             |
|                                                              | ~~docker.1panel.live~~                                       |
|                                                              | ~~https://dockerhub.jobcher.com~~                            |
|                                                              | ~~https://docker.chenby.cn~~                                 |
|                                                              | ~~https://vipmall.store/~~                                   |
|                                                              | ~~https://tzq.asia~~                                         |
|                                                              | ~~https://leitong.top/~~                                     |
|                                                              | ~~hub.xdark.top~~                                            |
|                                                              | ~~docker.nastool.de~~                                        |
|                                                              | ~~docker.udayun.com~~                                        |
| ~~[Docker Hub Search](https://docker.bowen.games/)~~         |                                                              |
| ~~[Docker Hub Search](https://futureperiod.icu/)~~           |                                                              |
| ~~[AtomHub 可信镜像仓库平台 ](https://atomhub.openatom.cn/)（~~只包含基础镜像，共336个，已于2024年12月30日下线） | ~~`https://atomhub.openatom.cn`~~                            |
| ~~[Docker Hub Container Image Library](https://docker.fxxk.dedyn.io/)~~ | ~~`https://docker.fxxk.dedyn.io`~~                           |
| [镜像使用说明](https://www.geekery.cn/free-service/docker-hub-mirror.html)： 支持docker命令行账户登录，支持推送到dockerhub账户。 | ~~`https://hub.geekery.cn`~~                                 |
| [链氪镜像-链氪网公益Docker镜像站-Docker-DockerHub国内镜像源加速｜链氪巴士](https://docker.linkedbus.com/) | ~~https://docker.linkedbus.com~~                             |
|                                                              | ~~docker.rainbond.cc~~                                       |
|                                                              | ~~docker.1panelproxy.com~~                                   |
|                                                              | ~~docker.kejilion.pro~~                                      |
| ~~[Docker Hub Search](https://func.ink/)~~                   | ~~https://func.ink~~                                         |
| ~~[Docker Hub Search](https://dockerhub.websoft9.com/)~~     | ~~dockerhub.websoft9.com~~                                   |
| ~~[Dockerhub镜像加速说明](https://docker.zhai.cm/)~~         | ~~https://docker.zhai.cm~~                                   |

### 配置Dockerhub镜像源使用教程

1. 为了加速镜像拉取，使用以下命令设置 **registry mirror**

> 支持系统：Ubuntu 16.04+、Debian 8+、CentOS 7+

```sh
sudo mkdir -p /etc/docker
sudo tee /etc/docker/daemon.json <<EOF
{
  "registry-mirrors": [
    "https://docker.1panel.live",
    "https://docker.1ms.run",
    "https://docker.mybacc.com",
    "https://dytt.online",
    "https://lispy.org",
    "https://docker.xiaogenban1993.com",
    "https://docker.yomansunter.com",
    "https://aicarbon.xyz",
    "https://666860.xyz",
    "https://a.ussh.net",
    "https://hub.littlediary.cn",
    "https://hub.rat.dev",
    "https://docker.m.daocloud.io"
  ]
}
EOF
sudo systemctl daemon-reload
sudo systemctl restart docker
```

2. 使用 DockerHub Proxy，以下以 `hub.uuuadc.top` 为例：可以根据列表自行替换来测试是否拉取成功

```sh
docker pull hub.uuuadc.top/library/mysql:5.7
```

说明：library是一个特殊的命名空间，它代表的是官方镜像。如果是某个用户的镜像就把library替换为镜像的用户名

或用以下命令检查是否生效：

```shell
ping -c 3 dockerpull.org
```

![Dockerhub加速源命令检查效果图](https://cdn.wwkejishe.top/wp-cdn-02/2024/202411071046451.png)

## DockerHub containerd的配置文件

由网友 [rxzy-krli](https://github.com/rxzy-krli) 提供

```sh
sudo tee /etc/containerd/config.toml <<EOF
[plugins."io.containerd.grpc.v1.cri".registry]
  [plugins."io.containerd.grpc.v1.cri".registry.mirrors]
    [plugins."io.containerd.grpc.v1.cri".registry.mirrors."docker.io"]
      endpoint = [
        "https://docker.1panel.live",
        "https://docker.1ms.run",
        "https://docker.mybacc.com",
        "https://dytt.online",
        "https://lispy.org",
        "https://docker.xiaogenban1993.com",
        "https://docker.yomansunter.com",
        "https://aicarbon.xyz",
        "https://666860.xyz",
        "https://a.ussh.net",
        "https://hub.littlediary.cn",
        "https://hub.rat.dev",
        "https://docker.m.daocloud.io"
      ]
EOF
sudo systemctl daemon-reload
sudo systemctl restart containerd
```


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

## Docker daemon 配置代理

- 参考 [Docker daemon 配置代理](https://docs.docker.com/config/daemon/systemd/#httphttps-proxy)
- [docker 设置代理，以及国内加速镜像设置](https://neucrack.com/p/286)：国内 Docker 代理来实现加速下载，docker pull 使用 http proxy

## 如何自建 DockerHub 加速服务

### 部署在CloudFlare上的Dockerhub加速服务

- [自建Docker Hub加速镜像](https://blog.lty520.faith/%E5%8D%9A%E6%96%87/%E8%87%AA%E5%BB%BAdocker-hub%E5%8A%A0%E9%80%9F%E9%95%9C%E5%83%8F/#%e6%96%b9%e6%a1%88%e4%b8%80%e4%ba%8c%e6%95%b4%e5%90%88)：通过 Nginx 和 Cloudflare Worker 两种方案以及两种方案的组合方案自建Docker hub加速镜像来解决这个问题
- [利用 Cloudflare Workers 自建 Docker 镜像](https://singee.atlassian.net/wiki/spaces/MAIN/pages/5079084/Cloudflare+Workers+Docker)
- [cmliu/CF-Workers-docker.io](https://github.com/cmliu/CF-Workers-docker.io): 这个项目是一个基于 Cloudflare Workers 的 Docker 镜像代理工具。它能够中转对 Docker 官方镜像仓库的请求，解决一些访问限制和加速访问的问题。
- [ciiiii/cloudflare-docker-proxy](https://github.com/ciiiii/cloudflare-docker-proxy):docker 注册表代理在 cloudflare Worker 上运行。

### 其他

- [NoCLin/LightMirrors](https://github.com/NoCLin/LightMirrors) 是一个开源的缓存镜像站服务，用于加速软件包下载和镜像拉取。 目前支持 **DockerHub**、PyPI、PyTorch、NPM 等镜像缓存服务。 当前项目仍处于早期阶段。

- [自建Docker Hub镜像服务](https://www.yooo.ltd/2024/06/08/self-host-docker-hub-mirror/)：文本使用[CNCF Distribution](https://distribution.github.io/distribution)的registry项目，只需要运行一个Docker容器，就可以自建Docker Hub镜像服务。

- [brighill/registry-mirror](https://github.com/brighill/registry-mirror)：: 自建简易 Docker 镜像加速&缓存服务（gcr.io、quay.io、nvcr.io、docker.io）

- [bboysoulcn/registry-mirror](https://github.com/bboysoulcn/registry-mirror)：包含 Dockerhub、gcr、ghcr、k8sgcr、quay、registryk8s

- [kubesre/docker-registry-mirrors](https://github.com/kubesre/docker-registry-mirrors)：多平台容器镜像代理服务,支持Docker Hub, GitHub, Google, k8s, Quay, Microsoft 等镜像仓库.

- [dockerhub2ghcr.io](https://github.com/foss-android/dockerhub2ghcr.io)：一键把 DockerHub 镜像搬运到 GitHub 容器注册表 (GHCR.IO)

- [dqzboy/Docker-Proxy](https://github.com/dqzboy/Docker-Proxy)：自建Docker镜像加速服务，基于官方Docker Registry 一键部署Docker、K8s、Quay、Ghcr、Mcr、Nvcr等镜像加速\管理服务。支持免服务器部署到Render\Koyeb

  > 提示
  >
  > 选择一台[国外服务器](https://bestvps.wwkejishe.top/tutorial-vps/choose-vps)（比如：[RackNerd](https://www.wangdu.site/fuliyouhui/1266.html)），并且未被墙。对于域名，无需进行国内备案。你也可以通过一些平台申请免费域名。在一键部署过程中，如果选择安装Caddy，它将自动配置HTTPS。若选择部署Nginx服务，则需要自行申请一个免费的SSL证书，或者通过其他方式来实现SSL加密。
  
- [KSpeeder | Docker镜像加速专家](https://kspeeder.istoreos.com/)：多镜像并发下载，动态负载均衡，断点续传支持，Docker镜像代理服务

  - 支持HTTPS协议
  - 自动配置Docker镜像源
  - 证书自动获取和缓存
  - 多架构支持(AMD64/ARM64/ARM)
  - 智能镜像选择和自动切换
  - 实时下载速度监控
  - 可视化状态监控界面
  - **Docker Compose支持**：使用compose文件轻松部署
  - **数据持久化**：可配置的卷挂载
  - **自定义配置**：适应不同环境的灵活设置


## Nas 群辉 Docker pull 代理设置方法

设备：黑群晖7.0.1
编辑文件：`vi /usr/local/lib/systemd/system/pkg-Docker-dockerd.service`，在 service下面新增三行环境变量，**代理地址记得改成自己的**  （来源：[【分享】群辉Docker pull代理设置方法](https://linux.do/t/topic/109710)）

```sh
[Service]
Environment="HTTP_PROXY=http://127.0.0.1:1080"
Environment="HTTPS_PROXY=http://127.0.0.1:1080"
Environment="NO_PROXY=localhost,127.0.0.0/8,192.168.0.0/16,172.16.0.0/12,10.0.0.0/8"
```

## Dockerhub使用常见问题

### hub.docker.com 无法访问，如何查看镜像信息

此处以 library/mysql 为例，使用 `DockerHub国内镜像加速源列表` 里的 Docker Hub Search 搜索镜像即可，或者直接替换 `https://hub.docker.com` 为你所用的代理地址。

```
# 官方地址
https://hub.docker.com/_/mysql
# 替代后地址
https://docker.mybacc.com/_/mysql
```


## 博主推荐仓库

<a href="https://github.com/dongyubin/Free-AppleId-Serve">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=dongyubin&repo=Free-AppleId-Serve" />
</a>

## Star History

![dongyubin/DockerHub](https://api.star-history.com/svg?repos=dongyubin/DockerHub&type=Date)
