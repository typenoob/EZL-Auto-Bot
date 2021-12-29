# E浙理自动健康申报（新版）

**！请填写登录sso的学号和密码，不能是手机号。**

2021/12/29更新：基于docker构建，简化流程。

## 快速开始

### 自己构建镜像 

```
git clone https://www.github.com/typenoob/EZL-Auto-Bot
docker build -t zstu .
docker run -d --name zstu --restart=always -p 5000:5000 zstu
```

### 使用我上传的镜像

```
docker run -d --name zstu --restart=always -p 5000:5000 typenoob/zstu
```

