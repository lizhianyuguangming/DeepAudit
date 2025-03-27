# DeepAudit 代码审计工具


## 简介
DeepAudit 是一款基于 Python 和 Tkinter 开发的代码审计工具，旨在帮助开发者自动分析项目代码，检测潜在的安全漏洞。该工具通过调用 DeepSeek API，对代码进行深入分析，并将结果以直观的界面展示给用户。同时，支持将漏洞结果导出为 Excel 文档，方便用户进行后续处理。

## 📌 核心功能

### 代码审计
- **多语言支持**：PHP、Java、JavaScript、HTML/XML 文件分析
- **智能分块处理**：自动拆分大文件进行分段分析
- **漏洞类型检测**：SQL注入、XSS、代码执行等常见高危漏洞
- **风险等级评估**：高危/中危/低危三级分类

### 可视化界面
- 项目文件树形浏览
- 代码实时预览与语法高亮
- 漏洞详情展示（风险点/Payload/修复建议）
- 交互式搜索与跳转功能

## 🛠️ 环境安装

### 依赖要求
```bash
Python 3.7+
pip install -r requirements.txt
```

## 🚀 快速使用
配置API密钥
首次运行会自动生成 config.ini，填入获取的API密钥
```
python DeepAudit代码审计工具.py
```
![image](https://github.com/user-attachments/assets/bc04820f-55ef-426c-b670-1b7c2d861355)


## 未完成模块
-  逆向追踪代码链
-  自动验证漏洞
-  .....


欢迎通过 Issue 提交：优化建议、代码bug等

      如果您觉得这个项目对您有帮助，别忘了点亮 Star ⭐！
      您的支持是我们继续优化和改进这个项目的动力！ 😊
