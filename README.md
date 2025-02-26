# Scoop Buckets

一个简易的 Scoop 软件包仓库。

## 目录结构

- `bucket/` - 存放所有的软件包定义文件
- `scripts/` - 存放辅助脚本
- `README.md` - 项目说明文件

## 如何使用

1. 安装 [Scoop](https://scoop.sh/)
2. 添加此 bucket 仓库：
    ```sh
    scoop bucket add bai_scoop-buckets https://github.com/lovebai/scoop-buckets
    ```
3. 安装软件包：
    ```sh
    scoop install bai_scoop-buckets/<package-name>
    ```

## 贡献指南

欢迎提交 Pull Request 来贡献新的软件包或改进现有的软件包。请确保遵循以下指南：

1. Fork 此仓库
2. 创建一个新的分支
3. 提交您的更改
4. 创建一个 Pull Request

## 许可证

此项目采用 [Apache License 2.0 许可证](LICENSE)。