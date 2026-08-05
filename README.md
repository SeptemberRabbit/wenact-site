# wenact-site

「吾为 · Wenact」App Store 用的公开静态页（隐私政策 / 技术支持），结构对齐 `crumpleden-site`。

源码仓可保持私有；本仓用于 **GitHub Pages**，避免公开主工程。

## 发布

1. 在 GitHub 创建公开仓：`SeptemberRabbit/wenact-site`
2. 绑定远程并推送：

```bash
cd /Users/algorix/Documents/Personal/wenact-site
git branch -M main
git remote add origin https://github.com/SeptemberRabbit/wenact-site.git
git add .
git commit -m "chore: initial privacy, support, and home pages"
git push -u origin main
```

3. GitHub → Settings → Pages → Deploy from branch `main` / root  
4. 打开：
   - https://septemberrabbit.github.io/wenact-site/
   - https://septemberrabbit.github.io/wenact-site/privacy.html
   - https://septemberrabbit.github.io/wenact-site/support.html

联系邮箱当前为 `wenact@163.com`（与遗失之地同为 `@163.com` 模式）；请确认邮箱可用，或改三处 HTML 后再推送。
