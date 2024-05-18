---
title: Phaten matter WB03A-8684H2V1 module material
---
# Matter WB03A-8684H2V1 module material

## 1. Product description
### 1.1 Product description
 WB03A-8684H2V1 is a low power consumption embedded Wi-Fi4 and BLE5 IOT dual-mode module. It consists of a highly integrated radio frequency (RF) wireless core, the ESP8684, and the WB03A-8684H2V1.
It consists of a highly integrated wireless RF chip, ESP8684, and a small number of peripheral devices, supports STA/AP/STA+AP operation modes, and low-power Bluetooth connectivity at the same time.
 The WB03A-8684H2V1 includes a 32-bit MCU running at up to 120 MHz, a 1T1R WLAN, 272 KB of SRAM and 2 MB of internal Flash, and a rich set of peripherals.
2MB Flash and rich peripheral resources.
 The WB03A-8684H2V1 is an RTOS platform with integrated libraries for all Wi-Fi MAC and TCP/IP protocols. Users can develop their own applications based on the WB03A-8684H2V1.
The H682-84V1 is an RTOS platform that integrates all Wi-Fi MAC and TCP/IP protocol libraries, and can be used to develop embedded Wi-Fi products that meet your needs.

### 1.2 Product Features

- Built-in low-power 32-bit MCU that can be used as an application processor.
- Supports 120MHz mains frequency
- Operating Voltage: 3V to 3.6V
- Wi-Fi connectivity
    - IEEE 802.11b/g/n
    - Channel 1-14 @ 2.4GHz (CH1-11 for US/CA, CH1-13 for EU/CN, CH1-14 for JP) 
    - Supports WEP/WPA/WPA2/WPA2 PSK(AES) and WPA3 security modes.
    - Supports STA/AP/STA+AP operating modes.
    - Supports Bluetooth, SmartConfig, and AP for both mesh methods (both Android and IOS devices).
- PCB on-board antenna
- Operating temperature: -40°C to 105°C
- Bluetooth connectivity
    - Low power consumption Bluetooth BLE5
    - Complete Bluetooth coexistence connector

### 1.3 Specification

| Item | Description |
| --- | --- |
| Product Name | WB03A-8684H2V1 |
| Product Description | Wi-Fi4 and BLE5 IOT Dual Mode Module |
| Encapsulation Type | SMT Stamp Hole/Pin Hole |
| Eco-Friendly Note | All hardware components are fully compliant with EU RoHS |


### 1.4 Absolute Electrical Parameters

| Parameters | Description | Numerical values | Maximum values | Units |
| --- | --- | --- | --- | --- | 
| Ts | Storage Temperature | -40 | 150 | ℃ |
| VBAT | Supply Voltage | -0.3 | 3.6 | V |
| Static Discharge Voltage (My Body Model) | TAMB -25 °C | -2 | 2 | KV |
| Static Discharge Voltage (Machine Models) | TAMB -25°C | -500 | 500 | V |


### 1.5 Normal operating conditions

| Parameters | Description | Minimum | Standard | Maximum | Units | 
| --- | --- | --- | --- | --- | --- |
| Ta | Operating Temperature | -40 | - | 105 | ℃ | VBAT | Operating Voltage | 3 | 3.3 | 3.6 | V |
| VBAT | Operating Voltage | 3 | 3.3 | 3.6 | V |
| VOL | IO Low Level Output | - | 0.1×VDD1 | - | V |
| VOH | IO high level output | 0.8×VDD1 | - | - | V |
| I | IO drive current | - | 40 | - | mA |

<!-- ## 2、射频参数
### 2.1 Wi-Fi射频性能

Wi-Fi基本射频性能

| 产品特性 | 产品描述 |
| --- | --- |
| ⽆线标准 | IEEE 802.11 b/g/n |
| ⼯作频率 | 2.400 GHz ~ 2.4835 GHz (2.4 GHz ISM Band) |
| 调制⽅法 | DSSS,DBPSK, DQPSK, CCK and OFDM (BPSK/QPSK/16-QAM/ 64-QAM) |
| Wi-Fi通道 | Channel 1-14@2.4GHz(CH1-11 for US/CA, CH1-13 for EU/CN, CH1-14 for JP) |
| 天线类型 | PCB板载天线 |

Wi-Fi发射性能

| TX | 最⼩值 | 典型值 | 最⼤值模式 | 单位 |
| --- | --- | --- | --- | --- |
| 802.11b@1Mbps EVM≤-21dB | - | 21 | - | dBm |
| 802.11b@11Mbps EVM≤-21dB | - | 21 | - | dBm |
| 802.11g@54Mbps EVM≤-25dB | - | 19 | - | dBm |
| 802.11g@6Mbps EVM≤-5dB | - | 21 | - | dBm |
| 802.11n@HT20 MCS0 EVM≤-5dB | - | 20 | - | dBm |
| 频偏误差 | -12 | - | 12 | ppm |

Wi-F接收性能

| | RX | 典型值 | 单位 |
| --- | --- | --- |
| 802.11b@11Mbps PER≤10% | -90 | dBm |
| 802.11n@HT20 MCS7 PER≤10% | -74 | dBm |
| 802.11g@54Mbps PER≤10% | -77 | dBm |

### 2.2 蓝⽛技术指标

蓝⽛基本规格

| 产品特性 | 产品描述 |
|---------|---------|
| 蓝⽛规格 | BLE5    |
| ⼯作频率 | 2.402~2.480GHz |

蓝⽛发射性能

| TX | 最⼩值 | 典型值 | 最⼤值 | 单位 |
|----|-------|-------|-------|-----|
| 发射功率 | -24 | - | 21 | dBm |
| 连接速率 | - | 1 | - | Mbps |
| 连接速率 | - | 1 | - | Mbps |

蓝⽛接收性能

| RX | 典型值 | 单位 |
|----|--------|-----|
| 灵敏度 @ PER≤1% | ≤-85 | dBm | -->

<!-- ## 3、天线信息
### 3.1 天线类型

PCB板载天线

### 3.2 天线设计注意事项
 当Wi-Fi模组上使⽤PCB 板载天线时，为确保Wi-Fi 性能的最优化，建议模组天线部分和其他⾦属件距
离⾄少在15mm 以上。⽤⼾PCB 板在天线区域勿⾛线甚⾄覆铜，以免影响天线性能。

![](/assets/images/matter/板载天线.png) -->

## 2. Pin Definition
### 2.1 Pin Layout

![](/assets/images/matter/8684-01c管脚.png)

### 2.2 Pin Descriptions

| Serial No. | Name | Type | Function |
| ---- | ---- | ---- | ---- |
| 1 | IO0 | I/O/T | GPIO0, ADC1_CH0 |
| 2 | IO1 | I/O/T | GPIO1, ADC1_CH1 |
| 3 | EN | I | High: Disk enable; Low: Disk disable; internal pull-up default. |
| 4 | IO2 | I/O/T | GPIO2, ADC1_CH2, FSPIQ |
| 6 | IO5 | I/O/T | GPIO5, FSPIWP, MTDI, LED PWM |
| 7 | IO6 | I/O/T | GPIO6, FSPICLK, MTCK, LED PWM |
| 8 | 3V3 | P | electricity supply |
| 9 | NC | -- | blank pin |
| 10 | NC | -- | blank pin |
| 11 | NC | -- | blank pin |
| 12 | IO18 | I/O/T | GPIO18 |
| 5 | IO4 | I/O/T | GPIO4, ADC1_CH4, FSPIHD, MTMS, LED PWM |
| 13 | NC | -- | blank pin |
| 14 | NC | -- | blank pin |
| 15 | GND | P | earth (electric connection) |
| 16 | IO7 | I/O/T | GPIO7, FSPID, MTDO, LED PWM |
| 17 | IO8 | I/O/T | GPIO8 |
| 18 | IO9 | I/O/T | GPIO9 |
| 19 | IO10 | I/O/T | GPIO10, FSPICS0, LED PWM |
| 20 | IO3 | I/O/T | GPIO3, ADC1_CH3, LED PWM |
| 21 | RXD0 | I/O/T | GPIO19, U0RXD |
| 22 | TXD0 | I/O/T | GPIO20, U0TXD |
| 23 | GND | P | earth (electric connection) |

## 3. Module Size and PCB Package Graphics
### 3.1 Module Size
PCB Size ：24±0.3(L)X16±0.3(W)X0.8±0.1(H)
![](/assets/images/matter/8684-01c尺寸.png)

## 4. Product Packaging Information

Pallet + outer box packaging

## More information

[For detailed datasheet, please go to Matter module datasheet download page](../../download/matter/socket1_5_datasheet.md)