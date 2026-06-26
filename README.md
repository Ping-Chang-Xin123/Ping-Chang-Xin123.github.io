# Personal Site for GitHub Pages

这是一个零构建的个人网站模板，适合直接托管到 GitHub Pages。
当前内容已经按 `Ping-Chang-Xin123` 这套 GitHub 身份做了第一轮个性化替换。

## 文件结构

- `index.html`: 首页内容
- `styles.css`: 页面样式
- `script.js`: 轻量滚动动效
- `.github/workflows/deploy.yml`: GitHub Pages 自动部署工作流

## 如何发布

1. 在 GitHub 新建一个仓库，仓库名建议直接用 `Ping-Chang-Xin123.github.io`。
2. 把当前目录内容推到仓库的 `main` 分支。
3. 进入仓库的 `Settings -> Pages`。
4. 在 `Build and deployment` 里选择 `GitHub Actions`。
5. 推送后等待 Actions 跑完，站点就会发布到 `https://ping-chang-xin123.github.io/`。

### 首次推送命令

```bash
git add .
git commit -m "Initial personal site"
git remote add origin https://github.com/Ping-Chang-Xin123/Ping-Chang-Xin123.github.io.git
git push -u origin main
```

## 建议修改的内容

- 按你的真实姓名、职业方向和项目经历继续细化首页文案
- 如果你愿意公开邮箱，可以把联系区再改成邮箱 + GitHub 双入口
- 从你的仓库里挑 2 到 3 个代表项目，替换目前的通用卡片
- 如果你有自定义域名，可以在 Pages 设置里绑定

## 推荐下一步

- 先把这个版本上线，确认域名和内容方向
- 后续如果你想加博客系统，可以升级到 Astro
