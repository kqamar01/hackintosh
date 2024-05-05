# HP Elitedesk 800 G1 Tower Opencore

## Specification

| Item  | Details |
| ------------- | ------------- |
| Model  |  HP EliteDesk 800 G1 TWR  |
| Bios Ver. | L01 v02.71 |
| Processor | Intel(R) Core(TM) i7-4770 CPU @ 3.40GHz  |
| RAM  | 16GB DDR3-1333 |
| iGPU  | HD4600 |
| dGPU  | none |
| Main boot drive | 120 GB SSD 2.5 inch generic brand  |
| Opencore  | V 0.7.5 & V 0.9.9 |
| MacOS  | Monterey (12) |
| SMBIOS  | iMac16,2 |

* not using any wifi , only ethernet
* not using any iMessage or anything Apple ID related. 

## Setting UP

1. **Update your HP Elitedeks BIOS**. The easiest method is using the sp80501.exe (L01 v02.71) from HP software and driver download.
2. **Set up BIOS for macOS compatibility**. Enter BIOS and set : 
   - Disable VTD (This option is unavailable is you are on older BIOS version)
   - Disable Legacy boot.
   - Disable secure Boot.
   - Set SATA to ACHI (default valure in BIOS)
3. Copy EFI into USB.
4. Follow and understand **Dortania** guide.
5. Make sure to change serial. 

## Quirk 
1. V 0.9.9 OC increase boot time compared to v 0.7.5
2. Keynote app : Choosing to animate any object will make the app freeze and had to be forced quit V0.9.9
3. Some font and text menu will be rendered "funny" in V 0.9.9
4. Most app donloaded from App Store need at least Ventura (13). The workaround is to log into latest Mac (real or virtual) and download all the apps that you want. Log into Monterey and look up purchase history and download form there. I didnt test this. 
    
 ### Notes
* This is just a hobby of mine. I got this machine barebone for MYR 200 (USD 50) from local FB Marketplace. I wont maintain this. 
* Looking for AMD Radeon Pro WX4100/WX5100 for future upgrade into Ventura (13) or Sonoma(14) as it is single slot and doesnt need additonal PCIE power connector. 
* Regular RX400 and 500 series length (more than 7 inches) will interfere with SATA, front USB and Card reader connector on Motherboard, not to mention for PSU upgrade and proprietary HP connector adaptor.
* v0.7.5 is obtained from some reddit forum and had been closed. 
* Currently this machine running Ubuntu as it is much more reliable as daily driver than macOS. 
 
 
