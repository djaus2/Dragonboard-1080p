# Dragonboard-1080p
Enable a Qualcomm DragonBoard 410c to use 1920x1080 instead of 1280x720 as display resolution when running Windows 10 IoT-Core

**1080p** (1920x1080 px; also known as full HD or FHD and BT.709) is a set of HDTV high-definition video modes characterized by 1080 horizontal lines of vertical resolution;[1] the p stands for progressive scan, i.e. non-interlaced. The term usually assumes a widescreen aspect ratio of 16:9, implying a resolution of 2.1 megapixels. It is often marketed as full HD, to contrast 1080p with 720p resolution screens.
*From Wikipedia*

The **Qualcomm DragonBoard 410c** Windows 10 IoI-Core image only supports 1280x720 screen resolution. It has been noted that is possible to modify the BSP so as to support the higher resolution 1080p. Whist it might be a simple as making some modification to the OS as distributed, or to run an app, it seems that a rebuild of the BSP is required. Whether this can be done in a public manner (you have to be registered to get tyeh BSP source) remains to be seen.

## In Brief
It has been suggested that the ACPI table in the BSP need modification.

## How to Contribute
Please contribute discussion points as Issues.  
To upload code to the repository please request to added to the project's contributors.  
Sure Fork Off and then Pull Request as well.

For detailed information that you can add, aim to get it in the Wiki.

Thanks

## Links
[About The DragonBoard](https://developer.qualcomm.com/hardware/dragonboard-410c)  
[DragonBoard  OS Binary](http://go.microsoft.com/fwlink/?LinkID=708576)  
[The BSP](https://developer.qualcomm.com/download/db410c/windows-10-iot-core-bsp.zip)  
[DragonBoard BSP Customisation Guide](https://developer.qualcomm.com/download/db410c/windows-10-iot-bsp-customization-guide.pdf)  
[DragonBoard Update Tool x86](https://developer.qualcomm.com/download/db410c/windows-10-iot-update-tool-dragonboard-410c-x86.zip)  
[DragonBoard Update Tool x64](https://developer.qualcomm.com/download/db410c/windows-10-iot-update-tool-dragonboard-410c-x64.zip)  
[DragonBoard Getting Started](https://developer.microsoft.com/en-us/windows/iot/Docs/GetStarted/dragonboard/stable/GetStartedStep1.htm)   
[Download and install Windows 10 IoT Core Dashboard](http://go.microsoft.com/fwlink/?LinkID=708576)  

