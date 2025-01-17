<div align="center" class="has-mb-6">

![logo][logo]

## :wrench: H7-TOOL 多功能开发工具

[淘宝链接][淘宝链接] |
[开发文档][开发文档] |
[论坛][论坛]

![H7-TOOL_IMG][H7-TOOL_IMG]

</div>

### :book: 简介 / Overview

为单片机工程师提供一款实用的多功能开发调试工具。

相信很多人有带板子回家调试、或带板子出差调试的情况。因为产品问题是无法预知的，多半情况不可能带齐全套测试工具的。经常遇到手边缺万用表、缺示波器、缺串口线、缺逻辑分析仪而导致工作很难继续。

`H7-TOOL` 是一款多功能测试工具，体积和 `J-Link` 一样大，方便携带。手边常备一个以备不时之需。

### :gift: 功能特性 / Features

1. 双通道虚拟示波器
2. 8 通道逻辑分析仪
3. USB-RS485 转换器
4. USB-RS232 转换器
5. USB-TTL 串口转换器
6. USB-CAN 转换器
7. 联机烧录器（内置 CMSIS DAP 下载器）
8. 脱机烧录器
9. I2C 控制器
10. SPI 控制器
11. GPIO 输入输出
12. 模拟信号发生器
13. PWM 发生器
14. 脉冲计数器（编码器输入）
15. 频率计
16. 负载电流波形测试仪（测量电压、电流，计算功率）

### :construction: 任务列表 / TODO
<!-- 以下为示例 -->
- [ ] DAP-Link
  - [x] DAP-Link 移植
  - [ ] DAP-Link 测试
  - [ ] `Wi-Fi` 无线调试
- [ ] 脉冲计数器（编码器输入）

### :warning: 注意事项 / Attention

1. KEIL MDK5 工程
2. 单片机 `STM32H750IBK6`
3. 程序定位地址（FLASH）：`0x0802 0000`，容量 2MB - 128KB
4. MDK 中 FLASH 配置使用 STM32H743 配置，强行使用 2MB Flash
5. 源文件编码为 `UTF-8`，缩进 `4` 个空格

### :scroll: 修改记录 / CHANGELOG

[查看更新日志][更新日志]

### :page_with_curl: 许可证 / LICENSE
<!-- License 类型可能需要更改， LICENSE 文件需要生成。 -->
This project is licensed under the `MIT License` - see the [LICENSE][许可证] file for details.

<!-- 以下内容为 Markdown 文档描述中出现的链接所指向的地址，统一在文档末尾进行管理。 -->
<!-- Markdown 超链接管理 -->
[淘宝链接]: https://item.taobao.com/item.htm?id=602704490583 "跳转到 H7-TOOL 购买链接"
[开发文档]: /Doc "查看开发文档"
[论坛]: http://www.armbbs.cn
[更新日志]: ./CHANGELOG "点击查看更新日志"
[许可证]: ./LICENSE

<!-- Markdown 图片链接管理 -->
[logo]: ./Armfly_Logo.png "安富莱 Armfly"
[H7-TOOL_IMG]: ./H7-Tool.jpg "H7-TOOL 多功能开发工具"
