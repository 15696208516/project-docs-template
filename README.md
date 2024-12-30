# 项目文档模板

这是一个通用的项目文档模板仓库，包含了常用的文档模板和最佳实践示例。

## 使用方法

1. 基础模板
   - 在 `templates` 目录下找到需要的文档模板
   - 复制到您的新项目中
   - 根据项目需求修改内容

2. 示例参考
   - 在 `examples` 目录下查看不同类型项目的文档示例
   - 参考示例进行文档编写

## 模板列表

### 基础文档
- `CONTRIBUTING.md`: 开发规范文档
- `README.md`: 项目说明文档

### 需求文档
- `requirements.md`: 需求说明文档
- `features.md`: 功能清单
- `changelog.md`: 变更日志

### 数据库文档
- `design.md`: 数据库设计文档
- `changelog.md`: 数据库变更记录

## 使用建议

1. 文档创建顺序
   - 先创建 README.md
   - 再创建 CONTRIBUTING.md
   - 然后是需求文档
   - 最后是具体实现文档

2. 文档维护
   - 定期更新文档内容
   - 保持文档的时效性
   - 及时补充新的最佳实践

## 目录结构
```
project-docs-template/
├── templates/              # 基础模板
│   ├── CONTRIBUTING.md     # 开发规范模板
│   ├── README.md          # README模板
│   ├── requirements/      # 需求文档
│   │   ├── requirements.md
│   │   ├── features.md
│   │   └── changelog.md
│   ├── database/         # 数据库文档
│   │   ├── design.md
│   │   └── changelog.md
│   └── api/             # API文档
│       └── api.md
├── examples/            # 实际示例
│   ├── go-project/     # Go项目示例
│   └── web-project/    # Web项目示例
└── README.md           # 使用说明
```

## 注意事项

- 所有文档使用 Markdown 格式
- 保持文档结构统一
- 根据实际项目调整内容
- 及时同步文档更新

## 文档模板更新记录

| 日期 | 更新内容 | 更新人 |
|------|----------|--------|
| 2023-12-30 | 创建文档模板仓库 | @dev |

## 贡献指南

欢迎提交 Issue 和 Pull Request 来帮助改进文档模板。在提交之前，请：

1. 检查现有模板是否满足需求
2. 确保新模板具有通用性
3. 提供完整的示例和说明
4. 更新相关文档 