<h1 align="center" >Neovim configuration</h1>

<p align="center">
 <img alt="banner_01" src="https://img.shields.io/github/last-commit/EddyBel/NeoVim-config?color=%23AED6F1&style=for-the-badge" />
 <img alt="banner_02" src="https://img.shields.io/github/license/EddyBel/NeoVim-config?color=%23EAECEE&style=for-the-badge" />
 <img alt="banner_03" src="https://img.shields.io/github/languages/top/EddyBel/NeoVim-config?color=%23F9E79F&style=for-the-badge" />
 <img alt="banner_04" src="https://img.shields.io/github/languages/count/EddyBel/NeoVim-config?color=%23ABEBC6&style=for-the-badge" />
 <img alt="banner_05" src="https://img.shields.io/github/languages/code-size/EddyBel/NeoVim-config?color=%23F1948A&style=for-the-badge" />
</p>

<p align="center" >Personal neovim configuration</p>

![Preview Proyect](./assets/capture_3.png)
![Preview proyect2](./assets/capture_4.png)

This repository contains my custom configuration for Neovim, an advanced text editor that can be turned into a powerful integrated development environment (IDE). With my configuration, Neovim becomes a virtually full-featured IDE, supporting multiple programming languages and offering a smooth and agile user experience thanks to the use of the **[Lazy](https://github.com/folke/lazy.nvim)** plugin manager. You'll find everything you need to start working with Neovim right away, from installing plugins to customizing keyboard shortcuts and display options - enjoy the productivity Neovim has to offer!

## 😸 Why ?

This repository was created to share my custom configuration of Neovim, an advanced text editor that I have used for a long time for my daily programming work. I have spent many hours customizing and refining my configuration to make Neovim perfectly suited to my needs, and I think other programmers could benefit from it.

My goal in sharing this configuration is to help others get a more productive and efficient programming experience in Neovim by providing a solid and customizable foundation for using this powerful text editor. In addition, the use of the Lazy plugin manager ensures that the setup is easy to install and maintain, which should save users time and effort.

I hope this Neovim setup will be useful to other programmers and allow them to enjoy the productivity that this advanced text editor can offer.

## 🔨 Requirements

In order to be able to use the code editor correctly, it is necessary to have some programs previously installed.

- [Neovim](https://github.com/neovim/neovim)
- [NodeJS](https://nodejs.org/en/)
- [Python](https://www.python.org/)
- [Compiler C++](./docs/Instalar%20compilador%20de%20C%2B%2B.md)

## 🦉 Features

- [x] Support for multiple programming languages.
  - [x] JavaScript
  - [x] HTML
  - [x] CSS
  - [x] Python
  - [x] Lua
  - [x] Vim Script
  - [x] JSON
  - [x] C
  - [x] C++
  - [x] C#
  - [x] SQL
  - [x] Dockerfiles
  - [x] YAML
  - [x] Markdown
  - [x] Rust
  - [x] Typescript
  - [x] Java
- [x] Code formatting for multiple languages.
- [x] Syntax coloring.
- [x] Information related to the project git repository, git version management.
- [x] Keyboard shortcuts similar to those of VSCode
- [x] Code autocompletion and snippets.

## 🧪 How to install

The first thing is to have neovim installed and to have the necessary configuration folder to save the files, if your system is **Windows** you can find the folder in `C:\Users$USER\AppData\Local\Nvim` and if your system is **Linux** you can find the folder in `~/.config/nvim `

Once everything is ready you can clone the github repository of the configuration and enter the repository folder.

```bash
git clone https://github.com/EddyBel/NeoVim-config.git
cd NeoVim-config
```

The next step is to copy the configuration files **init.lua**, **lua** and **lazy-lock.json** to the neovim configuration folder.

For the language servers there is the Mason Plugin, this plugin allows you to download with a simple command the servers for syntax autocompletion.

The plugin comes preloaded with the most common languages to use, but you can add the ones you need in the [mason.lua](./lua/plugins/mason.lua) configuration files.

You can install other programming languages you need as indicated in the [lsp-config](https://github.com/neovim/nvim-lspconfig) repository, the language configuration file is located inside the specific plugins folder [lsp.lua](./lua/plugins/lsp.lua), you can integrate there the language you need.

The next step is to install the code formatters for each language, the ones that are configured are Prettier for html, javascript, css, autopep8 for python etc. You can see more information in the [Neoformat.lua](./lua/plugins/neoformat.lua) file.

You can install them as follows:

[Prettier](https://prettier.io/docs/en/install.html) (JAVASCRIPT, HTML, CSS, SCSS, JSON, JAVA, KOTLIN, LESS, MARKDOWN, PHP, RUBY, TYPESCRIPT, XML, YAML)

```bash
npm i -g prettier
```

[Autopep8](https://pypi.org/project/autopep8/) (Python)

```bash
pip install autopep8
```

[Clang-format](https://pypi.org/project/clang-format/#description) (C, C++, C#)

```bash
pip install clang-format
```

Finally, just run neovim and Lazy will install and download all the listed plugins.

> ### Note
>
> Sometimes it is necessary to add to the terminal path of your system the necessary programs either python scripts or servers downloaded by Mason.

## 🎢 Project status

The project is constantly changing because it is my usual code editor and I will be improving and adding things as I see fit.

## 📑 LICENCE

This project is released under the terms of the MIT license. The MIT license allows users to use, copy, modify and distribute the source code of the project with certain restrictions and requirements. For more information on the terms and conditions of the MIT license, please refer to the license file included with this project or visit https://opensource.org/licenses/MIT.

---

<p align="center">
  <a href="https://github.com/EddyBel" target="_blank">
    <img alt="Github" src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" />
  </a> 
  <a href="https://www.linkedin.com/in/eduardo-rangel-eddybel/" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />
  </a> 
</p>
