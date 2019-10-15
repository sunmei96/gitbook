# gitbook docker 镜像

为gitbook docker镜像

# 效果图

效果如下图所示  
![](https://image-static.segmentfault.com/252/578/2525787201-5c64218aa520c_articlex)

# 使用说明

## 环境准备

需要docker环境。

## 使用步骤

### 第一种

1. 请先frok本项目
2. frok完成以后，登录主机，输入如下命令，项目拉取下来

```
git
clone
[您的frok项目地址]
;
```

1. 进行本地构建，输入如下代码

```
sudo docker build ./ -t gitbook:vo
```



