# 使用指南

在项目中使用 awesome-design-md 的设计系统，有以下 4 种方式：

---

## 方式一：直接复制 DESIGN.md

从主题目录复制 `DESIGN.md` 到你的项目根目录：

```bash
# 例如：使用 Linear 风格
cp design-md/linear.app/DESIGN.md ./DESIGN.md
```

---

## 方式二：告诉 AI 助手使用设计系统

将 DESIGN.md 路径告诉你的 AI 编程助手（Claude、Cursor、Windsurf 等）：

> "请参考项目根目录的 DESIGN.md 文件来构建 UI，遵循其中的颜色、字体、间距规范。"

或者在 AI 对话中直接粘贴 DESIGN.md 的关键内容，让它生成符合该设计风格的组件。

---

## 方式三：预览效果

打开主题目录中的预览文件，查看完整的组件目录：

```bash
# 浅色模式
open design-md/linear.app/preview.html

# 深色模式
open design-md/linear.app/preview-dark.html
```

预览文件包含：色彩色板、字体层级、按钮样式、卡片组件、间距系统等。

---

## 方式四：使用 Google Stitch

DESIGN.md 格式与 [Google Stitch](https://stitch.withgoogle.com/) 完全兼容。你可以直接将 DESIGN.md 导入 Stitch，或在 Stitch 中创建新设计时参考其格式。

 Stitch 会读取 DESIGN.md 中的颜色、字体、组件规范，自动生成对应的设计系统。

---

## 快速开始示例

```bash
# 1. 选择一个主题（例如 Vercel）
ls design-md/

# 2. 复制到项目
cp design-md/vercel/DESIGN.md ./DESIGN.md

# 3. 告诉 AI
# "使用当前目录的 DESIGN.md 构建一个登录页面"
```

---

## 查看所有主题

```bash
ls -la design-md/
```

共 58 个设计主题，涵盖 AI 产品、开发者工具、金融科技、汽车品牌等多种风格。