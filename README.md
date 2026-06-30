# H723 RS485 Demo

基于 STM32H723 的 RS485 通信演示工程。

## 硬件平台

- MCU：STM32H723VGTx
- 开发环境：Keil MDK-ARM + STM32CubeMX

## 工程结构

```
Core/               # 用户代码（main.c、中断、HAL 配置等）
Drivers/            # CMSIS 和 STM32H7xx HAL 库
MDK-ARM/            # Keil 工程文件
H723_RS485_Demo.ioc # STM32CubeMX 配置文件
```

## 使用说明

1. 使用 **STM32CubeMX** 打开 `H723_RS485_Demo.ioc` 可重新生成代码。
2. 使用 **Keil MDK-ARM** 打开 `MDK-ARM/H723_RS485_Demo.uvprojx` 编译下载。

## Git 管理

- 主分支：`main`
- 远程仓库：`https://github.com/tianchen233455-hue/hello_world.git`

常用命令：

```bash
git status              # 查看状态
git add .               # 添加所有改动
git commit -m "描述"    # 提交
git push                # 推送到 GitHub
git pull                # 从 GitHub 拉取更新
```
