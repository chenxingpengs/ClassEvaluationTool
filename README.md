# 🏫 课堂评价工具

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![.NET Version](https://img.shields.io/badge/.NET-6.0-purple.svg)
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg)

> 基于 WPF + Material Design 的现代化课堂评价解决方案

<div align="center">
  <img src="screenshots/demo.gif" width="800" alt="操作演示">
</div>

## 🚀 核心功能
- **小组评价系统**  
  ✅ 优秀小组标记 | ⚠️ 待改进小组追踪
- **个人表现管理**  
  📊 实时评分 | 📈 历史记录回溯
- **数据可视化**  
  📊 LiveCharts 动态图表 | 📅 时间轴分析
- **高级特性**  
  🔄 操作回退 | 📤 Excel 导出 | 🔐 数据加密

## 🛠️ 技术架构
📦 ClassEvaluationTool
├── 📂 Models           # 数据模型
├── 📂 ViewModels       # MVVM 逻辑层
├── 📂 Views            # 界面组件
├── 📂 Services         # 数据库服务
├── 📜 MainWindow.xaml  # 主界面
└── 📜 app.config       # 配置中心
🧑💻 快速开始
环境准备
复制
# 安装 .NET 6 SDK
winget install Microsoft.DotNet.SDK.6
编译运行
bash
复制
git clone https://github.com/yourname/class-evaluation-tool.git
cd class-evaluation-tool
dotnet restore
dotnet build
dotnet run
📜 开源协议
本项目采用 MIT License，欢迎二次开发！
