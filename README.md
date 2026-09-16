# zdxddmx

做嵌入式固件、FPGA 数字设计和配套的上位机工具。参加过全国大学生电子设计竞赛和全国大学生智能汽车竞赛。

## 在做的事

- **嵌入式固件** — 8051 与 Cortex-M 裸机开发。定时器中断调度、编码器测速、PID 与串级控制、串口与无线通信
- **FPGA 数字设计** — Verilog RTL、时序约束、图像采集与 UDP 传输、以太网协议
- **上位机与工具** — Python 实时波形与数据处理、代码生成

## 项目

### 竞赛

- [2026-smart-car-stc32g](https://github.com/zdxddmx/2026-smart-car-stc32g) — 智能汽车竞赛电磁组固件。STC32G 四路电感循迹、IMU 姿态积分、环岛状态机
- [smartcar-hardware](https://github.com/zdxddmx/smartcar-hardware) — 电磁组自研板卡。DRV8701 双驱、运放、四路循迹模块，立创 EDA 设计
- [2026-nuedc-steel-ball-control](https://github.com/zdxddmx/2026-nuedc-steel-ball-control) — 电赛 H 题车载平衡滚球。MaixCAM2 视觉检测，位置 / 球速 / 管角速度三级串级控制
- [2025-nuedc-line-following-car](https://github.com/zdxddmx/2025-nuedc-line-following-car) — 电赛循迹小车。MSPM0G3507 编码器速度环、陀螺仪航向修正、灰度循迹

### FPGA / Zynq

- [zynq_pdm_mic_udp_pc](https://github.com/zdxddmx/zynq_pdm_mic_udp_pc) — Zynq-7020 采集 PDM 麦克风，CIC 抽取滤波还原 PCM，经 UDP 上传
- [dual-cam-fpga-udp](https://github.com/zdxddmx/dual-cam-fpga-udp) — 双路 OV5640 同步采集与 UDP 图像传输
- [anlogic_fpga_vision_udp](https://github.com/zdxddmx/anlogic_fpga_vision_udp) — 安路 FPGA 图像采集与数码管识别
- [zynq7020-tracking-car](https://github.com/zdxddmx/zynq7020-tracking-car) — Zynq-7020 循迹车主控板原理图

### 工具

- [mcu-code-generator](https://github.com/zdxddmx/mcu-code-generator) — MCU 外设配置代码生成
- [ai_logic_analyzer](https://github.com/zdxddmx/ai_logic_analyzer) — 逻辑分析仪，瑞萨 RA 主控配上位机
- [ch585m-tri-mode-hid-mouse](https://github.com/zdxddmx/ch585m-tri-mode-hid-mouse) — 沁恒 CH585M 三模 HID 鼠标

## 常用

`C` `Verilog` `Python` `Keil MDK` `Vivado` `立创EDA`

---

<sub>番龄比码龄长。</sub>
