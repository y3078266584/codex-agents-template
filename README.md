# Codex 全局指令模板

一份开箱即用的 Codex 全局 `AGENTS.md`，规范沟通、工作流程、代码质量与项目管理。

## 适用场景

- Codex Desktop / CLI 用户
- 希望统一 Codex 行为规范的个人或团队
- 作为新项目初始化的起点

## 使用方法

将 `AGENTS.md` 复制到 `~/.codex/AGENTS.md`：

```powershell
# Windows
copy AGENTS.md $env:USERPROFILE\.codex\AGENTS.md
```

```bash
# macOS / Linux
cp AGENTS.md ~/.codex/AGENTS.md
```

重启 Codex 后，全局指令自动生效。

## 内容概览

| 分类 | 说明 |
|------|------|
| 🗣️ 沟通规范 | 中文回复、中文注释、进度告知 |
| 📋 工作流程 | 大改动先方案、改前读文件、改后跑测试 |
| ⚠️ 安全红线 | 禁止危险命令、不碰自动生成目录、只改任务相关 |
| 🧱 代码质量 | 风格一致、不引入无用依赖、根源修复 |
| 📁 项目管理 | 初始化流程、版本号规范、Git 存档规则 |

## 自定义

根据个人或团队需求增删条目。全局 `AGENTS.md` 的条目可被项目级 `AGENTS.md` 覆盖。

## 许可

MIT — 自由使用、修改、分享。
