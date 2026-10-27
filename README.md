# 众和 · 企业官网导航页（Apple 风格）拟作年会不能停衍生

一个以 Apple 官网设计语言打造的**企业导航 / 落地页**，用于展示企业「众和（ZHONGHE）」的产品、解决方案、关于与联系方式。

页面严格遵循 [Apple 设计系统](https://github.com/your-ref/awesome-design-md)（来自 `awesome-design-md` 项目的 `apple/DESIGN.md`）：

- 玻璃态固定导航（`rgba(0,0,0,0.8)` + 模糊）
- 黑 `#000000` 与浅灰 `#f5f5f7` 交替的「电影感」区块节奏
- 唯一强调色 Apple Blue `#0071e3`，仅用于可交互元素
- SF Pro 紧凑排版（负字距、紧行高），中文回退 PingFang SC / 微软雅黑
- 980px 药丸 CTA、唯一柔影、无边框、无渐变
- 响应式：移动端汉堡全屏菜单、滚动渐显动画

## 目录结构

```
.
├── index.html      # 页面主体（自包含 HTML/CSS/JS，无需构建）
└── README.md       # 本说明
```

> ```

## 自定义

- 企业信息：搜索 `众和` / `ZHONGHE` 替换品牌名与文案
- 联系方式：修改 `index.html` 中 `mailto:hello@zhonghe.com` 及页脚链接
- 配色：修改 `:root` 中的 CSS 变量（如 `--blue`、`--light`、`--black`）
- 产品 / 方案：在 `index.html` 的 `#products`、`#solutions` 区块增删卡片

## 技术说明

纯静态页面，零依赖、零构建步骤。HTML + 内联 CSS + 原生 JavaScript。
