# proj-support-riscv-for-microblocks-wireless

### 项目名称
使用MicroBlocks无线控制RISC-V玩具车

### 项目描述
MicroBlocks是一个免费开源的图形化编程平台，可以对单片机进行编程操作。本项目的目标是实现MicroBlocks有线串口控制CSM32RV20开发板，再使用无线串口透技术和玩具车里的CSM32RV20开发板进行通信，以实现MicroBlocks无线控制RISC-V玩具车。

### 所属赛道
2024全国大学生操作系统比赛的“OS功能挑战”赛道

参赛要求
- 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的学生
- 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖 
- 请遵循“2024全国大学生操作系统比赛”的章程和技术方案要求 

### 项目导师
廖俊波
- github: https://github.com/DC-DeepComputing-Activity
- email: junbo.liao@deepcomputing.io

### 难度
高

### 特征
- 了解单片机
- 了解RISC-V体系
- CSM32RV20开发板是基于RISC-V的芯片
- 全球首款RISC-V笔记本电脑DC-ROMA上进行开发构建

### 参考文档
- MicroBlock工具和smallvm固件源码: https://bitbucket.org/john_maloney/smallvm
- MicroBlocks在线开发工具: https://www.microblocksfun.cn/run/microblocks.html
- PlatformIO CLI源码: https://github.com/platformio/platformio-core
- PlatformIO对SiFive的支持(仅供参考): https://github.com/platformio/platform-sifive

### License
MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)

## 预期目标
本项目分2个阶段

第一阶段: 构建固件
1. 在DC-ROMA笔记本上，使PlatformIO CLI或者IDE可以正常运行。
2. 完成PlatformIO对CSM32RV20开发板的支持。
3. 完成smallvm对CSM32RV20开发板的支持。
4. 在DC-ROMA笔记本上，实现PlatformIO构建用于CSM32RV20开发板的smallvm固件。
5. 确保固件能更新到CSM32RV20开发板中。

第二阶段: 控制玩具车
1. 实现CSM32RV20和CSM32RV20之间的无线串口透传(需借助两个无线串口通信模块来实现)。
2. 使用USB串口线连接开发板和DC-ROMA笔记本，实现MicroBlocks对CSM32RV20的有线控制。
3. 基于无线串口透传技术，在DC-ROMA笔记本上实现MicroBlocks无线控制玩具小车。
