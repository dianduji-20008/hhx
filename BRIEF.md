# 槐花香（HHX）官网 — 项目说明

## 项目概述

为品牌「槐花香 HHX」创建产品矩阵官网，展示旗下所有工具产品。

## 仓库

- GitHub: https://github.com/dianduji-20008/hhx
- 已创建，已配置 remote origin
- main 分支会自动部署到 GitHub Pages

## 品牌信息

- 中文名：槐花香
- 英文名：HHX
- Slogan：让工具回归简单
- 色调：深色背景 + 金色（#f0c040）主色调，绿色（#6ee7a0）辅助色
- 字体：Noto Serif SC（标题）+ Inter（正文）
- 风格：暗色调、质感、克制、专业

## 产品矩阵

### 1. 工具盒子 ToolBox
- 链接：https://toolbox-duc.pages.dev/
- GitHub：https://github.com/dianduji-20008/toolbox-site
- 定位：十八款免费在线工具，纯浏览器本地运行
- 标签：免费 / 纯本地 / 网页端
- 核心卖点：开网页即用，数据不上传
- 工具列表：二维码生成器、JSON格式化、密码生成器、字数统计、Base64编解码、URL编解码、颜色拾取器、大小写转换、Hash计算器、时间戳转换、正则表达式测试、UUID生成器、进制转换器、IP地址查询、文本差异对比、Markdown编辑器、单位换算器、图片压缩

### 2. 报价单 QuoteMaker
- GitHub：https://github.com/dianduji-20008/QuoteMaker
- 定位：为小微服务商家打造的本地报价单工具
- 标签：买断制 / 纯本地 / Windows
- 核心卖点：3分钟出专业报价，数据完全本地存储
- 目标用户：装修/安装店、广告/设计工作室、摄影/婚庆、美容/家政、培训/咨询
- 定价：个人版 99元 / 工作室版 299元
- 状态：开发中，尚未正式发布

## 页面结构

单页网站，包含以下区域：

1. **导航栏** — 固定顶部，品牌标识 + 锚点链接 + GitHub
2. **Hero** — 大标题「让工具回归简单」+ 副标题 + CTA按钮
3. **产品矩阵** — 每个产品一张卡片，含产品预览示意图、描述、标签、操作按钮
4. **理念** — 三张卡片：数据属于你 / 小而专注 / 持续生长
5. **CTA** — 号召参与 GitHub
6. **Footer** — 版权 + 链接

## 技术要求

- 纯静态 HTML/CSS/JS，单文件 index.html
- 响应式设计，移动端适配
- 滚动动画（Intersection Observer）
- 无框架依赖
- GitHub Pages 自动部署（push main 即触发）

## 注意事项

- QuoteMaker 尚未正式发布，官网上的描述要体现「即将推出」或「开发中」
- 所有外部链接使用 target="_blank" rel="noopener"
- 中文内容，zh-CN 语言标签