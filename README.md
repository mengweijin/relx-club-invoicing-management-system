# relx-club-invoicing-management-system

#### 介绍
悦享电子烟 RELX Club Invoicing management system

#### 软件架构
软件架构说明


#### 安装教程

1.  安装 docker
    * linux 系统参考https://docs.docker.com docker 安装部分。
    * 如果是windows系统参考：https://docs.docker.com/docker-for-windows/install-windows-home/
    
注意：记得配置国内docker源，否则下载镜像的速度非常慢。
2.  安装 UI：
````
$ docker run --name relx-ui -p 80:80 -d registry.cn-hangzhou.aliyuncs.com/mengweijin/relx-ui:latest
````
3.  安装后台服务：
````
$ docker run --name relx-club-invoicing-management-system -d -p 8081:8081 registry.cn-hangzhou.aliyuncs.com/mengweijin/relx-club-invoicing-management-system:latest
````
4. 访问页面 http://localhost:80

#### 使用说明

1.  xxxx
2.  xxxx
3.  xxxx

#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request


#### 特技

1.  使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2.  Gitee 官方博客 [blog.gitee.com](https://blog.gitee.com)
3.  你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解 Gitee 上的优秀开源项目
4.  [GVP](https://gitee.com/gvp) 全称是 Gitee 最有价值开源项目，是综合评定出的优秀开源项目
5.  Gitee 官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6.  Gitee 封面人物是一档用来展示 Gitee 会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)
