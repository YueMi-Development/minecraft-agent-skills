# minecraft-agent-skills

Agent skills for Minecraft server development, PaperMC tools, and plugin ecosystems.

## Skills

### Available Skills

| Skill | Description |
| --- | --- |
| [`bstats`](skills/bstats/SKILL.md) | bStats metrics integration for Minecraft and Hytale plugins — chart types, REST API, and troubleshooting |
| [`minecraft-plugin-manifest`](skills/minecraft-plugin-manifest/SKILL.md) | Plugin metadata, `plugin.yml`, `paper-plugin.yml`, dependencies, permissions, loaders, and Folia support |
| [`minecraft-paper-folia-plugin`](skills/minecraft-paper-folia-plugin/SKILL.md) | Writing Paper plugins that support Folia — schedulers, manifest flags, detection, and migration |
| [`minecraft-paperweight-patcher`](skills/paperweight-patcher/SKILL.md) | Patching, building, and maintaining Minecraft server forks layered on top of Paper |

### Planned Skills

| Skill | Target Area | Description |
| --- | --- | --- |
| `minecraft-paperweight-core` | Server Core | Building Paper server core from upstream Mojang/Spigot |
| `minecraft-paperweight-userdev` | NMS Plugin Dev | Developing NMS plugins using Mojang mappings and paperweight-userdev |

## Installation

Install using the `skills` CLI:

```bash
npx skills add https://github.com/YueMi-Development/minecraft-agent-skills
```
