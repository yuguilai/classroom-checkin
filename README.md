# 📋 Classroom Checkin - 班级上课考勤核对小工具

一个轻量级的班级考勤管理工具，支持多文件上传、颜色区分、点击签到、长按标记请假，完全在浏览器中运行，无需后端。

![License](https://img.shields.io/badge/license-MIT-blue)
![GitHub last commit](https://img.shields.io/github/last-commit/yuguilai/classroom-checkin)

## ✨ 功能特性

- **多文件支持**：可同时上传多个Excel文件，每个文件自动分配不同颜色，方便区分班级或小组。
- **智能姓名识别**：自动识别表格中的“姓名”列（支持“姓名”、“名字”、“学生姓名”等常见表头）。
- **点击签到**：点击姓名卡片即可切换签到状态，带有流畅动画，签到后卡片变为文件对应的颜色。
- **长按请假标记**：长按姓名卡片弹出菜单，可标记/取消请假，卡片显示“请假”字样。
- **实时统计**：总人数、已签到、请假人数、签到率实时更新，进度条直观展示。
- **搜索定位**：支持按姓名快速搜索，匹配项高亮显示。
- **结果导出**：一键导出签到结果弹窗，支持复制名单到剪贴板。
- **响应式设计**：完美适配手机、平板和电脑。

## 🌐 在线体验

[点击这里立即体验](https://yuguilai.github.io/classroom-checkin)

## 📖 使用说明

1. **上传名单**：点击上传区域或拖拽Excel文件（.xlsx / .xls），可多选。文件中的“姓名”列将被自动提取。
2. **签到操作**：直接点击姓名卡片进行签到/取消签到。
3. **请假标记**：在姓名卡片上**长按**（约0.5秒），选择“标记请假”或“取消请假”。
4. **搜索**：使用顶部搜索框快速定位学生。
5. **批量操作**：使用“全签”一键标记所有学生为已签到，“重置”清除所有签到记录。
6. **导出结果**：点击“导出”查看签到统计，可复制完整名单。

## 🖼️ 界面截图

![主界面](screenshots/main.png)
![签到操作](screenshots/checkin.jpg)
![长按请假](screenshots/leave.jpg)

## 🛠️ 技术栈

- 原生 HTML5 / CSS3 / JavaScript
- [SheetJS (xlsx)](https://github.com/SheetJS/sheetjs) 用于解析Excel文件
- 无其他依赖，轻量快速

## 📦 部署

本工具为纯静态页面，可直接部署到 GitHub Pages、Vercel、Netlify 等平台。

**GitHub Pages 部署步骤：**

1. 将代码推送到 GitHub 仓库。
2. 在仓库设置中启用 GitHub Pages，选择分支（如 `main`）和根目录。
3. 访问 `https://你的用户名.github.io/classroom-checkin` 即可使用。

## 🤝 贡献

欢迎提交 Issue 和 Pull Request。如果您有好的想法或发现bug，请随时提出。

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

---

**作者**：[yuguilai](https://github.com/yuguilai)