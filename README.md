# AgentSkills

自定义 Comate Skills 仓库，配合 [AgentSkillsManager](https://github.com/zmzrobin/AgentSkills) 插件使用。

## Skills

### code-reviewer

代码审查与重构专家，提供系统化的代码审查能力。

**功能：**

- 逻辑正确性检查
- 潜在安全风险检测（SQL 注入、XSS、敏感信息泄露等）
- 可读性与命名规范审查
- 性能瓶颈分析
- 异常处理与边界条件检查

## 使用方法

将本仓库添加到 AgentSkillsManager 插件即可自动加载所有 skills。

## 添加新 Skill

在根目录下创建 `<skill-name>/SKILL.md` 文件，遵循 Comate Skill 格式规范。
