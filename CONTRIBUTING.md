# 贡献指南

感谢您对IPV项目的关注！我们非常欢迎社区成员的贡献。本文档将指导您如何参与项目开发。

## 如何贡献

### 1. 提交Issue

- 在提交Issue之前，请先搜索是否已经存在相似的Issue
- 使用清晰的标题和详细的描述
- 如果是bug报告，请提供：
  - 问题的详细描述
  - 复现步骤
  - 期望的行为
  - 实际的行为
  - 系统环境信息

### 2. 提交Pull Request

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的改动 (`git commit -m '添加某个特性'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建Pull Request

### 代码风格

- 遵循PEP 8 Python代码风格指南
- 使用有意义的变量名和函数名
- 添加必要的注释
- 确保代码通过所有测试

### 提交信息规范

提交信息应该清晰地描述改动的内容，建议使用以下格式：

- feat: 新功能
- fix: 修复bug
- docs: 文档更新
- style: 代码格式化
- refactor: 代码重构
- test: 测试相关
- chore: 构建过程或辅助工具的变动

示例：`feat: 添加IP地址池自动分配功能`

## 开发流程

1. 本地开发环境设置
```bash
# 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Windows使用: venv\Scripts\activate

# 安装依赖
pip install -r requirements.txt

# 安装开发依赖
pip install -r requirements-dev.txt
```

2. 运行测试
```bash
pytest
```

3. 代码检查
```bash
flake8
black .
isort .
```

## 发布流程

1. 版本号遵循语义化版本规范 (Semantic Versioning)
2. 更新CHANGELOG.md
3. 创建新的发布标签

## 行为准则

请参阅我们的[行为准则](CODE_OF_CONDUCT.md)，以了解我们的社区标准。

## 获取帮助

如果您在贡献过程中需要帮助，可以：

- 在Issue中提问
- 发送邮件到维护者邮箱
- 查阅项目Wiki

再次感谢您的贡献！