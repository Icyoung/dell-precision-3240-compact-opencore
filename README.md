# dell-precision-3240-compact-opencore
🍎 dell precision 3240 compact hackintosh
![image](https://user-images.githubusercontent.com/18390793/147807722-b95d9d41-6516-4334-8c67-843b7e83cb2a.png)

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
