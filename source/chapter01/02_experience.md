Hyperledger Fabric网络体验
=========================================
### 先决条件
在我们开始之前，如果您还没有这样做，您可能希望检查是否在要开发区块链应用程序和/或运行Hyperledger Fabric的平台上安装了以下所有前提条件。这里采用的是CentOS 7.6

```
[root@VM_0_9_centos ~]#  cat /etc/redhat-release
CentOS Linux release 7.6.1810 (Core)
```

#### 安装Git
如果尚未安装最新版本的git，或者如果您在运行curl命令时遇到问题，请下载它。

>yum install -y git

#### 安装cURL
如果尚未安装cURL工具的最新版本，或者从文档中运行curl命令时遇到错误，请下载它。

>yum install -y curl

#### 安装wget

>yum install -y wget

#### Docker和Docker Compose

您将需要在Hyperledger Fabric上进行操作或进行开发的平台上安装以下组件：

- MacOSX，* nix或Windows 10：Docker需要 Docker 17.06.2-ce或更高版本。
- Windows的旧版本：Docker Toolbox-同样，需要Docker版本Docker 17.06.2-ce或更高。
通过执行docker --version 查看版本
