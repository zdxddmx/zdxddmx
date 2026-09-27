# 张冬旭 · 嵌入式软件工程师（2027 届）

STM32 / ESP32 固件、嵌入式 Linux、工业通信协议与上位机。
按方向列代表作，每个仓库都带 README、调试记录与单元测试。

---

## 通信与协议

| 仓库 | 内容 | 测试 |
|---|---|---|
| [modbus-rtu-slave](https://github.com/zdxddmx/modbus-rtu-slave) | Modbus RTU 从机：FC 01/03/04/05/06/0x10、CRC-16、异常码、广播与错误帧静默策略 + STM32F103 接入示例（USART + DMA + IDLE 判帧） | 15 项用例 |
| [automotive-can-uds-lab](https://github.com/zdxddmx/automotive-can-uds-lab) | 手写 ISO-TP 传输层 + UDS 诊断栈，支持 SocketCAN / vcan | 159 项 |
| [iot-mqtt-ota-lab](https://github.com/zdxddmx/iot-mqtt-ota-lab) | MQTT 3.1.1 编解码、QoS1 发送窗口、OTA 镜像校验与 A/B 回滚 | 61 项 |
| [serial-data-gateway](https://github.com/zdxddmx/serial-data-gateway) | Linux/C++17 串口采集网关：CRC16 帧解析 + 有界队列三级流水线 + epoll 非阻塞 TCP 查询服务 | — |
| [mavlink-avionics-lab](https://github.com/zdxddmx/mavlink-avionics-lab) | MAVLink v2 帧编解码 + CRC_EXTRA + 流式解析 + 心跳监控与失联上锁 | 74 项 |
| [motor-ecu-base-sw](https://github.com/zdxddmx/motor-ecu-base-sw) | 车规风格底层软件：MCAL 端口层 + CDD 电机驱动 + ISO-TP + UDS + Bootloader 刷写 | — |

## 控制与电机

| 仓库 | 内容 | 测试 |
|---|---|---|
| [foc-motor-control-lab](https://github.com/zdxddmx/foc-motor-control-lab) | FOC：三相逆变 + SVPWM + Clarke/Park + 电流环速度环 PI（前馈解耦 / 弱磁）+ BLDC 六步换相 | 96 项 |
| [robot-motion-control](https://github.com/zdxddmx/robot-motion-control) | 机器人运动控制与安全内核：关节 Kp/Kd + S 曲线平滑插值 + 限位 / 姿态 / 通信 / 急停保护 | 135 项 |
| [digital-power-loop-sim](https://github.com/zdxddmx/digital-power-loop-sim) | Buck 变换器双闭环数字控制 + 电源状态机 + 保护逻辑 + 环路频域分析 | 34 项 |
| [second-gen-tea-picking-robot](https://github.com/zdxddmx/second-gen-tea-picking-robot) | STM32F407 + FreeRTOS：夹持力与位置双闭环 + 力反馈柔性夹持 + 分级保护（33 个提交） | 125 C + 22 Py |

## 嵌入式 Linux 与上位机

| 仓库 | 内容 |
|---|---|
| [esp-recorder](https://github.com/zdxddmx/esp-recorder) | ESP32-S3 双路串口 WiFi 数据记录仪：ESP-IDF + FreeRTOS（5 个任务）、环形缓冲 + 双条件落盘 + fsync、SD FATFS、USB CDC/MSC 复合设备、WiFi AP+STA 网页监控 |
| [upper-computer-control-lab](https://github.com/zdxddmx/upper-computer-control-lab) | C# 上位机：Modbus RTU 编解码 + 轮询调度（重试 / 降级 / 按点统计）+ WPF(MVVM) 界面 |
| [luckfox-pico](https://github.com/zdxddmx/luckfox-pico) | RV1106 嵌入式 Linux 平台实践：u-boot / Linux 5.10 / Buildroot 构建、设备树、字符设备驱动 |
| [dp-launcher](https://github.com/zdxddmx/dp-launcher) | 1:1 复刻投影仪 Android 桌面（Kotlin + RecyclerView），像素级对齐验证 |

## 竞赛与实物

| 仓库 | 内容 |
|---|---|
| [uav-car-adhesion-platform](https://github.com/zdxddmx/uav-car-adhesion-platform) | 无人机正压攀附平台：STM32F103 四舵轮车控固件 + PX4 覆盖层 + 失联保护 |
| [ai_logic_analyzer](https://github.com/zdxddmx/ai_logic_analyzer) | 瑞萨 RA6M5 手持逻辑分析仪：GPT 定时器 + DMA 连续采样、LVGL 触摸界面、Wi-Fi TCP、PySide6 自绘波形上位机 |
| [ch585m-tri-mode-hid-mouse](https://github.com/zdxddmx/ch585m-tri-mode-hid-mouse) | 沁恒 CH585M 三模 HID 鼠标：USB Full-Speed HID 1000 Hz / BLE HID / 2.4 GHz 私有协议 |
| [dual-cam-fpga-udp](https://github.com/zdxddmx/dual-cam-fpga-udp) · [zynq_pdm_mic_udp_pc](https://github.com/zdxddmx/zynq_pdm_mic_udp_pc) | FPGA 图像与音频链路：双路 OV5640 同步采集与千兆以太网传输、PDM 麦克风阵列 + CIC 抽取 + UDP |

---

**联系**：zdongxu17@gmail.com ｜ 电话见简历
