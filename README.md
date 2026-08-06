<h1 align="center">Fabre</h1>

<div align="center">
  高性能大型 MMORPG 游戏模拟器<br />
  使用 <code>Rust</code> 编写 · 兼容 rAthena 风格数据布局 · 解压即用
</div>

<br />

<div align="center">

  <!-- Discord -->
  <a href="https://discord.com/invite/Tygv5t7u23">
    <img alt="Discord" src="https://img.shields.io/discord/1482430722739273799?style=flat-square&label=Discord&logo=discord&logoColor=white&color=5865F2">
  </a>
  <!-- Latest release -->
  <a href="https://github.com/MidgardLabs/fabre-release/releases/latest">
    <img alt="Latest release" src="https://img.shields.io/github/v/release/MidgardLabs/fabre-release?style=flat-square&label=Release&color=0ea5e9">
  </a>
  <!-- Release date -->
  <a href="https://github.com/MidgardLabs/fabre-release/releases">
    <img alt="Release date" src="https://img.shields.io/github/release-date/MidgardLabs/fabre-release?style=flat-square&label=Updated">
  </a>
  <!-- Downloads (all releases) -->
  <a href="https://github.com/MidgardLabs/fabre-release/releases">
    <img alt="Downloads" src="https://img.shields.io/github/downloads/MidgardLabs/fabre-release/total?style=flat-square&label=Downloads&color=22c55e">
  </a>

</div>

<div align="center">
  <h3>
    <a href="https://fabre.app" target="_blank">官网</a>
    <span> · </span>
    <a href="https://fabre.app/roadmap" target="_blank">路线图</a>
    <span> · </span>
    <a href="https://fabre.app/changelog" target="_blank">更新日志</a>
    <span> · </span>
    <a href="https://github.com/MidgardLabs/fabre-release/releases">下载</a>
  </h3>
</div>

> Fabre 仍在持续开发。当前版本适合搭建测试服务器和体验已实现功能；部分职业技能、城战与战场功能仍在开发中。正式运营前，请先查看 [路线图](https://fabre.app/roadmap) 和 [当前版本说明](https://github.com/MidgardLabs/fabre-release/releases/latest)。

---

## 为什么选择 Fabre

- **一键启动**：单个可执行文件包含全部服务，双击即可运行。规模增长时，同一程序可切换为分布式部署
- **开箱即用**：内置 SQLite 引擎，下载即可运行，无需安装数据库、导入 SQL、配置连接参数等繁琐步骤
- **无忧升级**：版本更新时数据库结构自动迁移，无需手动执行升级脚本。随着规模扩大，只需修改一项配置即可从 SQLite 切换到 MySQL
- **兼容 rAthena 数据**：默认可加载 rAthena 风格的 `db/` 与 `npc/`
- **支持多语言**：服务端提示支持简体中文、繁体中文和英文

---

## 支持平台

| 平台 | 架构 |
|------|------|
| Windows | x64 |
| macOS | ARM64 (Apple Silicon) |

其他平台的可用情况以 [最新 Release](https://github.com/MidgardLabs/fabre-release/releases/latest) 为准。

---

## 快速开始

1. 从 [官网](https://fabre.app) 或 [GitHub Releases](https://github.com/MidgardLabs/fabre-release/releases/latest) 下载对应平台的发行包
2. 解压到任意目录
3. 运行 `fabre`；Windows 用户运行 `fabre.exe`

> 默认客户端协议版本为 `20220406`。使用其他客户端版本时，请修改 `conf/config.toml` 中的 `general.packetver`，并确保它与客户端 EXE 的 PACKETVER 一致。

---

## 许可协议

Fabre 服务器程序为闭源软件：通过本仓库 Release 与官网提供编译后的二进制，源码不在此公开。发行包内 `db/`、`npc/` 等游戏数据与脚本主要来自 [rAthena](https://github.com/rathena/rathena)，遵循其 GPLv3 及文件内声明。

---

## 反馈

使用问题请通过 [GitHub Issues](https://github.com/MidgardLabs/fabre-release/issues) 反馈，并附上 **版本号**、操作系统、客户端日期与可复现步骤。实时交流可加入 [Discord](https://discord.com/invite/Tygv5t7u23)。
