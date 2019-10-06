# 下载docker镜像

```
dockerFabricPull()函数

docker pull hyperledger/fabric-peer:x86_64-1.1.0
docker pull hyperledger/fabric-orderer:x86_64-1.1.0
docker pull hyperledger/fabric-ccenv:x86_64-1.1.0
docker pull hyperledger/fabric-tools:x86_64-1.1.0

```





```
dockerThirdPartyImagesPull() 函数

拉取三方的镜像 couchdb kafka zookeeper

docker pull hyperledger/fabric-couchdb:x86_64-0.4.6
docker pull hyperledger/fabric-kafka:x86_64-0.4.6
docker pull hyperledger/fabric-zookeeper:x86_64-0.4.6

```





```
dockerCaPull() 函数
拉取的ca的镜像(证书管理中心)
docker pull hyperledger/fabric-ca:x86_64-1.1.0
```



```
sampleInstall() 函数
git clone -b master https://github.com/hyperledger/fabric-samples.git
下载实例代码仓库

```



```
binaryIncrementalDownload() 函数
工具函数, 用来进行下载操作

```



```
binariesInstall() 函数 
下载二进制工具

https://nexus.hyperledger.org/content/repositories/releases/org/hyperledger/fabric/hyperledger-fabric/linux-amd64-1.1.0/hyperledger-fabric-linux-amd64-1.1.0.tar.gz

下载平台CA相关的二进制文件
https://nexus.hyperledger.org/content/repositories/releases/org/hyperledger/fabric-ca/hyperledger-fabric-ca/linux-amd64-1.1.0/hyperledger-fabric-ca-linux-amd64-1.1.0.tar.gz
```



