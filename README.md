# Claude Skills 项目

这是一个存放 Claude AI 自定义 skill 的项目仓库，用于收集和组织开发过程中编写的 skill 规则和配置。

## 项目结构

```
skills/
├── SKILL-PROJECT-NAME/      # 每个skill的独立目录
│   ├── SKILL.md            # Skill配置文件（必需）
│   ├── examples/           # 可选：示例文件
│   ├── docs/               # 可选：文档
│   └── assets/             # 可选：资源文件
├── README.md               # 项目说明
└── .gitignore              # Git忽略文件配置
```

## 创建新的 Skill

每个 skill 需要创建独立的目录，目录名应能清晰描述该 skill 的功能。每个 skill 目录必须包含一个 `SKILL.md` 文件。

### SKILL.md 模板

```markdown
# Skill Name

Skill 的简短描述，说明什么时候使用这个 skill。

## 触发条件

当用户请求与 skill 相关的功能时使用。列出典型的触发场景。

## 说明

详细说明 skill 的使用方法、注意事项和最佳实践。
```

## 技能管理

- 每个技能应该有明确的触发条件和使用场景
- 保持技能文件简洁明了
- 为复杂技能提供示例和文档
- 避免技能之间功能重叠

## 使用方法

1. 在 `skills/` 目录下创建新的 skill 目录
2. 编写 `SKILL.md` 文件
3. （可选）添加示例和文档
4. 在 Claude 环境中配置该 skill 路径

## 贡献

欢迎添加新的 skill，请确保：
- Skill 功能明确，不与现有 skill 重复
- 提供清晰的文档和说明
- 包含必要的示例

## 许可证

根据项目需要指定许可证