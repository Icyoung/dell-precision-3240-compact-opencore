# dell-precision-3240-compact-opencore
🍎 dell precision 3240 compact hackintosh

<img width="698" alt="info" src="https://user-images.githubusercontent.com/18390793/147809289-5c08fada-5afb-43fe-a0c8-d8e3813d01aa.png">
<img width="682" alt="info2" src="https://user-images.githubusercontent.com/18390793/147809296-6fdf1036-82fe-420a-a28c-599cde9e9c48.png">

## HARDWARE
* CPU: i7-10700
* Memory: 32G ddr4 3200 *2
* SSD: SM961 512G *2
* Wireless: BCM943602CS
* PCIe: Thunderbolt3 PCIe Card
* Extra: AMD Vega64 in eGPU

## PRE 
### tools: <a href="http://ruexe.blogspot.com/">RU.efi</a> 
| name     | form     | offset| value|
| -------- | -------- | ----- | ---- |
| CFG Lock | CpuSetup | 0x3E  | 0x00 |
| DVMT     | SaSetup  | 0xF5  | 0x02 | 

## NOT WORK
* Thunderbolt3 hotplug
