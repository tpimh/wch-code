# WCH demo code
8051 code published by WCH

The code is public domain if not stated overwise. The original source code was published by WCH on wch.cn, winchiphead.com and wch-ic.com.

I didn't modify any information of the original source, only converted it from GB2312 to UTF-8 with UNIX line terminators.

Hope it may be usefull to someone.

## Structure

- *include/* — headers

## MCU Selection Guide

### 8051 microcontrollers

All listed microcontrollers have an advanced 8051 core (8-15 times faster than original MCS-51), 256 byte of IRAM, Unique Chip ID feature and 16 bit timer resolution.

| Model | Frequency (MHz) | XRAM (byte) | Code Flash (byte) | Data Flash (byte) | USB 2.0 (Full Speed) | Type-C | Touch Key | UART | SPI | ADC | PWM | Timer | CAP | Package |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CH551G | 32 | 512 | 10K | 128 | Device |  | 5/10 | 1 | 1 |  | 2 | 3 | 2 | SOP16 |
| CH552G | 32 | 1K | 16K | 128 | Device | + | 5/10 | 2 | 1 | 4×8bit | 2 | 3 | 2 | SOP16 |
| CH552E | 32 | 1K | 16K | 128 | Device | + | 5/10 | 1 | 1 | 2×8bit | 1 | 3 | 1 | MSOP10 |
| CH552T | 32 | 1K | 16K | 128 | Device | + | 6/15 | 2 | 1 | 4×8bit | 2 | 3 | 2 | TSSOP20 |
| CH553G | 32 | 512 | 10K | 128 | Device/Host | + | 5/10 | 1 | 1 | 4×8bit | 2 | 3 | 2 | SOP16 |
| CH554G | 32 | 1K | 16K | 128 | Device/Host | + | 5/10 | 2 | 1 | 4×8bit | 2 | 3 | 2 | SOP16 |
| CH554E | 32 | 1K | 16K | 128 | Device/Host | + | 5/10 | 1 | 1 | 2×8bit | 1 | 3 | 1 | MSOP10 |
| CH554T | 32 | 1K | 16K | 128 | Device/Host | + | 6/15 | 2 | 1 | 4×8bit | 2 | 3 | 2 | TSSOP20 |
| CH555T | 55 | 1K | 32K | 1K | 1×Device/2×Host |  |  | 2/RS485 | 1 | 5×11bit | 1 | 4 | 2 | TSSOP20 |
| CH557T | 58 | 4K | 63K | 1K |  |  |  | 2 | 1 | 5×11bit | 3 | 4 | 2 | SSOP20 |
| CH557Q | 58 | 4K | 63K | 1K |  |  |  | 2/RS485 | 1 | 8×11bit | 3 | 4 | 3 | LQFP44 |
| CH558T | 56 | 4K | 35K | 5K | Device |  |  | 2 | 1 | 5×11bit | 1 | 4 | 2 | SSOP20 |
| CH558L | 56 | 4K | 35K | 5K | Device |  |  | 2/RS485 | 1 | 8×11bit | 1 | 4 | 3 | LQFP48
| CH559T | 56 | 6K | 63K | 1K | Device/Host |  |  | 2 | 1 | 5×11bit | 2 | 4 | 2 | SSOP20 |
| CH559L | 56 | 6K | 63K | 1K | 1×Device/2×Host |  |  | 2/RS485 | 2 | 8×11bit | 3 | 4 | 3 | LQFP48 |

### 8bit RISC microcontrollers

All listed microcontrollers have an in-house 8bit RISC core, 1 UART, 1 Watchdog, 1 8bit timer and 1 16bit timer.

| Model | Frequency (MHz) | RAM (byte) | Code Flash (byte) | Data Flash (byte) | USB 2.0 | SPI | I/Os | Package |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| CH530G | 10 | 256 | 4K | 64 | Device (Low Speed) |  | 11/39 | SOP16 |
| CH530Q | 10 | 256 | 4K | 64 | Device (Low Speed) |  | 11/39 | LQFP44 |
| CH534G | 14 | 384 | 8K | 64 | Device (Full Speed) | 1 | 11/23 | SOP16 |
| CH534S | 14 | 384 | 8K | 64 | Device (Full Speed) | 1 | 11/23 | SOP28 |
| CH536G | 14 | 384 | 8K | 64 | Device, Host (Full Speed) | 1 | 11/23/41 | SOP16 |
| CH536S | 14 | 384 | 8K | 64 | Device, Host (Full Speed) | 1 | 11/23/41 | SOP28 |
| CH536L | 14 | 384 | 8K | 64 | Device, Host (Full Speed) | 1 | 11/23/41 | LQFP48 |
| CH537X | 15 | 768 | 32K |  | 4×Device, 3×Host (Full Speed) | 1 | 37 | LQFP48 |

### 32bit ARM microcontrollers

All listed microcontrollers have an ARM9 core (ARMv5TE) with base frequency of 100MHz (burstable up to 130MHz), 28 Kbyte data flash, 100M Ethernet MAC and PHY, Unique Chip ID feature, 2 UARTs, 2 SPIs, 4 PWMs, 4 CAPs, 10bit ADC resolution and 4 28bit timers.

| Model | RAM (byte) | Code Flash (byte) | USB 2.0 (High Speed) | ADC | Package |
| --- | --- | --- | --- | --- | --- |
| CH561Q | 32K | 64K |  | 1 | LQFP64M |
| CH563Q | 64K | 224K | Device/Host | 1 | LQFP64M |
| CH563L | 64K | 224K | Device/Host | 3 | LQFP128 |
