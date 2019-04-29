---
layout: post
title: How To Start Programming
date: 2017-09-12 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: bridge1025x726.png # Add image post (optional)
tags: [Programming, Learn] # add tag
---
硬件平台1: Arduino 市售硬件平台約可分為三大類型 A.原創硬件設計Arduino B.複刻版硬件設計Arduino C.專業芯片原廠硬件設計,除了Arduino標準介面並含進階特色介面. 三大類型的硬件特色是都可以使用原創公司的Arduino IDE開發平台

硬件平台2: Raspberry Pi 市售硬件平台約可分為三大版本三大類型 A.Raspberry Pi2 B.Raspberry Pi3 C.Raspberry Pi Computer Module, 硬件版本很多種, 值得介紹的是 Raspberry Pi3 Pi3+ CM3 CM3+ ,Raspberry Pi目前不僅在Linux支持,同時也被Windows支持, 此外也有其他軟件系統支持

硬件平台3: Jetson Nano 市售硬件平台正值芯發售,也是硬件發行的第一版.  

### 原創硬件Arduino
版本Arduino Nano
>原創雙排GPIO的最小硬件模板(近似一顆DIP芯片排列), 使用micro USB與電腦對接

版本Arduino Uno
>雙列GPIO手掌大小,應用最廣的硬件版本幾乎是Arduino代表, 教學性質或入門學習使用, 透過USB type-B與電腦對接

版本Arduino Meaga
>雙列GPIO長方形尺寸, 一般多為GPIO應用不足而選用

![I and My friends]({{site.baseurl}}/assets/img/we-in-rest.jpg)


### 複刻版硬件Arduino
主要芯片還是一樣但USB介面只有模擬及下載,另外附加的串口Serial port功能. 其他幾乎是共通的.
>與原創主要差異為不能進行HID通訊模擬, 範例使用上要注意與HID相關的應用

### 專業芯片原創硬件Arduino
主要芯片以完全不一樣, 硬件介面不一, 軟件介面可以同時用Arduino IDE與專業芯片廠家提供等數種不同開發環境IDE, 使用原創之Arduino IDE幾乎是通過載入硬件連接介面驅動完成模擬
>MediaTek MT7697 (含WiFi,BT)
>Espressif ESP-WROOM-32 (含WiFi,BT,BLE)
>Realtek RTL8711AM (含WiFi)


