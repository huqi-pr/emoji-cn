# Emoji-CN 中文表情符号网站

![License](https://img.shields.io/badge/license-MIT-blue.svg)

一个简单易用的中文表情符号网站，支持快速搜索和复制表情符号。

## ✨ 特性

- 🔍 智能中文搜索
- 📋 一键复制表情符号
- 🎨 优雅的用户界面
- 📱 响应式设计
- 🚀 快速加载
- 🌏 完全中文支持

## 🛠️ 技术栈

- 后端：Rust + Actix-web
- 前端：原生JavaScript
- 模板引擎：Tera
- 静态文件服务：Actix-files

## 📦 安装

1. 克隆仓库：
```bash
git clone https://github.com/yourusername/emoji-cn.git
cd emoji-cn
```

2. 安装依赖：
```bash
cargo build
```

3. 运行项目：
```bash
cargo run
```

访问 `http://127.0.0.1:8081` 即可使用。

## 🎯 使用方法

1. 在搜索框输入关键词搜索表情符号
2. 点击表情符号即可复制到剪贴板
3. 使用分类按钮筛选不同类型的表情符号

## 🔧 配置

项目配置在 `Cargo.toml` 中：

```toml
[dependencies]
actix-web = "4.4"
actix-files = "0.6"
serde = { version = "1.0", features = ["derive"] }
serde_json = "1.0"
tera = "1.19"
tokio = { version = "1.35", features = ["full"] }
```

## 🤝 贡献

欢迎提交 Pull Request 或创建 Issue！

## 📝 开源协议

本项目采用 MIT 协议 - 查看 [LICENSE](LICENSE) 文件了解详情。

search emoji by chinese

thanks by https://getemoji.com/