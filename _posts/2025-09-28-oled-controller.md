---
title: OLED Controller
date: 2025-09-28 11:00:00 +1300
categories: [Projects]
tags: [pyqt, platformio, oled, nrf]
---

I had an OLED screen lying around, I decided it was time to give it a little personality. No particular reason - just pure experimentation.

This project is all about messing with an OLED driver and a lightweight desktop app to send images and animations to the screen.

# Hardware

## OLED Screen

I am using a [Grove - OLED Display 0.96" (SSD1315)](https://wiki.seeedstudio.com/Grove-OLED-Display-0.96-SSD1315/), which is a monochrome 128x64 pixel display and has an I2C interface.
I removed the 4-pin I2C header and moved it to the back because I didn't want the wires sticking out over the screen.

## Controller

I have a couple of [Seeed Studio XIAO nRF52840 Sense](https://wiki.seeedstudio.com/XIAO_BLE/) that were perfect for this project. It's tiny, has a nice USB interface, and it has several GPIOs to utilize. This board has lots of features that I don't need (BLE, IMU, microphone, battery charging, additional flash, etc.). Maybe in the future I will utilize some of these features, e.g. I could add a battery and use BLE to send images instead of serial USB. 

## Casing

The [casing is 3D printed](https://cad.onshape.com/documents/57535a84b8613a4384fcd9f1/w/855ea2d725360c99a9cd3771/e/f0070173e1d9ac47f211a9f3?renderMode=0&uiState=68d868069bcc8696d0914b52) and only really serves to hide the wires and provide a bit of rigidity. The XIAO nRF52840 Sense is press-fitted so it can be easily removed and repurposed if needed for other projects. The OLED display is held in with a single screw so can also be removed and repurposed.

# Firmware

First time using Platform-IO.

# Desktop Application

## Binary Images

## Dithering

## Animations

# Future

