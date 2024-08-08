# MinIO Client Quickstart Guide

## 源码适配
  该项目与架构无关，不需要适配

## 编译
  golang使用1.21版本
  编译命令
  ```
   make build
  ```

## rpm包制作
使用spec见src.rpm
  ```
  https://github.com/Loongson-Cloud-Community/mc/releases/download/untagged-c79ae86bb2c97de123bc/minio-client-20201218T105353Z-1.1.src.rpm
  ```
## 执行rpm包构建命令
  ```  
   rpmbuild -ba --nodebuginfo  minio-client.spec
  ```
