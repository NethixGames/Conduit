<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/NethixGames/Conduit">
    <img src="https://static.wikia.nocookie.net/minecraft_gamepedia/images/a/a8/Conduit_BE1.gif" alt="Logo" width="160" height="160">
  </a>

<h3 align="center">Conduit</h3>

<p align="center">
  Minecraft: Bedrock Edition server software written in Python
</p>

[![Minecraft - Version](https://img.shields.io/badge/minecraft-v1.20.81%20(Bedrock)-green)](https://feedback.minecraft.net/hc/en-us/sections/360001186971-Release-Changelogs)
[![GitHub License](https://img.shields.io/github/license/NethixGames/Conduit)](LICENSE)
[![Codacy Badge](https://img.shields.io/codacy/grade/8877402fc70b40f5a8c4b325d890e3f7?logo=codacy)](https://app.codacy.com/gh/NethixGames/Conduit/dashboard)

[//]: # ([![Discord]&#40;https://img.shields.io/discord/1215927956367740959?logo=discord&logoColor=white&color=5865F2&#41;]&#40;https://discord.gg/QJfCkbP4qw&#41;)

</div>

## 📄 Table of Contents

- [📖 Introduction](#-introduction-)
- [🛠️ Get started](#-get-started-)
- [🔌 Functionality](#-functionality-)
- [🙌 Contributing](#-contributing-)
- [⭐ Stars evolution](#-stars-evolution-)
- [🎫 License](#-license-)

## 📖 Introduction [🔝](#-table-of-contents)

Conduit is a Minecraft Bedrock Edition server software written in Python aiming to be Fast, Simplicity, Friendly plugin
development. This project meant to learn some minecraft mechanics, and it's personal project
by [Mitho Mizuno](https://github.com/mithomizuno),
so you don't expect this server software has continues updates.

## ️🛠️ Get started [🔝](#-table-of-contents)

Before getting started, verify that you have these installed on your system:

- Python ^3.12.0
- Poetry ^1.8.0

First, clone the repository and change to Conduit directory:

```shell
git clone https://github.com/NethixGames/Conduit.git
cd Conduit
```

Then, set your poetry to in-project environment:

```shell
poetry config virtualenvs.in-project true
```

Then, you need to install all the requirements using poetry and use conduit virtual environment:

```shell
poetry install
poetry shell
```

After that, you can run the server now:

```shell
poetry run conduit
```

## 🔌 Functionality [🔝](#-table-of-contents)

Currently, the Conduit project is under active development, and we invite you to review our roadmap.

| Milestone                 | Completion Time | Status | Version |
|:--------------------------|:---------------:|:------:|:-------:|
| **Raknet Implementation** |      ----       |   🚧   |  ----   |
| **MOTD**                  |      ----       |   ⏳    |  ----   |
| **Game Protocol**         |      ----       |   ⏳    |  ----   |
| **Plugins**               |      ----       |   ⏳    |  ----   |
| **Permissions**           |      ----       |   ⏳    |  ----   |
| **Login**                 |      ----       |   ⏳    |  ----   |
| **Commands**              |      ----       |   ⏳    |  ----   |
| **World Generation**      |      ----       |   ⏳    |  ----   |
| **Mobs**                  |      ----       |   ⏳    |  ----   |

Here's a legend to guide you:

- ✅: Task is completed. Woohoo! 🎉
- 🚧: Task is under way. We're on it! 💪
- ⏳: Task is up next. Exciting things are coming! 🌠

## 🙌 Contributing [🔝](#-table-of-contents)

We warmly welcome contributions to the Conduit project! If you're enthusiastic about enhancing Minecraft
Servers with Python and have ideas on how to improve Conduit, here are a few ways you can contribute:

1. **Reporting Bugs** <br /> If you encounter any bugs while using Conduit, please open
   an [issue](https://github.com/NethixGames/Conduit/issues) in
   our GitHub repository. Ensure to include a detailed description of the bug and steps to reproduce it. <br />
   <br />
2. **Submitting a Pull Request** <br /> We appreciate code contributions. If you've fixed a bug or implemented a new
   feature, please submit a pull request!
   Please ensure your code follows our coding standards and include tests where possible.

## ⭐ Stars Evolution [🔝](#-table-of-contents)

This will be a like indicator for this project. if you like it, don't forget to click the star button
[![Stargazers over time](https://starchart.cc/NethixGames/Conduit.svg?variant=adaptive)](https://starchart.cc/NethixGames/Conduit)

## 🎫 License [🔝](#-table-of-contents)

The Conduit project is licensed under the [MIT License](LICENSE). This is not an official Minecraft product and not
approved/associated with Mojang