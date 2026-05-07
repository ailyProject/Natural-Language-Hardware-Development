# 用自然语言开发硬件

本书是一套面向所有硬件开发入门者和实践者的 Aily Blockly 教程。它以常见嵌入式入门路径为主线，覆盖开发环境、GPIO 输入输出、串口调试、模拟量与 PWM、传感器、执行器、通信接口、显示反馈、物联网和综合项目等内容。

和传统教程不同的是，本书把自然语言需求表达、AI 生成 Blockly/代码草稿、连线检查、编译上传、串口验证和问题排查放进每个知识点中。读者不只是学习“怎么让硬件运行”，也会学习如何把硬件需求说清楚，如何检查 AI 生成结果，如何在真实开发板上逐步验证和迭代。

本书也吸收了主流 LLM 在提示设计、结构化上下文、任务拆解、少样本示例、工具使用和结果验证方面的实践建议。书中会区分适合一次完成的短程任务，以及需要规划、分步执行和阶段验收的长程任务，并给出一套面向硬件开发的自然语言长程任务方法。

本书适合所有希望使用自然语言、Blockly 和 AI IDE 学习 MCU 硬件开发的人，也适合已经接触过 Arduino、单片机或创客硬件，希望把自己的开发流程升级为 AI 辅助方式的实践者。

## 目录

- [序章：从 AI 编程到自然语言开发硬件](00-preface.md)
- [教程大纲](00-outline.md)
- [第 1 章：从自然语言开始：认识工作台并点亮第一个项目](01-natural-language-hardware.md)
- [第 2 章：把需求说清楚，再生成程序](02-clear-requirements.md)
- [第 3 章：程序结构和 GPIO 输出](03-program-structure-gpio-output.md)
- [第 4 章：GPIO 输入、按键和消抖](04-gpio-input-button-debounce.md)
- [第 5 章：串口调试和问题排查](05-serial-debugging.md)
- [第 6 章：模拟输入和 PWM 输出](06-analog-pwm.md)
- [第 7 章：传感器数据读取和处理](07-sensor-data-processing.md)
- [第 8 章：执行器控制和电源安全](08-actuator-power-safety.md)
- [第 9 章：常见通信接口：I2C、SPI 和 UART](09-communication-interfaces.md)
- [第 10 章：显示屏、矩阵灯和人机反馈](10-display-feedback.md)
- [第 11 章：联网硬件和物联网应用](11-iot-networking.md)
- [第 12 章：库管理和 AI 转库](12-library-management-ai-migration.md)
- [第 13 章：综合项目一：环境监测站](13-environment-monitoring-project.md)
- [第 14 章：综合项目二：可交互控制作品](14-interactive-control-project.md)
- [第 15 章：可靠性、安全和发布前检查](15-reliability-safety-release.md)
