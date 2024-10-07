# Hackintosh EFI for MSI MAG B460M MORTAR WIFI + i5-10400 + UHD630

## 硬件

| 硬件 | 名称 |
| ---- | --- |
| CPU  | i5 10400 |
| 主板 | 微星MAG B460M MORTAR WIFI |
| 显卡 | Intel UHD Graphics 630 |
| 机型 | iMac 20,1 |
| 网卡 | 奋威T919 |

## BIOS 设置

1. **Settings\高级\PCIe/PCI 子系统设置**

Above 4G memory/Crypto Currency mining -> 允许

Re-Size BAR Support ->允许

2. **Settings\高级\整合周边设置\SATA设置**

SATA模式 -> AHCI 模式

3. **Settings\高级\内建显示配置**

设置第一显示 -> IGD

集显共享内存 -> 64MB

4. **Settings\高级\USB 设置**

XHCI Hand-off -> 允许

5. **Settings\高级**

BIOS CSM/UEFI Mode -> UEFI

6. **Settings\启动**

快速开机 -> 禁止 

7. **Settings\安全\安全引导**

安全启动 -> 禁止

8. **Settings\安全\Trusted Computing**

Security Device Support -> 禁止

9. **Overclocking\CPU 特征**

Intel 虚拟化技术 ->允许

Intel VT-D 技术 -> 禁止

CFG 锁定 -> 禁止

SW Guard Extensions(SGX)  -> 禁止
