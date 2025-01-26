# Danheng Server

**__This project is under development! Some game features might not work as intended, if at all!__**

<p align="center">
<a href="https://visualstudio.com"><img src="https://img.shields.io/badge/Visual%20Studio-000000.svg?style=for-the-badge&logo=visual-studio&logoColor=white" /></a>
<a href="https://dotnet.microsoft.com/"><img src="https://img.shields.io/badge/.NET-000000.svg?style=for-the-badge&logo=.NET&logoColor=white" /></a>
<a href="https://www.gnu.org/"><img src="https://img.shields.io/badge/GNU-000000.svg?style=for-the-badge&logo=GNU&logoColor=white" /></a>
</p>
<p align="center">
  <a href="https://discord.gg/xRtZsmHBVj"><img src="https://img.shields.io/badge/Discord%20Server-000000.svg?style=for-the-badge&logo=Discord&logoColor=white" /></a>
</p>

[EN](README.md) | [简中](docs/README_zh-CN.md) | [繁中](docs/README_zh-TW.md) | [JP](docs/README_ja-JP.md)

## 💡 Function

- [√] **Shop**
- [√] **Formation**
- [√] **Gacha** - Custom probability : )
- [√] **Battle** - Some errors are exist among scene skills
- [√] **Scene** - Walking simulator, interaction, correct loading of entities
- [√] **Basic character development** - Some minor bugs that don't significantly affect the playing experience
- [√] **Quests** - There may be some bugs in some missions, the main story before Penacony is basically playable, and most of the story after Penacony has bugs
- [√] **Friends**
- [√] **Forgotten Hall & Pure Fiction & Apocalyptic Shadow**
- [√] **Simulated Universe & Gold and Gears**
- [√] **Achievements** - Most achievements can be completed.

- [ ] **More**  - Coming soon

Some functions of the game might not be supported at first, when a new version of the "Anime Game" drops, in such cases, please wait for a new commit tp this Server. Since version 2.3, The original Creators've created a private fork which supports the beta version of the game, and the private fork will be merged to the main branch ASAP when it's ready for release.

## 🍗 Use & Installation

### Quick Start

DOESNT EXIST YET, ORIGINAL IS FAULTY AND DOESNT REALLY WORK, AND IM TOO BORED TO MAKE A WORKING ONE, IF YOU HAVE A GOOD QUICK START GUIDE IN TEXT, MESSAGE @bioleft3 ON DISCORD (dont waste my time with random stuff)

### Build

DanhengServer is built using .NET Framework

**Requirement: **

- [.NET](https://dotnet.microsoft.com/)
- [Git](https://git-scm.com/downloads)

```shell
git clone --recurse-submodules https://github.com/EggLink/DanhengServer-Public.git
cd DanhengServer
```
Compile for Windows
```shell
dotnet publish Program\Program.csproj -o Release\win-x64 -r win-x64 --framework net8.0 -p:PublishSingleFile=true
```
Compile for Linux
```shell
dotnet publish Program\Program.csproj -o Release\linux-x64 -r linux-x64 --framework net8.0 -p:PublishSingleFile=true
```
Compile for Arm Linux
```shell
dotnet publish Program\Program.csproj -o Release\linux-arm64 -r linux-arm64 --framework net8.0 -p:PublishSingleFile=true
```

## 🔗API Help
[EN](docs/MuipAPI.md) | [简中](docs/MuipAPI_zh-CN.md) | [繁中](docs/MuipAPI_zh-TW.md) | [JP](docs/MuipAPI_ja-JP.md)

## ❕️ Troubleshooting

For solutions to common problems or assistance, please join the 'offficial' DanhengServer Discord server at [https://discord.gg/xRtZsmHBVj](https://discord.gg/xRtZsmHBVj)

## 🙌 Acknowledgements

- Weedwacker - Provides kcp implementation
- [SqlSugar](https://github.com/donet5/SqlSugar) - Provides ORM
- [LunarCore](https://github.com/Melledy/LunarCore) - Some data structures and algorithms
