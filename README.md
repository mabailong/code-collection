# code-collection

我的 GitHub 起点：工具、高分项目与代码片段收集。

这台电脑已经配好了 SSH 密钥，读写仓库不需要再输入密码。

## 常用操作

```bash
# 把 GitHub 上任意项目下载到本地
git clone git@github.com:作者/仓库名.git

# 也可以直接用网页上的 HTTPS 地址，会自动转成 SSH
git clone https://github.com/作者/仓库名.git

# 保存改动到云端仓库
git add .
git commit -m "说明改了什么"
git push

# 把云端最新版拉下来
git pull
```

本地仓库放在 `~/格莱希娅/code-collection`。

## GitHub 命令行工具（gh）常用命令

```bash
gh repo list                       # 列出我的仓库
gh repo create 名字                # 新建仓库
gh search repos --stars ">50000"   # 搜索高分项目
gh repo clone 作者/仓库名           # 下载公开项目
gh api /user                       # 查看账号信息
```

## 当前 GitHub 上星数最高的项目

| 项目 | 星数 | 简介 |
|---|---|---|
| [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) | 550,712 | Master programming by recreating your favorite technologies  |
| [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | 512,527 | 😎 Awesome lists about all kinds of interesting topics [NOTE: |
| [public-apis/public-apis](https://github.com/public-apis/public-apis) | 484,449 | A collective list of free APIs |
| [freeCodeCamp/freeCodeCamp](https://github.com/freeCodeCamp/freeCodeCamp) | 456,543 | freeCodeCamp.org's open-source codebase and curriculum. Lear |
| [EbookFoundation/free-programming-books](https://github.com/EbookFoundation/free-programming-books) | 398,175 | :books: Freely available programming books |
| [openclaw/openclaw](https://github.com/openclaw/openclaw) | 390,809 | The AI that really does things. Any OS. Any Platform. The lo |
| [donnemartin/system-design-primer](https://github.com/donnemartin/system-design-primer) | 372,563 | Learn how to design large-scale systems. Prep for the system |
| [nilbuild/developer-roadmap](https://github.com/nilbuild/developer-roadmap) | 368,531 | Interactive roadmaps, guides and other educational content t |
| [jwasham/coding-interview-university](https://github.com/jwasham/coding-interview-university) | 362,134 | A complete computer science study plan to become a software  |
| [vinta/awesome-python](https://github.com/vinta/awesome-python) | 324,146 | The definitive list that answers "I want to do X in Python,  |

---

账号：mabailong
