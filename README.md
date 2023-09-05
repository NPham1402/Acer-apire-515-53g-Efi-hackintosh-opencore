# Acer-apire-515-53g Laptop
Acer-apire-515-53g Laptop with OpenCore 0.9.4 bootloader  
Test for macOS bisgur and macOS 13.5

### Computer Spec:

| Component        | Specifications                         |
| ---------------- | ---------------------------------------|
| CPU              | Intel Core i5-8265U                    |
| iGPU             | Intel UHD Graphics 620                 |
| RAM              |  20GB DDR4 2666Mhz                     |
| NVMe             | Kioxia RC10 512GB / WD SN520 512GB     |
| LAN              | Realtek RTL8168G/8111G                 |
| Audio            | i don't know                           |
| WiFi & Bluetooth | BCM94360CSAX                           |
| SMBIOS           | Macbookpro 15.2                        |
| BootLoader       | OpenCore 0.9.4                         |

### What works:

- Full function

### BIOS Settings:

* Update BIOS to M1AKT50A  
* Disable: CSM   
* Boot this OpenCore
* Press the space bar
* Choose "SetupVar"
* Run code to set 64M DVMT:
```
setup_var 0x7AC 0x2   
```
* Reboot to install macOS



## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://github.com/dortania) for great and detailed guides.
