# FULL PORTABLE LIST
一个为可移动存储设备精心整理的免费且真正便携的软件列表。

<div align="center">
  
  [English](README.md) | [简体中文](README.zh_CN.md)
  
</div>

<!-- Shields/Badges -->
<p align="center">
  <img src="Shields/FPL-Native_Portable-blue.svg" alt="原生便携"/>
  <img src="Shields/FPL-Setting_Portable-brightgreen.svg" alt="设置便携"/>
  <img src="Shields/FPL-Isolated_Portable-orange.svg" alt="隔离便携"/>
  <img src="Shields/FPL-Fake_Portable-lightgrey.svg" alt="伪便携"/>
  <img src="Shields/FPL-No_Portable-red.svg" alt="无便携"/>
  <img src="Shields/FPL-Runtime-purple.svg" alt="运行时"/>
</p>

## FULL PORTABLE 标准

- **自由软件：** 必须符合 FSF（自由软件基金会）对自由软件的定义。
- **自包含数据：** 所有配置、数据和缓存文件必须仅存储在指定的本地目录中。软件不得向主机系统目录或注册表写入数据（例外：必要的操作系统级缓存，如 GPU 驱动缓存等，不受此限制）。
- **活跃社区：** 项目应有健康的社区环境，并具备一定的流行度门槛（例如，GitHub 星标数不少于 1000 或等效认可度）。
- **安全与稳定：** 软件必须安全、稳定，无已知的恶意行为或开发者不当行为历史。

---

## 定义

- **原生便携（Native Portable）：** 软件原生即支持将所有数据存储在指定目录，无需特殊配置即可实现。
- **设置便携（Setting Portable）：** 软件默认会向主机系统写入数据，但可通过内置设置（如存在特定文件夹或文件）将所有数据存储在指定目录（例如 VSCode 检测 "data" 文件夹，Windows Terminal 检测 ".portable" 文件等）。
- **隔离便携（Isolated Portable）：** 软件默认仅支持向主机系统写入数据，但可通过技术手段（如设置环境变量或添加参数）将所有数据重定向到指定目录，避免写入主机环境。
- **伪便携（Fake Portable）：**（*不符合 FULL PORTABLE 标准*）数据初始写入主机系统，随后迁移到指定目录，以实现便携性。
- **无便携（No Portable）：** 不符合上述任何便携标准。

---
