# Cangjie LSP Plugin

仓颉语言 Claude Code LSP 插件。

## 依赖

- 仓颉 SDK 已安装，`LSPServer` 在 PATH 中

## 安装

### 第一步：添加市场

```
/plugin marketplace add sanchuanhehe/cangjie-lsp
```

### 第二步：安装插件

```
/plugin install cangjie-lsp
```

### 本地开发

```bash
git clone https://github.com/sanchuanhehe/cangjie-lsp.git
claude --plugin-dir ./cangjie-lsp
```

## 功能

| 功能 | 触发 |
|------|------|
| 代码补全 | `.` `` ` `` |
| 悬停类型提示 | Hover |
| 跳转定义 | Go to Definition |
| 查找引用 | Find References |
| 重命名 | Rename |
| 语义高亮 | Semantic Tokens |
| 签名帮助 | `(` `,` |
| 文档/工作区符号 | Symbols |
| 调用/类型层次 | Hierarchy |

## 关联文件

- `.cj` — 仓颉源文件
- `.cangjie` — 仓颉模块文件
