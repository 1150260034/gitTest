# gitTest

## 简介

本仓库是一个用于学习和练习 Git 版本控制操作的测试仓库。

## 目的

- 练习 Git 基本命令（`git init`、`git add`、`git commit`、`git push` 等）
- 学习分支管理（创建、合并、删除分支）
- 熟悉多平台（Windows / Linux / macOS）下的 Git 工作流
- 练习使用 VSCode 等编辑器集成的 Git 功能

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 示例 HTML 页面，用于测试提交与版本追踪 |
| `a.txt` | 通过 VSCode 及开发分支添加的测试文件 |
| `b.txt` | 空白测试文件 |
| `test.txt` | 在 master 分支上添加的测试文件 |
| `Windows.txt` | 在 Windows 环境下添加的测试文件 |

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/1150260034/gitTest.git

# 查看当前状态
git status

# 查看提交历史
git log --oneline
```

## 常用 Git 命令参考

```bash
# 添加文件到暂存区
git add <文件名>

# 提交更改
git commit -m "提交说明"

# 推送到远程仓库
git push origin master

# 创建并切换到新分支
git checkout -b <分支名>

# 合并分支
git merge <分支名>
```
