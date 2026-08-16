# Awesome-Embedded with stars

A curated list of awesome embedded resource.

Table of content

* [Awesome-Embedded](#awesome-embedded)
  * [Interview](#interview)
  * [Embedded Software Skill](#embedded-software-skill)
  * [Common](#common)
  * [MCU programming](#mcu-programming)
    * [Bare-metal programming (Don't need MCU)](#bare-metal-programming-dont-need-mcu)
    * [MSP430](#msp430)
    * [TM4C123](#tm4c123)
    * [MSP432](#msp432)
    * [STM32](#stm32)
    * [STM32F7](#stm32f7)
    * [STM8](#stm8)
    * [ESP8266](#esp8266)
  * [Raspberry](#raspberry)
  * [Beaglebone](#beaglebone)
  * [Linux Kernel and device driver development](#linux-kernel-and-device-driver-development)
  * [Assembly](#assembly)
  * [RTOS](#rtos)
  * [Automotive](#automotive)
  * [OS](#os)
  * [WindowCE](#windowce)
  * [Compiler](#compiler)
  * [Bootloader](#bootloader)
  * [Makefile](#makefile)
  * [Peripheral](#peripheral)
    * [Memory Protection Unit](#memory-protection-unit)
    * [USB](#usb)
  * [Others](#others)
  * [Embedded GUI Development](#embedded-gui-development)
  * [Machine Learning & AI on MCU](#machine-learning--ai-on-mcu)
  * [Utilities](#utilities)
  * [Tips & tricks](#tips--tricks)
* [Tech blogs](#tech-blogs)
  * [FAQ\_Embedded](#faqembedded)
  * [Looking for more lists like this?](#looking-for-more-lists-like-this)
  * [BOOKs](#books)

## Interview

* [Embedded Interview Questions](https://docs.google.com/document/d/18HMyd-lFu1hWiixFLS2Pc7-SgyzDDqitzXbfAnUVeBE/mobilebasic)
* [Interview Questions Archive by Company](https://docs.google.com/document/d/1uW030FMfBxKLxXz-eIwyzlMJdERN5DMEwtUnJMYsF-g/edit?usp=sharing)
* [Coding Interview University](https://github.com/jwasham/coding-interview-university) ⭐ 358,944 | 🐛 123 | 📅 2025-08-28 - A complete computer science study plan to become a software engineer.

## Embedded Software Skill

* [16 Essential Skills for Embedded Engineer](https://swedishembedded.com/insights-build-embedded-systems/)
* [How to be low-level programmer](https://github.com/gurugio/lowlevelprogramming-university) ⚠️ Archived
* [Programmer Competency Matrix](https://www.sijinjoseph.com/programmer-competency-matrix/)

## Common

* [Integer size in C on 32-bit and 64-bit system](https://usrmisc.wordpress.com/2012/12/27/integer-sizes-in-c-on-32-bit-and-64-bit-linux/)
* [TeraTerm - TTL command reference](http://ttssh2.osdn.jp/manual/en/macro/command/index.html)
* [TeraTerm Scripts](http://processors.wiki.ti.com/index.php/Teraterm_Scripts)
* [Linker Command File Primer](http://processors.wiki.ti.com/index.php/Linker_Command_File_Primer)
* [The C build process](https://blog.feabhas.com/2012/06/the-c-build-process/)
* [Building Bare-Metal ARM Systems with GNU](https://www.embedded.com/design/mcus-processors-and-socs/4026111/Building-Bare-Metal-ARM-Systems-with-GNU-Part-9)
* [ELF – Executable and Linkable Format](https://2wisebit.wordpress.com/2018/06/08/elf-executable-and-linkable-format/)
* [Toolchains](https://web.eecs.umich.edu/~prabal/teaching/resources/eecs373/toolchain-notes.pdf)
* [What is an application binary interface (ABI)?](https://stackoverflow.com/questions/2171177/what-is-an-application-binary-interface-abi)
* [ARM Cortex M4 Blink Example (Linker Script)](http://robotics.mcmanis.com/src/arm-blink/linker-script.html)
* [A Sample Linker Script](http://hertaville.com/a-sample-linker-script.html)
* [Linking and Loading](http://www.iecc.com/linker/linker01.html)
* [Embedded Software \_ Getting started](http://www2.thu.edu.tw/~emtools/DOE_project/NCCU/embedded%20system/ESD_06_GettingStarted.pdf)
* [How to convert from an armlink scatter file to a GNU ld linker script](https://www.mayrhofer.eu.org/node/24)
* [Using the GNU Linker](https://www.math.utah.edu/docs/info/ld_3.html)
* [Everything You Never Wanted To Know About Linker Script](https://mcyoung.xyz/2021/06/01/linker-script/)
* [Modern Embedded Systems Programming Course](https://github.com/QuantumLeaps/modern-embedded-programming-course) ⭐ 1,431 | 🐛 1 | 🌐 C | 📅 2026-07-07 - Learn from the basics to modern embedded programming practice.

## MCU programming

### General

* [McuOnEclipse](https://mcuoneclipse.com) - Everything about Eclipse, microcontrollers, software and tools.

### Bare-metal programming (Don't need MCU)

* [Bare metal programming guide](https://github.com/cpq/bare-metal-programming-guide) ⭐ 4,817 | 🐛 2 | 🌐 C | 📅 2026-07-03 - a detailed guide for beginners
* [Real-Time C++](https://github.com/ckormanyos/real-time-cpp) ⭐ 802 | 🐛 10 | 🌐 C++ | 📅 2026-08-08 - companion bare-metal code to Real-Time C++ book.
* [hypervisor](https://github.com/willamhou/hypervisor) ⭐ 16 | 🐛 0 | 🌐 Rust | 📅 2026-06-09 - ARM64 Type-1 bare-metal hypervisor in no\_std Rust, runs at EL2 on QEMU virt, boots Linux with FF-A v1.1 SPMC.
* [Simplest bare metal program for ARM](https://balau82.wordpress.com/2010/02/14/simplest-bare-metal-program-for-arm/) ([table of content](https://balau82.wordpress.com/arm-emulation/))

### MSP430

* [MSP430-GCC](http://www.simplyembedded.org/tutorials/setting-up-a-virtual-machine/)
* [CS4101: Introduction to Embedded Systems](http://www.cs.nthu.edu.tw/~king/courses/cs4101/2016/cs4101.html) -  The course is designed around labs, using TI MSP430 LaunchPad and Arduino Uno to discuss concepts such as basic I/O, timing and clocking, interrupt handling, serial communication, embedded operating systems, synchronization, etc.
* [msp430-template](https://github.com/uctools/msp430-template) - A template for MSP430 firmware.
* [MSP430 reference](https://students.cs.byu.edu/~clement/cs224/references/my_references.php)

### TM4C123

* [Drivers and examples](https://github.com/Mohammed-AhmedAF/ARM/tree/master/tiva-c) ⭐ 36 | 🐛 34 | 🌐 C | 📅 2026-05-25 - Drivers for internal peripherals and external modules for Tiva C, examples of FreeRTOS features under development/FreeRTOS
* [EmbeddedSystems.Playground](https://github.com/glennlopez/EmbeddedSystems.Playground/wiki/Periodic-SysTick-Interrupts) ⭐ 34 | 🐛 0 | 🌐 C | 📅 2021-01-10
* [Linux command line build system to generate binaries for TM4C123 (ARM Cortex M4)](https://github.com/pitankar/TM4C) ⭐ 24 | 🐛 1 | 🌐 C | 📅 2019-08-11
* [tivaapps](https://github.com/alexeicolin/tivaapps) ⭐ 17 | 🐛 0 | 🌐 C | 📅 2014-05-08 - Example hello-world apps for Texas Instruments TI-RTOS for Tiva C using a Linux host
* [tm4c-gcc](https://github.com/martinjaros/tm4c-gcc) ⭐ 8 | 🐛 0 | 🌐 C | 📅 2015-06-02 - TM4C123 GCC project template.
* [Macros in TivaWare](https://sites.google.com/site/luiselectronicprojects/tutorials/tiva-tutorials/direct-register-access-notes/macros-in-tivaware)
* [Analog to Digital Conversion, Data Acquisition and Control](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C14_ADCdataAcquisition.htm)
* [Embedded Systems - Shape The World](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/)
* [HowTo: Develop on the TI Tiva LaunchPad using Linux](http://chrisrm.com/howto-develop-on-the-ti-tiva-launchpad-using-linux/)
* [The complete tutorial for Stellaris LaunchPad development with GNU/Linux (I)](http://kernelhacks.blogspot.com/2012/11/the-complete-tutorial-for-stellaris.html)
* [Getting Started with the TI Stellaris LaunchPad on Linux](https://www.jann.cc/2012/12/11/getting_started_with_the_ti_stellaris_launchpad_on_linux.html)
* [Embedded Systems with TM4C123 @Valvano](http://users.ece.utexas.edu/~valvano/arm/)
* [Create FreeRTOS Demo Project using the GCC Compiler](http://shukra.cedt.iisc.ernet.in/edwiki/EmSys:Create_freertos_on_tm4c123_CCS_Project)
* [Serial bootloader on TM4C12x Microcontroller](http://www.ti.com/lit/an/spma074a/spma074a.pdf)
* [Tivaware bootloader](http://www.ti.com/lit/ug/spmu301d/spmu301d.pdf)
* [Diagnosing Common Development Problems and Tips & Info for TM4C Devices](http://e2e.ti.com/support/microcontrollers/tiva_arm/f/908/t/374640)
* [FreeRTOS-GCC-tm4c123glx](https://github.com/nhivp/FreeRTOS-GCC-tm4c123glx) - A port of FreeRTOS to the Texas Instruments Tiva TM4C123GLX Launchpad.
* [Stellaris\_TM4C123G\_GCC\_Template](https://github.com/AndoniV/Stellaris_TM4C123G_GCC_Template) - Texas Instruments template project for the TM4C123 series using GNU toolchain.

### MSP432

* [Real-Time Bluetooth Networks - UTAustinX](https://github.com/monpeco/real_time_bn) ⭐ 28 | 🐛 7 | 🌐 C | 📅 2017-01-15 - Learn the design fundamentals of a real-time operating system (RTOS) and how to build a Bluetooth network in this hands-on project-based course.

### STM32

* [Standalone TCP/IP stack for STM32, bare metal or RTOS](https://github.com/cesanta/mongoose) ⭐ 12,993 | 🐛 4 | 🌐 C | 📅 2026-08-15
* [Customizable Bootloader for STM32 microcontrollers.](https://github.com/akospasztor/stm32-bootloader) ⭐ 1,051 | 🐛 0 | 🌐 C | 📅 2022-12-02
* [STM32F103C8 Examples](https://github.com/avislab/STM32F103) ⭐ 968 | 🐛 7 | 🌐 C | 📅 2018-10-11
* [Lightweight USB device Stack for STM32 microcontrollers](https://github.com/dmitrystu/libusb_stm32) ⭐ 825 | 🐛 29 | 🌐 C | 📅 2025-10-06
* [libopencm3 and FreeRTOS projects using the STM32F103C8T6 MCU](https://github.com/ve3wwg/stm32f103c8t6) ⭐ 390 | 🐛 12 | 🌐 C | 📅 2023-11-18
* [DFU Bootloader for STM32 chips](https://github.com/devanlai/dapboot) ⭐ 380 | 🐛 13 | 🌐 C | 📅 2025-02-22
* [stm32-hid-bootloader](https://github.com/bootsector/stm32-hid-bootloader) ⭐ 183 | 🐛 0 | 🌐 C | 📅 2021-08-15 - Driverless USB HID bootloader and flashing tool for STM32F10X devices
* [A demo project of FreeRTOS running on a STM32F4 Discovery board.](https://github.com/wangyeee/STM32F4-FreeRTOS) ⭐ 174 | 🐛 1 | 🌐 C | 📅 2018-05-28
* [A tiny portable 3D graphics lib for micro controllers (Oled display)](https://github.com/avem-labs/ol3d) ⭐ 152 | 🐛 4 | 🌐 C | 📅 2018-10-26
* [A template for building STM32F0 ARM projects with GCC](https://github.com/szczys/stm32f0-discovery-basic-template) ⭐ 129 | 🐛 3 | 🌐 C | 📅 2022-09-05
* [stm32f103](https://github.com/trebisky/stm32f103) ⭐ 122 | 🐛 2 | 🌐 C | 📅 2023-12-10 - Bare metal programming on a generic STM32F103c8 board
* [stm32\_samples](https://github.com/dwelch67/stm32_samples) ⭐ 108 | 🐛 3 | 🌐 C | 📅 2022-09-13
* [STM32 programming with Embedded GNU Compiler](https://github.com/rowol/stm32_discovery_arm_gcc) ⭐ 91 | 🐛 1 | 🌐 C | 📅 2019-10-24
* [stm32f4de example code](https://github.com/dwelch67/stm32f4d) ⭐ 66 | 🐛 0 | 🌐 C | 📅 2016-05-12
* [stm32-dc-dc](https://github.com/gemesa/stm32-dc-dc) ⚠️ Archived - STM32 based DC-DC converter
* [Tests to program STM32 Nucleo in C with GCC ARM embedded toolchain and libopencm3](https://github.com/balau/nucleo_tests) ⭐ 32 | 🐛 0 | 🌐 C | 📅 2018-07-31
* [stm32-rf-scanner](https://github.com/gemesa/stm32-rf-scanner) ⚠️ Archived - STM32 and nRF24L01+ based 2.4GHz RF scanner
* [rustlink](https://github.com/gemesa/rustlink) ⚠️ Archived - small set of Rust tools to program STM32 devices
* [Getting started with the STM32F4-Discovery board using the EmBitz IDE](https://github.com/RoanFourie/STM32F4-DISCO-EMBITZ-Blinky) ⭐ 2 | 🐛 0 | 🌐 C | 📅 2017-09-22
* [STM32 bootloader](http://ciesie.com/post/stm32_bootloader/)
* [Open source flash program for STM32 using the ST serial bootloader](https://sourceforge.net/projects/stm32flash/)
* [stm32l1xx-template](https://github.com/uctools/stm32l1xx-template) - A template for building firmware for the STM32L1xx.
* [stm32f4xx with Rust at the HAL](https://apollolabsblog.hashnode.dev/series/stm32f4-embedded-rust-hal) - A series of tutorials for building STM32F4xx applications with Rust.

### STM32F7

* [STM32F7 Series](https://www.st.com/en/microcontrollers/stm32f7-series.html?querycriteria=productId=SS1858)
* [STM32 eLinux](https://elinux.org/STM32)
* [STM32F7 os.mbed](https://os.mbed.com/platforms/ST-Discovery-F746NG/)

### STM8

* [stm8-bare-min](https://github.com/lujji/stm8-bare-min) ⭐ 129 | 🐛 2 | 🌐 C | 📅 2022-11-01 - Tiny peripheral library for STM8S
* [stm8-bootloader](https://github.com/lujji/stm8-bootloader) ⚠️ Archived - Serial bootloader for STM8S microcontrollers
* [Wolk STM8 stuff ](https://github.com/LonelyWolf/stm8) ⭐ 34 | 🐛 0 | 🌐 C | 📅 2015-03-22
* [stm8-multi-tasker](https://github.com/vsch/stm8-multi-tasker) ⭐ 8 | 🐛 1 | 🌐 C | 📅 2018-02-02 - STM8-Multi-Tasker - Preemptive/Cooperative Round Robin Scheduler for STM8
* [STM8S001J3\_tiny\_board](https://github.com/HexRx/STM8S001J3_tiny_board) ⭐ 4 | 🐛 0 | 📅 2020-10-18 - A tiny dev board for STM8S001J3 MCU designed in KiCad.

### ESP8266

* [Sming - ESP8266/ESP32 IoT Framework](https://github.com/SmingHub/Sming) ⭐ 1,569 | 🐛 82 | 🌐 C++ | 📅 2026-07-20
* [Wi-FI ESP8266 learning journey](https://github.com/xuhongv/StudyInEsp8266) ⭐ 716 | 🐛 3 | 🌐 Assembly | 📅 2021-05-28
* [Wi-FI ESP32 learning journey](https://github.com/xuhongv/StudyInEsp32) ⭐ 505 | 🐛 7 | 🌐 C | 📅 2024-10-14
* [An open source bootloader for the ESP8266](https://github.com/raburton/rboot) ⭐ 318 | 🐛 14 | 🌐 C | 📅 2019-08-04
* [An esp8266 rom creation tool](https://github.com/raburton/esptool2) ⭐ 65 | 🐛 0 | 🌐 C | 📅 2019-08-04

## Raspberry

* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os) ⭐ 13,909 | 🐛 66 | 🌐 C | 📅 2024-03-29
* [Writing a "bare metal" operating system for Raspberry Pi 4](https://github.com/babbleberry/rpi4-osdev) ⭐ 3,766 | 🐛 0 | 🌐 C | 📅 2026-08-04
* [Bare metal Raspberry Pi 3 tutorials](https://github.com/bztsrc/raspi3-tutorial) ⭐ 3,036 | 🐛 6 | 🌐 C | 📅 2024-06-21
* [Raspberry Pi ARM based bare metal examples](https://github.com/dwelch67/raspberrypi) ⭐ 2,822 | 🐛 34 | 🌐 Assembly | 📅 2023-07-14
* [64-bit Tiano Core UEFI for the Raspberry Pi 3](https://github.com/andreiw/RaspberryPiPkg) ⭐ 741 | 🐛 3 | 🌐 C | 📅 2020-02-19
* [Raspberry-Pi Bare Metal Tutorial](https://github.com/BrianSidebotham/arm-tutorial-rpi) ⭐ 614 | 🐛 1 | 🌐 C | 📅 2020-12-21
* [A port of FreeRTOS to the raspberry pi](https://github.com/jameswalmsley/RaspberryPi-FreeRTOS) ⭐ 503 | 🐛 7 | 🌐 C | 📅 2017-12-11
* [Sample source: Baremetal source code for Raspberry](https://github.com/LdB-ECM/Raspberry-Pi) ⭐ 334 | 🐛 7 | 🌐 C | 📅 2019-05-06
* [A public Baremetal Raspberry Pi code](https://github.com/LdB-ECM/Raspberry-Pi) ⭐ 334 | 🐛 7 | 🌐 C | 📅 2019-05-06
* [A port of FreeRTOS to the raspberry pi 2B. With USB+Ethernet+TCP/IP.](https://github.com/Forty-Tw0/RaspberryPi-FreeRTOS) ⭐ 141 | 🐛 1 | 🌐 C | 📅 2017-07-02
* [ARM shellcode and exploit development - BSidesMunich 2018](https://github.com/invictus1306/Workshop-BSidesMunich2018) ⭐ 106 | 🐛 0 | 🌐 Python | 📅 2018-04-09
* [UEFI for RaspberryPi2 and RaspberryPi3 based on Linaro EDK2](https://github.com/ms-iot/RPi-UEFI) ⚠️ Archived
* [Build a Debian-based ARM64 system for Raspberry Pi 3](https://github.com/UMRnInside/RPi-arm64) ⭐ 92 | 🐛 1 | 🌐 Shell | 📅 2019-08-08
* [ARM-episodes](https://github.com/invictus1306/ARM-episodes) ⭐ 79 | 🐛 0 | 🌐 C | 📅 2018-01-25 & [ARM exploitation for IoT](https://quequero.org/2017/07/arm-exploitation-iot-episode-1/)
* [「BareMetalで遊ぶ Raspberry Pi」のプログラムです。](https://github.com/jitomesky/RPi_Micon_C85book) ⭐ 50 | 🐛 2 | 🌐 C | 📅 2018-08-13
* [Bare-metal examples](https://github.com/mrvn/RaspberryPi-baremetal) ⭐ 32 | 🐛 0 | 🌐 C | 📅 2015-04-26
* [uCOS-II on Raspberry Pi](https://github.com/fmlab/ucos_RaspberryPi) ⭐ 28 | 🐛 1 | 🌐 C++ | 📅 2013-06-17
* [Bare-metal lab](https://github.com/tzuCarlos/RaspberryPi) ⭐ 23 | 🐛 0 | 🌐 C | 📅 2015-03-20
* [Sample source: NarcOS - A bare metal ultralight kernel for Raspberry Pi 3](https://github.com/forkachild/NarcOS) ⭐ 22 | 🐛 0 | 🌐 C | 📅 2018-05-08
* [A bootloader for the Raspberry Pi using the ethernet device](https://github.com/Nvreformat/Etherboot) ⭐ 11 | 🐛 0 | 🌐 C | 📅 2015-05-04
* [Sample source: FreeRTOS v9.0.0 port for Raspberry Pi 1](https://github.com/leodido99/RaspberryPi1-FreeRTOSv9.0.0) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2018-09-15
* [Sample source: A bare-metal experiments with the RaspberryPi](https://github.com/majorviraj/my-os) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2020-01-06
* [Assembly code for Raspberry Pi](https://github.com/Alkesst/RPIAssembly) ⭐ 3 | 🐛 0 | 🌐 Assembly | 📅 2018-02-11
* [PiSpot-Show](https://github.com/GeiserX/PiSpot-Show) ⚠️ Archived - A Raspberry Pi captive portal that creates a WiFi hotspot displaying a customizable web page to connected users using hostapd, dnsmasq, and nginx.
* [Porting uCOSII to the raspberry pi A+/B+/2B](https://github.com/mopplayer/uCOSII_RPi) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2015-07-31
* [Raspberry Pi Bare Metal](https://github.com/fordp2002/ArmCopro/wiki/Raspberry-Pi-Bare-Metal) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2016-03-15 & [related link](https://microeletroniki.wordpress.com/)
* [ChibiOS/RT on the Raspberry Pi](https://www.stevebate.net/chibios-rpi/GettingStarted.html)
* [Open Projects: Raspberry, Beaglebone BSP](https://devel.rtems.org/wiki/Developer/OpenProjects)
* [A Real-Time Operating System on the Raspberry Pi](http://www.pebblebay.com/raspberry-pi-embedded/)
* [FreeRTOS Successfully Ported](https://www.raspberrypi.org/forums/viewtopic.php?f=72\&t=22423)
* [Exploring AArch64 assembler - Raspberry](https://thinkingeek.com/2016/10/08/exploring-aarch64-assembler-chapter1/)
* [Bare Metal Raspberry Pi](https://taylorpetrick.com/blog/post/bare-metal-pi-setup)
* [Bare Metal Programming in C](http://www.valvers.com/open-software/raspberry-pi/step01-bare-metal-programming-in-cpt1/)
* [Baking Pi – Operating Systems Development](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/)
* [Search for 'Raspberry' topic on Github](https://github.com/topics/raspberry-pi-3?l=c)
* [elinux: Raspberry Pi Programming](https://elinux.org/Raspberry_Pi_Programming) or [elinux: RPi Hub](https://elinux.org/RPi_Hub)
* [Stanford CS104e - An Experimental Course on Operating Systems](https://web.stanford.edu/class/cs140e/)
* [Computer Systems](http://cs107e.github.io/)
* [CXCORE-RaspberryPi3-ubuntu-18.04-aarch64](https://github.com/chainsx/ubuntu64-rpi#cxcore-raspberrypi3-ubuntu-1804-aarch64--)
* [64 bit Bare Metal Programming on RPI-3](https://archive.fosdem.org/2017/schedule/event/programming_rpi3/attachments/slides/1475/export/events/attachments/programming_rpi3/slides/1475/bare_metal_rpi3.pdf)
* [Raspberry Pi 3 Bare Metal](https://adamransom.github.io/posts/raspberry-pi-bare-metal-part-1.html)
* [Exploring Raspberry Pi: Interfacing to the Real World with Embedded Linux {book}](https://www.wiley.com/en-us/Exploring+Raspberry+Pi%3A+Interfacing+to+the+Real+World+with+Embedded+Linux-p-9781119188681)
* [Exploring Raspberry Pi: Interfacing to the Real World with Embedded Linux {website}](http://exploringrpi.com/)

## Beaglebone

* [BBB-BareMetal](https://github.com/allexoll/BBB-BareMetal) ⭐ 140 | 🐛 1 | 🌐 C | 📅 2024-04-29- Works on the beaglebone black (bare metal)
* [bbb-asm-demo](https://github.com/mvduin/bbb-asm-demo) ⭐ 20 | 🐛 0 | 🌐 Assembly | 📅 2021-06-09 - Extremely tiny baremetal application for BeagleBone Black
* [FreeRTOS for BeagleBone Black](https://github.com/henfos/BBBFreeRTOS) ⭐ 13 | 🐛 1 | 🌐 C | 📅 2014-06-10
* [beaglebone\_samples](https://github.com/dwelch67/beaglebone_samples) ⭐ 9 | 🐛 0 | 🌐 C | 📅 2016-10-02
* [bare metal c project for beaglebone, ti sitara am335x](https://github.com/0xCA5A/kickstart/tree/master/beaglebone/bare_metal_hello_world) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2015-08-13
* [Various projects that utilize low level hardware instructions to interface with leds, speaker output and joystick input.](https://github.com/travelln/beaglebone-projects) ⭐ 2 | 🐛 1 | 🌐 C | 📅 2022-07-05
* [Simple implementation of an OS for the BeagleBoard C4 with ARMv7 A8 processor.](https://github.com/Oxydation/MinionOS) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2018-03-14
* [BeagleBone Black I2C References](https://datko.net/2013/11/03/bbb_i2c/)
* [Learning BeagleBone Python Programming](https://hub.packtpub.com/learning-beaglebone-python-programming/)
* [Windows Embedded Compact BSP for TI's Beaglebone](https://github.com/dvescovi1/WECBeagleBone)
* [Running a Baremetal Beaglebone Black](https://www.twosixlabs.com/running-a-baremetal-beaglebone-black-part-1/) & [Part 2](https://www.twosixlabs.com/running-a-baremetal-beaglebone-black-part-2/)
* [Bare Metal on the BeagleBone (Black and Green)](https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/BareMetalGuide.pdf) & [link1](https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/) + [Link2](https://www.cs.sfu.ca/CourseCentral/433/bfraser/weekly.html)
* [A tutorial on bare-metal \[OS\] development on the Texas Instruments BeagleBoard.](https://wiki.osdev.org/ARM_Beagleboard)
* [Bare Metal Applications on OSD335x using U-Boot](https://octavosystems.com/app_notes/bare-metal-on-osd335x-using-u-boot/#_Toc382081430)
* [Beaglebone - Getting started with JTAG and CCS](https://beagleboard.org/static/beaglebone/latest/Docs/ccs-jtag-simple.htm)
* [BeagleBoardJTAG](https://elinux.org/BeagleBoardJTAG)

## Linux kernel and device driver development

* [Linux inside](https://github.com/0xAX/linux-insides) ⭐ 32,919 | 🐛 23 | 🌐 Python | 📅 2026-08-06 - A little bit about a linux kernel
* [low-level programming university #linux-kernel-and-device-driver](https://github.com/gurugio/lowlevelprogramming-university#linux-kernel-and-device-driver) ⚠️ Archived
* [Linux Kernel Exploitation](https://github.com/xairy/linux-kernel-exploitation) ⭐ 6,593 | 🐛 0 | 📅 2026-08-14 - A bunch of links related to Linux kernel exploitation
* [Linux Kernel Module Cheat](https://github.com/cirosantilli/linux-kernel-module-cheat) ⭐ 4,507 | 🐛 73 | 🌐 Python | 📅 2026-06-16
* [Minimal Linux Live](https://github.com/ivandavidov/minimal) ⭐ 1,670 | 🐛 53 | 🌐 HTML | 📅 2026-06-05 - a tiny educational Linux distribution
* [c-periphery](https://github.com/vsergeev/c-periphery) ⭐ 1,059 | 🐛 4 | 🌐 C | 📅 2025-11-02 - A C library for peripheral I/O (GPIO, SPI, I2C, MMIO, Serial) in Linux.
* [Linux driver practices ](https://github.com/starnight/DriverPractice) ⭐ 192 | 🐛 0 | 🌐 C | 📅 2024-02-14
* [Writing device drivers in Linux](http://freesoftwaremagazine.com/articles/drivers_linux/)
* [YOLINUX Tutorials](http://www.yolinux.com/TUTORIALS/)
* [Linux driver programming](https://sites.google.com/site/embedded247/ddcourse)
* [Free training materials and conference presentations](https://bootlin.com/docs/)
* [eBook: Linux Drivers](https://sysplay.github.io/books/LinuxDrivers/book/index.html) or [Slides: Linux Drivers](https://sysplay.in/index.php?pagefile=linux_drivers)
* [OpenEmbedded](http://www.openembedded.org/wiki/Main_Page),
* [Start linux kernel module development!](https://rayanfam.com/topics/start-linux-kernel-module-development/)
* [Yocto Project](https://www.yoctoproject.org/) - Create custom Linux-based systems regardless of the hardware architecture.
* [Buildroot](https://buildroot.org/) - Simple, efficient and easy-to-use tool to generate embedded Linux systems through cross-compilation.

## Assembly

* [GCC-Inline-Assembly-HOWTO](https://www.ibiblio.org/gferg/ldp/GCC-Inline-Assembly-HOWTO.html)
* [Assembly programming](https://courses.cs.washington.edu/courses/cse351/17sp/lectures/CSE351-L07-asm-I_17sp-ink.pdf)

## RTOS

* [How to create an OS from scratch](https://github.com/cfenollosa/os-tutorial) ⭐ 30,656 | 🐛 130 | 🌐 C | 📅 2026-02-04
* [RT-Thread is an open source IoT operating system from China.](https://github.com/RT-Thread/rt-thread) ⭐ 12,154 | 🐛 482 | 🌐 C | 📅 2026-08-16
* [30 Days make OS](https://github.com/yourtion/30dayMakeOS) ⭐ 6,446 | 🐛 12 | 🌐 C | 📅 2024-04-01 --> [YOS](https://github.com/yourtion/YOS) ⭐ 264 | 🐛 2 | 🌐 C | 📅 2021-05-24 @[Yannik](https://yannik520.github.io/)
* [tock](https://github.com/tock/tock) ⭐ 6,412 | 🐛 206 | 🌐 Rust | 📅 2026-08-15 - A secure embedded operating system for Cortex-M based microcontrollers.
* [AliOS-Things](https://github.com/alibaba/AliOS-Things) ⭐ 4,626 | 🐛 74 | 🌐 C | 📅 2023-07-04 - AliOS Things released by Alibaba is an open-source implementation of operating system (OS) for Internet of Things (IoT).
* [High performance motor control](https://github.com/madcowswe/ODrive) ⭐ 3,736 | 🐛 18 | 🌐 C++ | 📅 2026-01-20
* [Sample Source: TetrOS is a small feature rich Tetris clone which is written in Assembly.](https://github.com/daniel-e/tetros) ⭐ 781 | 🐛 0 | 🌐 Assembly | 📅 2016-12-18
* [object-oriented C++ RTOS for microcontrollers](https://github.com/DISTORTEC/distortos) ⭐ 468 | 🐛 4 | 🌐 C++ | 📅 2026-07-16
* [Sample Source: TNeo - a well-formed and carefully tested preemptive real-time kernel for 16- and 32-bits MCUs](https://github.com/dimonomid/tneo) ⭐ 246 | 🐛 3 | 🌐 C | 📅 2024-12-28
* [Sample Source: RTOS for microcontrollers](https://github.com/jimtremblay/nOS) ⭐ 211 | 🐛 5 | 🌐 C | 📅 2020-12-02
* [Free real-time operating system (RTOS) designed for deeply embedded applications](https://github.com/stateos/StateOS) ⭐ 208 | 🐛 0 | 🌐 C++ | 📅 2026-07-30
* [mini-arm-os & qemu with a stm32](https://github.com/embedded2015/mini-arm-os) ⭐ 205 | 🐛 2 | 🌐 C | 📅 2017-09-01 or [here](https://github.com/jserv/mini-arm-os) ⭐ 1,252 | 🐛 2 | 🌐 C | 📅 2025-12-14 - Build a minimal multi-tasking OS kernel for ARM Cortex-M series from scratch
* [Sample Source: A Powerful embedded RTOS for ARM Cortex M microcontrollers](https://github.com/StratifyLabs/StratifyOS) ⭐ 153 | 🐛 27 | 🌐 C | 📅 2024-06-07
* [Sample Source: An embedded operating system for ARM Cortex-M based microcontrollers](https://github.com/onkwon/yaos) ⭐ 51 | 🐛 4 | 🌐 C | 📅 2020-03-01
* [yaos is an embedded operating system for Internet of Things(IoT) devices, specifically for a single-core processor without MMU virtualization.](https://github.com/onkwon/yaos) ⭐ 51 | 🐛 4 | 🌐 C | 📅 2020-03-01
* [Sample Source: RTOS-From-Scratch](https://github.com/RTOS-From-Scratch/RTOS-From-Scratch) ⭐ 38 | 🐛 0 | 🌐 C | 📅 2017-08-16
* [Sample Source: rnk is a RTOS targeting ARM architecture.](https://github.com/raphui/rnk) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2026-01-09
* [Real-Time Kernel '0'](https://github.com/antoniogiacomelli/RK0) ⭐ 14 | 🐛 0 | 🌐 C | 📅 2026-08-16 - A lean, highly deterministic, low-latency real-time kernel for ARMv6/7M.
* [Sample Source: Embeded OS for PIC32MX270F256B](https://github.com/envzhu/kozos-pic) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2025-02-23
* [List of open source real-time operating systems](https://www.osrtos.com/)
* [ROS](http://www.ros.org/)
* [FreeRTOS](https://freertos.org/)
* [FreeRTOS - Explanation](http://www.aosabook.org/en/freertos.html)
* [FreeRTOS API Reference Documentation](http://web.ist.utl.pt/~ist11993/FRTOS-API/index.html)
* [How to Write a Small RTOS](https://larrylisky.com/2012/07/14/how-to-create-a-small-rtos/)
* [RTOS From Scratch](https://github.com/RTOS-From-Scratch)
* [Writing a simple operating system from scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
* [MPSoC FreeRTOS Development](http://www.wiki.xilinx.com/MPSoC+FreeRTOS+Development)
* [Atomthreads: Open Source RTOS](https://atomthreads.com/)
* [MINIX3: Open source RTOS](http://www.minix3.org/)
* Community: [OSDEV.org](https://wiki.osdev.org/Main_Page), [reddit/osdev](https://www.reddit.com/r/osdev/)
* [Real-time System Group](https://www.cs.york.ac.uk/rts/)
* [How I ended up writing a new real-time kernel](https://dmitryfrank.com/articles/how_i_ended_up_writing_my_own_kernel)
* [RT-Thread for Raspberry Pi 2B ](https://github.com/BernardXiong/raspi2)
* [CoRTOS](https://forum.43oh.com/topic/13151-cortos-an-open-source-minimalist-rtos/) & [CoRTOS Simple Cooperative RTOS](https://sourceforge.net/projects/cortos-simple/) - An open source minimalist RTOS.
* [µOS++ Reference](http://micro-os-plus.github.io/develop/references/)
* [TNKernel](http://www.tnkernel.com/index.html) - a compact and very fast real-time kernel for the embedded 32/16/8 bits microprocessors.
* [Femto OS](http://www.femtoos.org/news.html) - a very concise portable real time - preemptive operating system (RTOS) for embedded microcontrollers with minimal ram and flash, say 2KB .. 16KB flash and 128 .. 1024 bytes ram.

## Automotive

* [automotive software(OSEK & AUTOSAR) ](https://github.com/parai/as) ⭐ 1,050 | 🐛 11 | 🌐 C | 📅 2026-01-18 - Because I am not powerful so I decided to develop tiny but smart part of automotive software based on open source, and create a general AUTOSAR & Automotive Software study environment.
* [Sample Source: Trampoline is a static RTOS for small embedded systems.](https://github.com/TrampolineRTOS/trampoline) ⭐ 743 | 🐛 21 | 🌐 C | 📅 2025-09-15 & [labs](http://www.irccyn.ec-nantes.fr/~bechenne/trampoline-labs/)
* [Sample source: An integration an example AUTOSAR project which every part in AUTOSAR (OS, RTE, BSW, MCAL) are collected from different open source.](https://github.com/leduynguyen/My_AUTOSAR_Project) ⭐ 402 | 🐛 1 | 🌐 C | 📅 2018-04-03
* [BlackFlag ECU](https://github.com/bad-antics/blackflag-ecu) ⭐ 33 | 🐛 3 | 📅 2026-02-27 - Automotive CAN bus security testing and analysis tool for ECU research, fuzzing, and reverse engineering of vehicle communication protocols.

## OS

* [Bootstrap yourself to write an OS from scratch. A book for self-learner.](https://github.com/tuhdo/os01) ⭐ 13,673 | 🐛 66 | 🌐 TeX | 📅 2024-03-26
* [A simple OS kernel for research, teaching, and fun](https://github.com/dthain/basekernel) ⭐ 937 | 🐛 19 | 🌐 C | 📅 2026-01-08
* [TetrOS](https://github.com/daniel-e/tetros) ⭐ 781 | 🐛 0 | 🌐 Assembly | 📅 2016-12-18 - Tetris that fits into the boot sector.
* [Operating Systems C Term 2018](https://github.com/Mcdonoughd/CS3013) ⚠️ Archived
* [ucLinux](http://www.uclinux.org/): The Embedded Linux/Microcontroller project is a port of Linux to systems without a Memory Management Unit (MMU).
* [Tizen](https://www.elinux.org/Tizen)
* [Kernel 101 – Let’s write a Kernel](https://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
* [The little book about OS development](https://littleosbook.github.io/)
* [Writing a Simple Operating System from Scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
* [JamesM's kernel development tutorials](http://www.jamesmolloy.co.uk/tutorial_html/)
* [Bare Bones](https://wiki.osdev.org/Bare_Bones) - a simple kernel for 32-bit x86 and boot it.
* [Operating System Development Series](http://www.brokenthorn.com/Resources/OSDevIndex.html)
* [7 Steps to Writing a Simple Cooperative Scheduler](https://www.edn.com/7-steps-to-writing-a-simple-cooperative-scheduler/)

## WindowCE

* [GuruCE Blog](https://guruce.com/blog)
* [Windows CE Base Team Blog](https://blogs.msdn.microsoft.com/ce_base/)
* [DevWinCE blog](http://devwince.blogspot.com/)
* [Windows Embedded Compact BSP for Raspberry Pi](https://archive.codeplex.com/?p=ceonpi)
* [Windows Embedded Board Support Package for BeagleBone](https://archive.codeplex.com/?p=beaglebonebsp)

## Compiler

* [ARM Compiler - armasm User Guide](https://static.docs.arm.com/dui0801/i/DUI0801I_armasm_user_guide.pdf)

## Bootloader

* [OpenBLT](https://github.com/feaser/openblt) ⭐ 964 | 🐛 0 | 🌐 C | 📅 2026-07-14 - an open source and portable bootloader for microcontrollers.
* [can-bootloader](https://github.com/cvra/can-bootloader) ⭐ 153 | 🐛 1 | 🌐 C | 📅 2023-02-06 - The bootloader used to flash our CAN-connected boards
* [ARMv7M ELF loader ](https://github.com/martinribelotta/elfloader) ⭐ 110 | 🐛 0 | 🌐 C | 📅 2026-05-18
* [A bootloader for ARM Cortex-M based microcontrollers](https://github.com/onkwon/yaboot) ⭐ 29 | 🐛 0 | 🌐 C | 📅 2019-11-11
* [Writing a boot loader in Assembly and C](https://www.codeproject.com/Articles/664165/Writing-a-boot-loader-in-Assembly-and-C-Part)
* [Writing a Bootloader Part 3](http://3zanders.co.uk/2017/10/18/writing-a-bootloader3/)
* [Writing a Bootloader Part 1](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
* [Bootloaders 101](https://www.embedded.com/design/prototyping-and-development/4410233/1/Bootloaders-101--making-your-embedded-design-future-proof)
* Understand boot process: [link1](https://www.beningo.com/understanding-the-microcontroller-boot-process/), [link2](https://www.beningo.com/understanding-the-microcontroller-boot-process/), [link3](https://www.eevblog.com/forum/microcontrollers/copy-data-from-rom-to-ram-and-execute/)
* Keywords: *hello world bootloader*, *writing a bootloader from scratch*, *how to write a bootloader in assembly*, ...

## Makefile

* [Managing projects with GNU Make](http://uploads.mitechie.com/books/Managing_Projects_with_GNU_Make_Third_Edition.pdf)
* [GCC and Make](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)

## Peripheral

### Memory Protection Unit

* [Building Hardware Components for Memory Protection of Applications on a Tiny Processor](https://carrv.github.io/2017/papers/oh-mpu-carrv2017.pdf)
* [KeyStone Architecture: Memory Protection Unit (MPU)](http://www.ti.com/lit/ug/sprugw5a/sprugw5a.pdf)

### USB

* [tinyusb](https://github.com/hathach/tinyusb) ⭐ 7,038 | 🐛 243 | 🌐 C | 📅 2026-08-16 - An open source USB stack for a variety of Embedded Systems.

## Others

* [apollo](https://github.com/ApolloAuto/apollo) ⭐ 26,795 | 🐛 1,045 | 🌐 C++ | 📅 2026-04-16 - An open autonomous driving platform.
* [A C++ template library for embedded applications](https://github.com/ETLCPP/etl) ⭐ 3,095 | 🐛 65 | 🌐 C++ | 📅 2026-08-16
* [Advanced fault backtrace library for ARM Cortex-M series MCU](https://github.com/armink/CmBacktrace) ⭐ 2,151 | 🐛 47 | 🌐 C | 📅 2026-05-21
* [DirtyJTAG](https://github.com/jeanthom/DirtyJTAG) ⭐ 623 | 🐛 10 | 🌐 C | 📅 2026-03-10 - JTAG adapter firmware for STM32F1
* [mcu-starter-projects](https://github.com/ataradov/mcu-starter-projects) ⭐ 342 | 🐛 5 | 🌐 C | 📅 2025-11-08 - Simple starter projects for bare-metal MCU development.
* [Generic\_MCU\_Software\_Infrastructure](https://github.com/GorgonMeducer/Generic_MCU_Software_Infrastructure) ⭐ 241 | 🐛 0 | 🌐 C | 📅 2024-03-09 - Provide necessary software infrastructure, service, macros to support some high level abstract concept or paradigm, such as OOPC, FSM, delegate (event-driven) and etc.
* [Embedded rework of C++ STL](https://github.com/malachi-iot/estdlib) ⭐ 85 | 🐛 108 | 🌐 C++ | 📅 2026-07-29 - `basic_string`, `basic_ostream` etc. leaned way down.  Cross platform (including AVR).
* [RAMEN 🍜](https://github.com/Zubax/ramen) ⭐ 75 | 🐛 2 | 🌐 C++ | 📅 2026-05-02 - flow-based programming implemented in a simple single-header unopinionated library.
* [A practical approach to Kalman filter and how to implement it](http://blog.tkjelectronics.dk/2012/09/a-practical-approach-to-kalman-filter-and-how-to-implement-it/)
* [Embedded System programming](http://www.5square.in/): Diving into Syllabus for investigation.
* [ELC 2018 Presentations](https://elinux.org/ELC_2018_Presentations)
* [ARM Edition](https://sparkylinux.org/wiki/doku.php/sparky_arm): Sparky ARM Edition is a Sparky version created for a single board mini computer RaspberryPi.
* [The gem5 Simulator](https://developer.arm.com/research/research-enablement/system-modeling) is a well-known sophisticated simulator used for computer system research at both architecture and micro-architecture levels. Main page is [here](http://gem5.org/Main_Page).
* [LineageOS Android Distribution](https://github.com/LineageOS)
* [The NoCAN platform](http://omzlo.com/articles/the-nocan-platform)
* [Realtime OS on Embedded Systems](http://socialledge.com/sjsu/index.php/Realtime_OS_on_Embedded_Systems)
* [These projects were produced in the five weeks of ECE 4760 each year.](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/)
* * [A Development Environment for ARM TrustZone with GlobalPlatform Support](https://www.eit.lth.se/sprapport.php?uid=793)

## Embedded GUI Development

* [Embedded Wizard](https://www.embedded-wizard.de/) - Sophisticated GUI for Your Embedded Platform
* [lvgl](https://lvgl.io/) - Graphics library to create an embedded GUI with easy-to-use graphical elements, beautiful visual effects and low memory footprint. It offers anti-aliasing, opacity, and animations using only one frame buffer.

## Machine Learning & AI on MCU

* [m2cgen](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,996 | 🐛 62 | 🌐 Python | 📅 2024-08-03 - A CLI tool which allows to transpile trained classic ML models into a native code of various programming languages with zero dependencies including C.
* [Embedded Learning Library (ELL)](https://github.com/Microsoft/ELL) ⚠️ Archived - Microsoft's library to deploy intelligent machine-learned models onto resource constrained platforms and small single-board computers.
* [uTensor](https://github.com/uTensor/uTensor) ⭐ 1,928 | 🐛 56 | 🌐 C++ | 📅 2025-05-10 - AI inference library based on mbed (an RTOS for ARM chipsets) and TensorFlow.
* [nnom](https://github.com/majianjia/nnom) ⭐ 1,164 | 🐛 88 | 🌐 C | 📅 2024-04-08 - A higher-level Neural Network library for microcontrollers.
* [kann](https://github.com/attractivechaos/kann) ⭐ 760 | 🐛 32 | 🌐 C | 📅 2025-06-06 - A lightweight C library for artificial neural networks.
* [nn2](https://github.com/facex-engine/facex/tree/master/nn2) ⭐ 333 | 🐛 6 | 🌐 C | 📅 2026-05-14 - Tiny zero-dependency neural network inference engine in pure C with hand-written SIMD kernels (AVX-512 / AVX2 / NEON). Runs the FaceX face recognition stack on Apple Silicon, ARM SBCs and ESP32-P4. Apache 2.0.
* [edge-agents (ForestHub)](https://github.com/ForestHubAI/edge-agents) ⭐ 97 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-29 - Open-source (AGPL-3.0) 30 MB AI agent runtime for edge devices. Offline by default; GPIO/UART/MQTT as first-class nodes; local SLMs alongside cloud LLMs. Runs on Raspberry Pi 5, Jetson Orin Nano, STM32MP25, ctrlX CORE.
* [voicute](https://github.com/voicute/onnx-wakeword) ⭐ 56 | 🐛 0 | 🌐 C | 📅 2026-08-14 - Lightweight keyword spotting and wake word detection engine for ESP32 with INT8 quantization (\~74KB per keyword), multi-language support including Chinese, and cross-platform ONNX Runtime inference.
* [nn4mp](https://github.com/correlllab/nn4mp) ⭐ 33 | 🐛 7 | 🌐 C++ | 📅 2022-02-03
* [EmbededAI](https://github.com/boralt/EmbeddedAI) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2022-09-13 - A library that provides elements of AI to C++ applications.
* [Qualcomm Neural Processing SDK for AI](https://developer.qualcomm.com/software/qualcomm-neural-processing-sdk) - Libraries to developers run NN models on Snapdragon mobile platforms taking advantage of the CPU, GPU and/or DSP.
* [CMSIS NN](https://arm-software.github.io/CMSIS_5/NN/html/index.html) - A collection of efficient neural network kernels developed to maximize the performance and minimize the memory footprint of neural networks on Cortex-M processor cores.
* [ARM Compute Library](https://developer.arm.com/technologies/compute-library) - Set of optimized functions for image processing, computer vision, and machine learning.

## Utilities

* [Serial Studio](https://github.com/Serial-Studio/Serial-Studio) ⭐ 7,127 | 🐛 23 | 🌐 C++ | 📅 2026-08-15 - Visualize, analyze and stream over the internet data generated by your MCU project
* [mspdebug](https://github.com/dlbeer/mspdebug) ⭐ 215 | 🐛 58 | 🌐 C | 📅 2025-11-13 - Debugging tool for MSP430 MCUs
* [Jumpstarter](https://github.com/jumpstarter-dev/jumpstarter) ⭐ 211 | 🐛 179 | 🌐 Python | 📅 2026-08-16 - Open source hardware-in-the-loop testing framework for automated testing on real and virtual embedded hardware with CI/CD integration.
* [lm4tools](https://github.com/utzig/lm4tools) ⭐ 209 | 🐛 15 | 🌐 C | 📅 2018-09-03
* [NaiveSystems Analyze](https://github.com/naivesystems/analyze) ⭐ 204 | 🐛 4 | 🌐 C++ | 📅 2025-12-29 - Static Analysis Tool for Code Security and Compliance
* [pycs](https://github.com/deadsy/pycs) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2023-02-27 - Python Based ARM CoreSight Debug and Trace Tools
* [EmbedEval](https://github.com/Ecro/embedeval) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2026-08-06 - Benchmark that measures how well LLMs write embedded firmware. 233 cases across Zephyr, ESP-IDF, STM32 HAL, FreeRTOS, Linux drivers and Yocto, verified through static checks, SDK compilation, runtime execution and mutation testing.
* [aem-modbus-simulator](https://github.com/leaberg69/aem-modbus-simulator) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-05-31 - Open-source Python Modbus RTU/TCP slave simulator emulating an industrial DC voltage monitor (147 holding registers, 6 baudrates). Lets SCADA/PLC firmware engineers test Modbus integration in CI pipelines without physical hardware on the bench.
* [CRA Kit SBOM](https://cra.synthworx.com/integrations/crakit-sbom.mjs) - Zero-dependency CI script that reads Zephyr, Yocto, Buildroot, PlatformIO, ESP-IDF and STM32Cube build manifests and emits CycloneDX SBOMs.
* [Scrutiny Debugger](https://scrutinydebugger.com) - An open source debugging, visualization and testing tool for C/C++ embedded applications that works through instrumentation.
* [MemBrowse](https://membrowse.com) - Memory footprint tracking for ELF binaries with CLI and CI integration to monitor flash/RAM usage across commits.
* [memprobe.dev](https://memprobe.dev) - ELF firmware analysis as a web app, CLI, and GitHub Action. Break down flash and RAM usage by section, file, library, and symbol, compare builds, track project history and memory growth over time, and set CI size budgets.
* [SiliconRig](https://siliconrig.dev) - Cloud-hosted embedded boards (ESP32-S3, STM32, RP2350) for remote flashing, serial console, and hardware-in-the-loop testing in CI. Open-source CLI, Python SDK, and GitHub Action.
* [Velxio](https://velxio.dev) - Fully local, open source Arduino simulator with real AVR8, RP2040 and ESP32 emulation, a visual circuit canvas and an in-browser code editor. Runs in the browser or self-hosted via Docker.

## Tips & tricks

* [Awesome Cheat Sheets](https://github.com/mintisan/awesome-cheat-sheets/blob/master/README.md) ⭐ 155 | 🐛 0 | 📅 2023-12-13

> Awesome Cheat Sheets for Developer Utility, like Git, Vim , Tmux, SublimeText, Markdown, Shell.

* [Vim Config for Reading Linux Kernel Source Code](https://github.com/mintisan/oh-my-vim) ⭐ 36 | 🐛 0 | 🌐 Vim script | 📅 2022-03-13
* [GNU GDB Debugger Command Cheat Sheet](http://www.yolinux.com/TUTORIALS/GDB-Commands.html)

# Tech blogs

* [What a C programmer should know about memory](http://marek.vavrusa.com/memory/)
* [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf)
* [What Every C Programmer Should Know About Undefined Behavior ](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html) [part 2](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know_14.html) [part 3](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know_21.html)
* [A Guide to Undefined Behavior in C and C++](https://blog.regehr.org/archives/213)
* [Software Engineering Takeaways](https://blog.regehr.org/archives/1594)
* [Embedsys weekly newsletter](https://embedsysweekly.com/)
* [EdgeLog](https://edgelog.dev/) - Embedded and edge AI engineering notes, with measurements from running LLMs and agents against real hardware.

## FAQ\_Embedded

* [Boot section is removed (gcc, ld, ar, as)](https://www.embeddedrelated.com/showthread/lpc2000/47841-1.php)
* [What are .axf files?](https://stackoverflow.com/questions/17761328/what-are-axf-files)

## Looking for more lists like this?

* [Curated list of awesome lists](https://github.com/sindresorhus/awesome) ⭐ 496,498 | 🐛 100 | 📅 2026-06-30
* [Curated list of project-based tutorials](https://github.com/tuvtran/project-based-learning) ⭐ 279,456 | 🐛 267 | 🌐 Python | 📅 2026-08-10
* [A curated list of awesome Raspberry Pi tools, projects, images and resources](https://github.com/thibmaek/awesome-raspberry-pi) ⭐ 16,744 | 🐛 17 | 🌐 Shell | 📅 2026-07-27
* [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) ⭐ 8,028 | 🐛 14 | 📅 2026-08-11 - Curated list of resources for Embedded and Low-level development in the Rust programming language.
* [Curated List of Self-Driving Cars and Autonomous Vehicles Resources](https://github.com/takeitallsource/awesome-autonomous-vehicles) ⭐ 2,389 | 🐛 1 | 📅 2024-03-15
* [awesome-c](https://github.com/uhub/awesome-c) ⭐ 2,209 | 🐛 11 | 📅 2026-08-04 - A curated list of awesome C frameworks, libraries and software.
* [awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems) ⭐ 1,005 | 🐛 8 | 📅 2024-01-04
* [theEmbeddedNewTestament.github.io](https://github.com/theEmbeddedGeorge/theEmbeddedNewTestament.github.io) ⭐ 939 | 🐛 2 | 🌐 C | 📅 2026-06-27
* [awesome-cheat-sheets](https://github.com/mintisan/awesome-cheat-sheets) ⭐ 155 | 🐛 0 | 📅 2023-12-13 - Awesome Cheat Sheets for Developer Utility, like Git, Vim, Tmux, Sublime Text, Markdown, Shell.
* [A curated list of project-based tutorials in C](https://github.com/rby90/Project-Based-Tutorials-in-C)

## BOOKs

* [Mastering the Raspberry Pi](http://web.archive.org/web/20190713103510/http://mensshed-llandudno.co.uk/wp-content/uploads/Mastering%20the%20Raspberry%20Pi.pdf)
* [Modern C](http://web.archive.org/web/20190219172719/http://icube-icps.unistra.fr/img_auth.php/d/db/ModernC.pdf)
* [An Embedded Software Primer](https://archive.org/details/embeddedsoftware00davi)
* [Embedded Software with Rust](https://www.manning.com/books/embedded-software-with-rust)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

* Fork the repository
* Create your feature branch (`git checkout -b feature/amazing-feature`)
* Commit your changes (`git commit -m 'Add amazing feature'`)
* Push to the branch (`git push origin feature/amazing-feature`)
* Open a Pull Request

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
