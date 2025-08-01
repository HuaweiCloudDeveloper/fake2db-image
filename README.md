<p align="center">
  <h1 align="center">fake2db Data Generation Tool</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>

## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction
[fake2db](https://github.com/emirozer/fake2db) is a tool for generating mock database data.

### **Core Features:**

- **Multi-database Support:**
    - Supports various mainstream database systems such as SQLite, MySQL, PostgreSQL, MongoDB, Redis, CouchDB, etc.
    - Specify database type, connection information (host, port, username, etc.) and data volume through command-line parameters.
- **Data Generation Mechanism:**
    - Relies on the fake-factory (now named Faker) library to generate realistic test data, such as names, addresses, emails, etc.
    - Supports localization settings (e.g., --locale cs_CZ to generate Czech data) and random seeds (--seed) to ensure data reproducibility.
    - Allows custom data columns (--custom) to meet specific testing scenario requirements.

The open-source image product [**fake2db Data Generation Tool**]() provided by this project has pre-installed Neo4j and its related operating environment, and offers deployment templates. Follow the user guide to easily start an "out-of-the-box" efficient experience.

> **System Requirements:**
> - CPU: 2GHz or higher
> - RAM: 4GB or larger
> - Disk: At least 40GB

## Prerequisites
[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                       | Feature Description                                      | Remarks |
|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------|---------|
| [fake2db-1.0.0-kunpeng](https://github.com/HuaweiCloudDeveloper/fake2db-image/tree/fake2db-1.0.0-kunpeng) | Installed and deployed based on Kunpeng server + Huawei Cloud EulerOS 2.0 64bit |         |

## Get Help
- For more questions, you can contact us through [issue](https://github.com/HuaweiCloudDeveloper/fake2db-image/issues) or the service support of the designated product in the Huawei Cloud Market.
- Other open-source images can be found in [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## How to Contribute
- Fork this repository and submit a pull request
- Synchronously update README.md based on your open-source image information