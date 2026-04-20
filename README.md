# online-gotool - 程序员的一站式在线工具箱文档库 🛠️

**online-gotool** 是 [GoTool](https://gotool.top) 的静态资源与文档仓库。本项目收录了工具箱中所有功能的静态 HTML 页面及相关文档说明，支持多语言（中文简体、繁体、英文）。

🔗 **在线使用工具**: [https://gotool.top](https://gotool.top)

---

## 📂 仓库结构

此仓库结构对应工具箱的各个功能模块：

- `index.html`: 首页入口。
- `docs/`: 中文简体文档与工具页面（如 SQL 转 GORM, JSON 转换等）。
- `en/docs/`: 英文版本。
- `zh-tw/docs/`: 繁体中文版本。

## 🌟 工具核心亮点 (以 ORM 转换为例)

### 1. 数据库模型转换 (ORM Generator)
支持将 SQL DDL 语句一键转换为各种 Go ORM 模型：
- **SQL -> GORM Struct**: 自动解析字段名、类型、约束及注释。
- **SQL -> XORM Struct**: 完美生成 XORM 专用 Tag（pk, autoincr, notnull 等）。
- **SQL -> Ent/DML/Gorm**: 覆盖主流 Go ORM 框架。
- **支持数据库**: MySQL, PostgreSQL, Oracle, SQLite 等。

### 2. 开发提效工具
- **JSON 相关**: JSON 转 Go Struct (Interface)、Proto、Java、ES Mapping。
- **格式化**: SQL 美化、JSON 美化、Crontab 生成。
- **图片处理**: Base64 互转、图片压缩、尺寸调整。
- **常用工具**: UUID 生成、二维码生成、正则调试、时间戳转换。

---

## 🚀 为什么选择 GoTool?

- **极速免配置**: 纯 Web 实现，无需安装 CLI，即开即用。
- **深度解析**: 自动解析 SQL `COMMENT`，生成带注释的 Go 结构体。
- **多语言支持**: 为全球开发者提供一致的体验。
- **隐私保障**: 数据处理主要在客户端完成，安全可靠。

---

## 🛠️ 技术栈
- **Frontend**: 纯原生 HTML5, JavaScript, CSS (不依赖重型框架，极速响应)
- **Deployment**: [https://doc.gotool.top](https://doc.gotool.top)

---

## 🤝 关联项目
- **主站**: [gotool.top](https://gotool.top)
- **文档库 (本仓库)**: [doc.gotool.top](https://doc.gotool.top)
