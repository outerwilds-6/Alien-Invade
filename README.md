## 简介

一款基于Pygame的简单小游戏

## 环境配置

先使用 `conda` 安装虚拟环境，然后在虚拟环境中使用 `pip` 管理需要的包。

这些方法均已在 `Windows` 平台上试验过，如在其他操作系统上出现问题，还请开 `issue` 帮助我完善这个项目。

### 安装Python环境

建议采用 `conda` 安装 `Python 3.11` 虚拟环境，若已安装可以跳过。
在命令行中运行：

```shell
conda create --prefix .\\env python=3.11
```

若出现 `conda` 不存在之类的提示，建议切换到 `conda` 安装目录后运行下面的指令以完成 shell association，然后切回仓库目录重试上面的指令。

```shell
conda init
```

### 安装相应包

如果你使用了 `conda` 管理虚拟环境，先执行这条命令进入 `Python` 上下文：

```shell
conda activate .\\env
```

进入 `Python` 上下文后执行这条命令安装必要的包：

```shell
pip install -r requirements.txt
```

## 运行游戏

运行 `main.py` 开始游戏。

```shell
python main.py
```

## 参考项目

+ [Python Crash Course - Third Edition](https://github.com/ehmatthes/pcc_3e)
