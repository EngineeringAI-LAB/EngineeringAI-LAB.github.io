# EngineeringAI Lab GitHub Pages

这是 EngineeringAI Lab 的 GitHub Pages 静态主页。页面无需构建工具，推送到组织主页仓库后即可由 GitHub Pages 发布。

## 推荐仓库名

组织主页仓库请命名为：

```text
EngineeringAI-LAB.github.io
```

发布后的默认访问地址为：

```text
https://engineeringai-lab.github.io/
```

如果使用普通同名仓库，例如 `EngineeringAI-LAB`，页面地址会变成：

```text
https://engineeringai-lab.github.io/EngineeringAI-LAB/
```

## 发布步骤

1. 在 GitHub 组织 `EngineeringAI-LAB` 中新建仓库 `EngineeringAI-LAB.github.io`。
2. 将本目录初始化为 git 仓库并推送到该远程仓库。
3. 打开仓库的 `Settings -> Pages`，选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/root`。
4. 等待 GitHub Pages 完成部署。

可使用以下命令：

```bash
git init -b main
git add .
git commit -m "Initial GitHub Pages site"
git remote add origin git@github.com:EngineeringAI-LAB/EngineeringAI-LAB.github.io.git
git push -u origin main
```

如果使用 HTTPS 远程地址：

```bash
git remote add origin https://github.com/EngineeringAI-LAB/EngineeringAI-LAB.github.io.git
git push -u origin main
```
