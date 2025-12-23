# Calculator

轻量级的网页计算器（版本 1.0.2）。

“index.html”为此仓库中的最新版界面 —— 直接打开它即可使用计算器功能。

## 功能
- 基本算术运算：加、减、乘、除
- 支持小数运算
- 清除/删除（CE / Backspace）
- 计算历史记录：查看和加载过去的计算结果
- 简洁响应式界面，可在桌面和移动设备上使用

## 快速开始
1. 克隆仓库或下载 ZIP：
   ```bash
   git clone https://github.com/JiangWanZhengChouYv/Calculator.git
   ```
2. 在本地直接打开 `index.html`（双击或在浏览器中打开文件）即可使用。
   - 如果你使用静态站点服务器（推荐用于某些浏览器的权限限制）：
     ```bash
     # 用 Python 3 快速启动静态服务器（在仓库根目录）
     python -m http.server 8000
     # 然后在浏览器打开 http://localhost:8000/index.html
     ```

## 演示
（可在此处放置截图或演示 GIF，便于用户直观了解界面）
- 示例：打开 `index.html` 后即可输入表达式并查看结果。

## 支持的浏览器
- 现代浏览器：Chrome、Firefox、Edge、Safari（较旧浏览器在某些 ES/HTML 特性上可能有差异）

## 文件结构（简要）
- index.html — 主界面（运行时直接打开）
- README.md — 项目说明（本文件）

## 贡献
欢迎提交 issue 和 PR：
- 提交 bug 报告请说明重现步骤、浏览器与版本信息。
- 提交新功能建议请描述预期行为和用例。

## 许可证
本项目使用 MIT 许可证。

## 作者
JiangWanZhengChouYv

## 版本历史
- 1.0.2 — 优化界面排版，历史面板默认显示并支持响应式布局
- 1.0.1 — 添加历史功能，支持查看和加载过去的计算记录
- 1.0.0 — 初始版本（包含基本计算功能）
