# Codex Skills Catalog

这是一个面向 Codex 环境的已安装 Skills 整理仓库，用来记录当前环境中正在使用的 skills、它们的来源，以及面向日常使用的说明文档。

这个仓库适合以下用途：

- 备份个人 Codex skill 环境
- 向团队共享一套常用 skills
- 为新机器迁移 skill 配置提供参考
- 为后续自动化安装、校验和审查提供统一清单

## 仓库内容

- [使用说明.md](./使用说明.md)
  - 面向人的主说明文档，详细介绍每个 skill 的用途、适合场景、前置条件和使用方法。
- [换电脑安装操作手册.md](./换电脑安装操作手册.md)
  - 面向迁移场景的恢复手册，说明换电脑后如何重新安装这套 skills。
- [skills-manifest.json](./skills-manifest.json)
  - 面向程序的 skill 清单，适合后续自动化脚本、校验、迁移或再安装。

## 快速开始

如果你是第一次查看这个仓库，推荐按下面顺序阅读：

1. 先看 [使用说明.md](./使用说明.md)
2. 如果你要迁移到新电脑，再看 [换电脑安装操作手册.md](./换电脑安装操作手册.md)
3. 再看 [skills-manifest.json](./skills-manifest.json)
4. 如果你要复刻环境，再根据其中的来源信息逐个安装

## 当前收录的 Skills

当前目录整理了以下 skills：

1. `using-superpowers`
2. `playwright`
3. `markitdown`
4. `obsidian-markdown`
5. `obsidian-bases`
6. `obsidian-cli`
7. `json-canvas`
8. `defuddle`
9. `find-skills`
10. `security-threat-model`
11. `pdf`

## 阅读建议

- 想快速知道某个 skill 是干什么的：看 [使用说明.md](./使用说明.md)
- 想在新电脑上恢复同样环境：看 [换电脑安装操作手册.md](./换电脑安装操作手册.md)
- 想做自动化处理：看 [skills-manifest.json](./skills-manifest.json)
- 想把这套配置同步到别的设备：同时参考两个文件

## 说明

这个仓库记录的是“已安装 skill 的整理信息”和“使用说明”，不是所有 skill 的原始源码镜像。实际 skill 文件位于本机的 `~/.codex/skills/` 目录。
