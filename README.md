# 五月医学前沿月报

每月 1 号自动更新的医学前沿月报网站，涵盖 5 大栏目：

- 🔬 小儿外科前沿
- 💡 腹壁疝外科
- 🔪 外科技术革新
- 🤖 AI + 医疗
- 🧬 生命科学重大进展

## 网站地址

https://may-medical-digest.netlify.app

## 技术栈

- 纯静态 HTML + CSS + JavaScript
- 数据从 `digest.json` 读取渲染
- 支持离线双击打开（数据嵌入 HTML）
- 移动端适配

## 自动部署

- GitHub 仓库：https://github.com/17741795395/may-medical-digest
- 部署平台：Netlify
- 触发方式：推送 main 分支自动部署

## 文件结构

```
web/
├── index.html      # 网站主页面
├── digest.json     # 最新一期数据
├── update_web.js   # 更新脚本（嵌入数据到 HTML）
└── README.md
```

## 本地预览

直接用浏览器打开 `index.html` 即可。
