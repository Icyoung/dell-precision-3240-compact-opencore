# dell-precision-3240-compact-opencore
🍎 dell precision 3240 compact hackintosh

<img width="698" alt="截屏2021-12-31 下午2 40 58" src="https://user-images.githubusercontent.com/18390793/147807940-9422c0b9-3585-417d-9dc0-2e565149b21c.png">

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
