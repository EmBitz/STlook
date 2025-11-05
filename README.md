# STlook: A Look-Alike STLink Firmware

This repository hosts the ongoing development of **STlook**, a look-alike STLink firmware.  

The project will begin with the **USB Full-Speed (FS, V2)** version on its original platform, **STM32F1**, followed by the **USB High-Speed (HS, V3)** version on **STM32F7**.

### Why a "software clone"?

Beyond being fun to develop, a **software clone** is useful because it provides full control over the probe's firmware. This allows the project to be **ported to other MCUs and manufacturers**, and enables the addition of **features and enhancements** that are not available in the original software.  

By leveraging the existing command structure, development can proceed quickly, and all necessary test tools are readily available through existing GDB servers, such as **EBlink**.  

This project is primarily for **educational fun**, but it also aims to deliver a **truly useful result**.
