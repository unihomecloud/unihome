# unihome
这是一个集成了诸多开源的家庭云解决方案的项目，旨在提供可一键交付的家庭云产品.

## 安装 docker compose

项目的各组件均通过 docker compose 进行安装。[安装方式](https://github.com/docker/compose)

## 组件清单

- [immich](./components/immich/README.md) : 一款优秀的图片和视频管理软件，拥有手机端 APP 。[官方网站](https://immich.app/)
- [DLNA](./components/dlna/README.md): 简单理解为家庭多媒体，可以将服务器中的视频对外提供流媒体服务，在电视或手机中直接打开
- [迅雷离线下载](./components/xunlei/README.md): 用于在私有服务器上提供离线下载功能，使用迅雷提供的套件
## 安装使用
```
git clone https://github.com/unihomecloud/unihome.git
cd components/immich
docker compose up -d
```

## 关联资源

- [ophub/amlogic-s9xxx-armbian](https://github.com/ophub/amlogic-s9xxx-armbian): 一个提供丰富的 armbian 刷机系统资源的项目
