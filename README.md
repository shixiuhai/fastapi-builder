# 「 FastAPI Builder 」

<div align="right">
    <a href="https://fastapi.tiangolo.com/zh/"><b>fastapi 官方网站 ➡</b></a>
</div>

<br>

> 💡 **fastapi 项目构建器. 一款帮助你快速构建 fastapi 项目的工具.**

+ ***[特性](#-特性)***

+ ***[TODO](#-todo)***

+ ***[快速开始](#-快速开始)***

+ ***[特别感谢](#-特别感谢)***

+ ***[许可证](#-许可证)***

<div align="center">
    <img src="https://github.com/fmw666/my-image-file/blob/master/images/cute/small-cute-8.jpg" width=100>
</div>

<br>

## 💬 特性

+ 创建可自定义的 project 项目.

+ 创建可定制的 app 应用.

+ 为您生成完整的项目结构.

+ 可选的 Dockerfile.

+ 可选的 pre-commit.

<br>

## 🎯 TODO

<div align="right"><i><b><a href="#no-reply">PS: 期待您对本项目做出贡献...</a></b></i></div>

+ [ ] 完善项目框架代码部分

+ [ ] 完善项目框架文档部分

+ [ ] 提供英文版本

+ [ ] 提供项目数据库 PostgreSQL 选项

+ [ ] 提供完整的 run 方法

+ [ ] 内置 alembic 数据迁移等管理

<br>

## 🚀 快速开始

<div align="right">
<i><b>依赖：Python 3.6+</b></i>
<br>
<i>详细教程见：<b><a href="docs/tutorial.md">tutorial</a></b></i>
</div>

安装 `fastapi-builder` 项目：

```sh
pip install fastapi-builder
```

查看项目版本：

```sh
fastapi --version
```

项目帮助：

```sh
fastapi --help
fastapi startproject --help
```

创建 `fastapi` 项目：

```sh
fastapi startproject [name]

# or 带有交互选择

fastapi startproject [name] --interactive
```

创建 `fastapi` 应用：

```sh
fastapi startapp [name]
```

运行 `fastapi` 项目：

```sh
fastapi run
```

<br>

## ⚡ 特别感谢

项目配置生成及 questionary 内容基于项目：<https://github.com/ycd/manage-fastapi>

fastapi 项目基础框架参考：<https://github.com/nsidnev/fastapi-realworld-example-app/>

<br>

## 🚩 许可证

项目根据麻省理工学院的许可条款授权.
