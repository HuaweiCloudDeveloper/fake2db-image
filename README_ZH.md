<p align="center">
  <h1 align="center">fake2db数据生成工具</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍
[fake2db](https://github.com/emirozer/fake2db) 是一种用于生成模拟数据库数据的工具。‌

### **核心功能：**

- **‌多数据库支持：** 
  - 支持 SQLite、MySQL、PostgreSQL、MongoDB、Redis、CouchDB 等多种主流数据库系统‌。‌
  - 通过命令行参数指定数据库类型、连接信息（主机、端口、用户名等）及数据量规模‌。‌
- **数据生成机制：** 
  - 依赖 fake-factory（现名 Faker）库生成逼真的测试数据，如姓名、地址、邮件等‌‌。‌
  - 支持本地化设置（如 --locale cs_CZ 生成捷克语数据）和随机种子（--seed）确保数据可复现‌‌。‌
  - 允许自定义数据列（--custom），满足特定测试场景需求‌。

本项目提供的开源镜像商品 [**fake2db数据生成工具**]() ，已预先安装Neo4j及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。

> **系统要求如下：**
> - CPU: 2GHz 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                      | 特性说明                                           | 备注 |
|-----------------------------------------------------------------------------------------------------------|------------------------------------------------| --- |
| [fake2db-0.5.4-kunpeng](https://github.com/HuaweiCloudDeveloper/fake2db-image/tree/fake2db-0.5.4-kunpeng) | 基于 鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/fake2db-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md
