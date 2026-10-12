# minecraft-agent-skills

Agent skills for Minecraft server development, PaperMC tools, and plugin ecosystems.

## Skills

### Available Skills

| Skill | Description |
| --- | --- |
| [`minecraft-plugin-manifest`](skills/minecraft-plugin-manifest/SKILL.md) | Plugin metadata, `plugin.yml`, `paper-plugin.yml`, dependencies, permissions, and loaders |
| [`minecraft-paperweight-patcher`](skills/paperweight-patcher/SKILL.md) | Patching, building, and maintaining Minecraft server forks layered on top of Paper |

### Planned Skills

| Skill | Target Area | Description |
| --- | --- | --- |
| `minecraft-paperweight-core` | Server Core | Building Paper server core from upstream Mojang/Spigot |
| `minecraft-paperweight-userdev` | NMS Plugin Dev | Developing NMS plugins using Mojang mappings and paperweight-userdev |
| `minecraft-plugin-bootstrap` | Architecture | Plugin lifecycle, bootstrappers, custom classloaders, and DI setup |

## Installation

Install using the `skills` CLI:

```bash
npx skills add https://github.com/YueMi-Development/minecraft-agent-skills
```
