# 有理数专题互动课 · GitHub Pages 部署包

包内文件（请全部放在仓库同一目录，文件名不要改）：

| 文件 | 内容 |
| --- | --- |
| `index.html` | **课程首页（入口）**，访问仓库根地址时自动打开，含两个专题的导航卡片 |
| `jueduizhi-huajian.html` | 专题 1：绝对值化简的分类讨论思想（零点分段五步法、多绝对值分段最小值、带范围化简、4 关闯关、错题医院） |
| `shu-de-bijiao.html` | 专题 2：数的大小比较四大方法（特殊值法 / 测试点法 / 作差法 / 作商法、4 关闯关、错题医院） |
| `.nojekyll` | 空文件，让 GitHub 原样发布（不要删） |
| `README_部署说明.md` | 本说明（不需要上传） |

## 部署步骤（约 5 分钟，全程浏览器操作）

1. 登录 https://github.com → 右上角 **+** → **New repository**
2. 仓库名填 `math6`（或任意英文名），选 **Public**，勾选 **Add a README file**，点 **Create repository**
3. 点 **uploading an existing file**，把解压出的 **4 个文件**（index.html、两个 .html、.nojekyll）拖进去 → **Commit changes**
4. 仓库 **Settings → Pages**，Source 选 **Deploy from a branch**，Branch 选 **main / (root)** → **Save**
5. 等 1~2 分钟，直接访问根地址即可看到课程首页：
   - **首页：https://你的用户名.github.io/math6/**
   - 专题1直链：https://你的用户名.github.io/math6/jueduizhi-huajian.html
   - 专题2直链：https://你的用户名.github.io/math6/shu-de-bijiao.html

## ⚠️ 常见问题

- **根地址显示 404「File not found」**：说明仓库根目录缺少 `index.html`。GitHub Pages 访问文件夹时默认打开该文件夹下的 `index.html`，没有就报 404。请确认 `index.html` 已上传到仓库**根目录**（不是在某个子文件夹里）。
- **文件名大小写**：GitHub 区分大小写，`Index.html` 或 `index.HTML` 都不行，必须是全小写 `index.html`。
- **两个专题互跳失效**：三个 html 必须在同一目录，且文件名保持全小写拼音不变。
- **刚上传还是 404**：Pages 首次发布需 1~3 分钟，稍等后刷新（可按 Ctrl+F5 强制刷新）。

## 更新内容
重新上传同名文件覆盖即可，Pages 约 1 分钟自动更新。
