# GitHub 上传指南

## 将 StarLoom 项目上传到 GitHub

以下是将此项目上传到 GitHub 的详细步骤：

### 1. 已完成的步骤

- 初始化 Git 仓库
- 创建 .gitignore 文件
- 添加所有文件到 Git
- 创建初始提交

### 2. 后续步骤

#### 在 GitHub 上创建新仓库

1. 登录您的 GitHub 账户
2. 点击右上角的 "+" 图标，选择 "New repository"
3. 输入仓库名称（例如：starloom）
4. 可以添加描述："基于AI的算命与占卜系统"
5. 选择仓库可见性（公开或私有）
6. 不要勾选 "Initialize this repository with a README"
7. 点击 "Create repository"

#### 将本地仓库连接到 GitHub

在命令行中执行以下命令（请替换 `YOUR_USERNAME` 为您的 GitHub 用户名）：

```bash
git remote add origin https://github.com/YOUR_USERNAME/starloom.git
git branch -M main
git push -u origin main
```

#### 验证上传

1. 刷新 GitHub 仓库页面
2. 确认所有文件已成功上传

### 注意事项

- 确保不要上传敏感信息（API密钥、密码等）
- .gitignore 文件已配置为忽略常见的不需要上传的文件
- 如果遇到大文件上传问题，可能需要使用 Git LFS

### 后续维护

每次修改代码后，可以使用以下命令更新 GitHub 仓库：

```bash
git add .
git commit -m "更新说明"
git push
```

祝您项目顺利！