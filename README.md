# Academic Thesis LaTeX Environment

基于 GitHub Codespaces 的中英文学术论文标准化 LaTeX 撰写环境。

## 🚀 快速开始

1. 点击仓库绿色的 **"Code"** -> **"Create codespace on main"**。
2. **⚠️ 首次启动注意**：
   - 容器启动进入 VS Code 后，后台会自动运行环境安装脚本（下载 LaTeX 核心包）。
   - **请耐心等待约 5-10 分钟**。
   - 你可以通过终端输入 `ps aux | grep apt` 查看安装进程是否在运行。
   - 安装完成后，终端输入 `xelatex --version` 确认成功，即可开始编译。

## ✨ 特性
- **OS**: Debian 12 (Bookworm)
- **Engine**: XeLaTeX (完美支持中文)
- **Fonts**: 内置标准 Times New Roman 及宋体/黑体，无需配置系统字体。
- **Tools**: 预装 Git, Copilot, LaTeX Workshop。

## 📂 字体说明
本项目使用 `fonts/` 目录下的本地字体文件，请勿删除核心文件 (`simsun.ttc`, `times.ttf` 等)。
