# SBTI 人格测试

MBTI 已经过时，SBTI 来了。

31 道灵魂拷问，15 个维度深度剖析，找到属于你的隐藏人格。

## 特性

- **单页面应用** — 纯 HTML/CSS/JS，无需构建工具，开箱即用
- **31 道测试题** — 30 道常规题 + 1 道隐藏门控题，每次随机排列
- **15 个评估维度** — 涵盖自我、情感、态度、行动驱力、社交五大模型
- **25+ 种人格类型** — 每种人格配有专属描述和插图
- **隐藏机制** — 选择"饮酒"可触发隐藏酒鬼人格；匹配度低于 60% 时兜底为傻乐者

## 快速开始

```bash
# 克隆项目
git clone https://github.com/freeman5860/SBTI.git
cd SBTI

# 启动本地服务器
python3 -m http.server 8080

# 打开浏览器访问
open http://localhost:8080
```

## 项目结构

```
SBTI/
├── index.html    # 主页面（包含完整的 HTML + CSS + JS）
└── image/        # 27 张人格类型配图
```

## 部署

本项目为纯静态页面，可直接部署到任意静态托管平台：

- **Cloudflare Pages** — 直接连接 GitHub 仓库
- **GitHub Pages** — Settings → Pages → Deploy from branch
- **Vercel / Netlify** — 导入仓库即可

## 致谢

原始测试内容来自 B 站 UP 主 [蛆肉儿串儿](https://space.bilibili.com/417038183)。
