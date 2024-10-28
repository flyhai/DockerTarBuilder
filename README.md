[![GitHub](https://img.shields.io/github/license/wukongdaily/DockerTarBuilder.svg?label=LICENSE&logo=github&logoColor=%20)](https://github.com/wukongdaily/DockerTarBuilder/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/wukongdaily/DockerTarBuilder.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/wukongdaily/DockerTarBuilder.svg?style=flat&logo=appveyor&label=Forks&logo=github)

## 🤔 这是什么？
它是一个工作流。可快速构建指定架构/平台的docker镜像

## 使用说明
https://wkdaily.cpolar.cn/archives/gc
## 使用方法
```bash
解压
# unzip docker-images-tar.zip
Archive:  docker-images-tar.zip
  inflating: x86-64-images.tar.gz    
再解压：
#tar -zxvf x86-64-images.tar.gz
# ls -lh alpine:latest-amd64.tar
-rw------- 1 mysql 127 7.8M 7月   4 16:57 alpine:latest-amd64.tar
​
导入
# docker load < alpine:latest-amd64.tar
​
导入成功。
# docker images
REPOSITORY                                         TAG                 IMAGE ID            CREATED             SIZE
alpine                                             latest              a606584aa9aa        13 days ago         7.8 MB
```
## 教学视频
https://www.bilibili.com/video/BV1EZ421M7mL
## 解压工具
> Windows 上推荐使用7zip<br>
> macOS 推荐使用MacZip<br>
> Linux上推荐直接用tar 命令

## 相关项目
https://github.com/wukongdaily/OrangePiShell
## 在哪里可以搜索或查询docker镜像的详细信息
### [查询镜像的详细信息 点击这里直达](https://docker.fxxk.dedyn.io/)
