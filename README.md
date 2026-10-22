# my-first-repo

我的第一个 GitHub 仓库，用来熟悉 GitHub 的基本流程：写文件、提交、开分支、提 PR。

## 目录结构

| 文件 | 说明 |
| --- | --- |
| `README.md` | 本说明文件 |
| `hello.py` | 一个最简 Python 示例，用来验证代码能跑 |
| `notes.md` | 学习笔记 |
| `.gitignore` | 告诉 Git 哪些文件不要提交 |

## 怎么跑起来

```bash
python hello.py
```

## 常用流程回顾

1. 建分支：`git checkout -b 分支名`
2. 改文件后提交：`git commit -am "说明"`
3. 推送：`git push -u origin 分支名`
4. 在 GitHub 上发起 Pull Request，合并回 `main`
