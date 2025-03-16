# IPV - IP地址管理工具

IPV是一个强大的IP地址管理工具，旨在帮助网络管理员和开发人员更好地管理和监控IP地址资源。

## 功能特点

- IP地址池管理
- 子网划分与计算
- IP地址使用状态监控
- IP地址分配历史记录
- 支持IPv4和IPv6
- 多用户权限管理
- RESTful API支持
- 可视化报表

## 快速开始

### 安装要求

- Python 3.8+
- PostgreSQL 12+
- Redis 6+

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/jxpony/IPV.git
cd IPV
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置数据库
```bash
cp config.example.yml config.yml
# 编辑 config.yml 文件，配置数据库连接信息
```

4. 运行应用
```bash
python manage.py runserver
```

## 文档

详细文档请访问 [Wiki](https://github.com/jxpony/IPV/wiki)

## 贡献指南

我们欢迎任何形式的贡献，包括但不限于：

- 提交问题和建议
- 改进文档
- 提交代码修复
- 添加新功能

请查看 [CONTRIBUTING.md](CONTRIBUTING.md) 了解更多信息。

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情。

## 联系方式

- 提交Issue: https://github.com/jxpony/IPV/issues
- 邮件联系: your-email@example.com

## 致谢

感谢所有为本项目做出贡献的开发者。