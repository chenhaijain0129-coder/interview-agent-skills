# Interview Agent Skills

一组面向中文求职与群面场景的 Codex Skills。

## 包含的 Skills

### `interview-prep`

根据目标公司、岗位 JD、面试轮次和用户主动提供的经历，生成结构化面试准备材料。Skill 不携带候选人个人资料，也不会主动读取本机简历；信息不足时会先询问用户。

### `group-interview`

适用于商业案例、产品运营、资源分配、公共议题、危机处理和创意策划等无领导小组讨论。帮助用户快速搭框架、贡献观点、处理分歧并完成汇报。

## 安装

将需要的 Skill 文件夹复制到 Codex Skills 目录：

```text
~/.codex/skills/
```

安装后的目录示例：

```text
~/.codex/skills/interview-prep/
~/.codex/skills/group-interview/
```

重启 Codex 后即可使用：

```text
使用 $interview-prep，先询问我的经历，再帮我准备这场面试。
```

```text
使用 $group-interview，帮我在 30 秒内搭出这道群面题的讨论框架。
```

## 隐私与事实边界

- 仓库不包含真实简历、联系方式、内部项目资料或本机路径。
- 用户经历只在当前对话中由用户主动提供。
- Skill 不编造项目、数据、职责或公司内部信息。
- 涉及最新公司、产品或市场信息时，应查证公开来源并区分事实与推断。

## 参与贡献

欢迎提交 Issue 或 Pull Request。修改 Skill 时，请保持触发描述清晰、避免引入个人资料，并确保引用文件能从对应的 `SKILL.md` 找到。

## License

[MIT](LICENSE)
