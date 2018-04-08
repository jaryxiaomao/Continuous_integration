# Continuous_integration
>介绍几种主要的代码管理，自动打包上传服务器等一系列持续化所需要的工具

# gitlab git的使用

> git是一种代码版本管理工具，利用git可以对服务器中的项目代码进行上传，下载，修改和打标签等一系列的管理，git的相关的教程可以参考[git初步了解](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)<br>
全面了解git的使用请点击这里[git详细教程](https://git-scm.com/book/zh/v2)，有的项目中可能包含子项目或者其他子模块，git子模块能够有效的解决这个问题[子模块](https://segmentfault.com/a/1190000003076028)<br>

gitlab是服务器上控制代码权限用的，利用gitlab进行分布式开发的权限管理提高项目代码安全性[权限管理示例](http://blog.51cto.com/sgk2011/1925922)，一般安装在公司私服上，gitlab其他使用小技巧[gitlab小技巧](https://www.jianshu.com/p/2bd89bcf9995)<br>

# maven nexus使用

>maven能够根据pom文件对相关的maven项目进行包的自动引进，并对项目进行打包，自动测试，创建报表等其他管理maven的安装和各个目录作用[maven安装和目录结构](https://blog.csdn.net/camiiqqo/article/details/55096592)<br>
maven的生命周期[点击](https://www.cnblogs.com/EasonJim/p/6816340.html)<br>

nexus是maven引用三方库使用的一种仓库管理服务器，该服务器为局域网中的特殊远程仓库，利用该服务器能够稳定构建减少带宽，部署第三方组件等等[nexus搭建](https://blog.csdn.net/fygkchina/article/details/62976387)<br>
nexus对仓库也进行了权限的管理，只有获取相关仓库权限的用户才能上传三方包和修改仓库配置等管理[权限管理和调度任务](https://blog.csdn.net/crave_shy/article/details/41015355)<br>


# jenkins 介绍

>jenkins 通俗讲是一种工具，这种工具将项目的开发，打包发布到部署到服务器上的容器等一系列操作进行的集成，只需要点击或者设定定时任务就能够自动完成从项目的上传测试，部署等操作，jenkins的插件可以实现部署到容器，上传到服务器等操作<br>
[Deploy to container Plugin插件](https://blog.csdn.net/houyefeng/article/details/50996198)jenkins的集成的例子 [publish over ssh插件](https://www.cnblogs.com/lidong94/p/7427923.html)<br>

# tomcat jboss容器


