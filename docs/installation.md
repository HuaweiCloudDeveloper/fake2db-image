# fake2db部署指南

## ‌一、环境准备

### 一、更新系统

```bash
yum -y update  
yum -y upgrade
```

## ‌二、安装fake2db

```bash
# 安装 Python3 和 pip
sudo yum install -y python3 python3-pip
# 创建项目目录
mkdir -p /opt/fake2db && cd /opt/fake2db

# 创建并激活虚拟环境
python3 -m venv venv
source venv/bin/activate  # 激活虚拟环境

# 安装依赖（解决可能的编译问题）
sudo yum install -y gcc python3-devel

# 安装 FAKE2DB
pip install fake2db

```
