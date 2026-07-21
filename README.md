# Guijia Zhang — Personal Homepage

个人学术主页，纯静态 HTML/CSS，无需任何构建工具，直接托管在 GitHub Pages。

横向布局：顶部固定导航 + 宽幅内容区。视觉使用勇士蓝、金色、球场几何线和 30 号元素，
同时保持论文优先的正式学术风格。
内容拆分为五个独立页面：

- `index.html` — About + News
- `publications.html` — 论文列表
- `experience.html` — 科研经历 + 教育背景
- `projects.html` — 工程项目
- `awards.html` — 奖项与培训

公共样式在 `style.css`。修改导航或联系方式时，五个页面需要同步更新。

## 本地预览

直接双击 `index.html`，或：

```bash
cd homepage
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 部署

GitHub 仓库：`https://github.com/123zgj123/gjzhang.github.io`

由于 GitHub Pages 的根域名必须和账号名一致，账号 `123zgj123` 下的实际项目地址为：
`https://123zgj123.github.io/gjzhang.github.io/`。

## 后续可补充

- ECA（2605.19192）、STARS（2604.10286）、GUI Agents（2607.04334）三篇的 arXiv 链接已填好；
  “Agent Skill Regulation” 和 “EchoRAG” 两篇暂无链接，拿到 arXiv 编号后可参照其他条目补上
- 简历已放在 `assets/cv.pdf`
- 当前头像采用 30 号圆章；如需本人照片，可放入 `assets/avatar.jpg` 并修改导航头像
