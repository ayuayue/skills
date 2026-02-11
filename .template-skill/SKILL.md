# Template Skill

这是一个示例 skill 模板，用于展示如何创建新的 Claude skill。

## 触发条件

当需要创建新的技能时，可以作为参考模板。

## 说明

### Skill 结构

每个 skill 目录必须包含一个 `SKILL.md` 文件，这是 skill 的核心配置文件。

### SKILL.md 基本格式

```markdown
# Skill Name

简短描述，说明这个 skill 的用途和适用场景。

## 触发条件

列出何时应该使用这个 skill。提供具体的触发场景示例。

## 说明

详细说明：
- Skill 的功能和用法
- 注意事项和限制
- 最佳实践
- 相关的配置选项
```

### 可选目录结构

```
skill-name/
├── SKILL.md           # 必需：核心配置文件
├── examples/          # 可选：示例文件
│   ├── example1.md
│   └── example2.txt
├── docs/              # 可选：详细文档
│   ├── getting-started.md
│   └── advanced-usage.md
└── assets/            # 可选：资源文件
    ├── images/
    └── templates/
```

### 命名规范

- 目录名：使用小写字母和连字符，如 `my-awesome-skill`
- 文件名：使用小写字母和连字符
- 描述：清晰、简洁，避免技术术语

### 最佳实践

1. **明确触发条件** - 让 Claude 知道何时使用这个 skill
2. **详细文档** - 提供完整的使用说明
3. **示例代码** - 包含实用的示例
4. **避免重叠** - 与其他 skill 功能互补，不重复
5. **保持简洁** - 专注于单一功能领域