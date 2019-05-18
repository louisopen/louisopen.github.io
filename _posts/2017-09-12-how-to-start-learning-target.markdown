---
layout: post
title: How To Start Target Board
date: 2019-04-28 11:30:00 +0800
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: Boards.jpg  # Add image post (optional)
tags: [Programming, AI Learnning, Arduino, Raspberry Pi, Jetson Nano, Azure, AWS, Google GAE, Thingspeak, Exosite, 智慧聯網大平台] # add tag
---

編程到底是如何開始?

# ~

### 平台(Hardware/Cloud) 你的志向
當你開始學習如何編寫程式時一定會問自己幾個問題,如:編寫純軟體(軟件)還是帶有芯片IC的軟體(又稱韌體或稱Firmware)? 職業生涯上當然是愈廣愈好,但困難度也相對一定高,但如果有適當方法及途徑,再經過名師點化,相信水到可以渠成,所以我們就用市場上幾個相對簡單又可以容易購買的硬件平台,在市場上容易取得又不是很貴的價格,既可以容易取得範例也有相對的可靠性,就從這個面向持續擴大自己的知識面向開始吧!

另外一個是非硬件的平台,指的就是大型的雲端系統平台提供者Microsoft Azure, Amazon AWS, Google GAE..., 這些產也衍生雲端應用平台產業如ThingSpeak, Exosite, 中華電信智慧聯網大平台...這方面的產業面非常廣,知識及經驗要不斷增長才能應付人文科學的快速變化及需求



#### Arduino硬件平台: 
* 非常適合初學者的Arduino 市售硬件平台約可分為三大類型 A.原創硬件設計Arduino B.複刻版硬件設計Arduino C.專業芯片原廠硬件設計,除了Arduino標準介面並含進階特色介面. 三大類型的硬件特色是都可以使用原創公司的Arduino IDE開發平台.
* 官網: [Arduino](https://www.arduino.cc/)

#### Arduino原創硬件版本
##### 原創版本Arduino Nano: 原創雙排GPIO(15pin x2)的最小硬件模板(近似一顆DIP芯片排列),使用mini USB接口與電腦對接
>![ArduinoNano]({{site.baseurl}}/assets/img/ArduinoNano.jpg){:height="40px" width="100px"}

##### 原創版本Arduino Uno: 雙列GPIO(28pin)手掌大小,應用最廣的硬件版本幾乎是Arduino代表,教學性質或入門學習使用,透過USB type-B與電腦對接
>![ArduinoUno]({{site.baseurl}}/assets/img/ArduinoUno.jpg){:height="150px" width="200px"}

##### 原創版本Arduino Mega: 多列GPIO長方形尺寸,一般多為GPIO應用不足而選用,透過USB type-B與電腦對接
>![ArduinoMega]({{site.baseurl}}/assets/img/ArduinoMega.jpg){:height="150px" width="280px"}

#### 複刻版硬件Arduino
主要芯片還是一樣但USB介面只有模擬及下載,另外附加的串口Serial port功能. 其他幾乎是共通的.
>與原創主要差異為不能進行HID通訊模擬, 範例使用上要注意與HID相關的應用

#### 專業芯片原創硬件Arduino
主要芯片以完全不一樣, 硬件介面不一, 軟件介面可以同時用Arduino IDE與專業芯片廠家提供等數種不同開發環境IDE, 使用原創之Arduino IDE幾乎是通過載入硬件連接介面驅動完成模擬
>MediaTek MT7697 (含WiFi,BT)
![I and My friends]({{site.baseurl}}/assets/img/ArduinoMT7697.jpg){:height="130px" width="200px"}

>Espressif ESP-WROOM-32 (含WiFi,BT,BLE)
![I and My friends]({{site.baseurl}}/assets/img/ArduinoESP WROOM 32.jpg){:height="130px" width="200px"}

>Realtek RTL8711AM (含WiFi)
![I and My friends]({{site.baseurl}}/assets/img/ArduinoRTL8711AM.jpg){:height="130px" width="200px"}

>Will be continue other ...



### Raspberry Pi硬件平台: 
* 有興趣再進一步了解物聯網OS平台者,這是一個非常好的環境Raspberry Pi(樹莓派)市售硬件平台約可分為三大版本三大類型 A.Raspberry Pi2 B.Raspberry Pi3 C.Raspberry Pi Computer Module, 硬件版本很多種, 值得介紹的是 Raspberry Pi3 Pi3+ CM3 CM3+ ,Raspberry Pi目前不僅在Linux支持,同時也被Windows支持, 此外也有其他軟件系統支持.
* 官網: [RaspberryPi](https://www.raspberrypi.com.tw/)

#### Raspberry Pi 2樹莓派版本
整合多種試驗後,主要的硬體版本分Raspberry Pi 2 A版(GPIO 20pin)與Raspberry Pi B版(GPIO 40pin)
>
![RaspberryPi2A]({{site.baseurl}}/assets/img/RaspberryPi2A.jpg){:height="130px" width="200px"}
![RaspberryPi2B]({{site.baseurl}}/assets/img/RaspberryPi2B.jpg){:height="130px" width="200px"}

#### Raspberry Pi 3樹莓派版本
延續Raspberry Pi 2精神,效能再度提升兩個版次Pi 3及Pi 3Plus,要小心的是Pi 3與Pi 3Plus由很大的差異是芯片升級相容性高但周邊芯片更換由原先的只支持WiFi+BLE提升為WiFi+BT+BLE還有提升到可以自行加入POE的應用(網線帶電)
>
![RaspberryPi_Pi3B]({{site.baseurl}}/assets/img/RaspberryPi3B.jpg){:height="130px" width="200px"}
![RaspberryPi_Pi3B+]({{site.baseurl}}/assets/img/RaspberryPi3B+.jpg){:height="130px" width="200px"}

#### Raspberry Pi CM module 樹莓派模組版本
最大的色在於已經將記憶體內置於模組內分為8G,16G,32G版本,當然還是有保留外接SD card的型號,這樣的考慮應該足夠應付市場需求,更別說創客市場了,也非常適合工業上的應用及生產,因為無其他周邊裝置,網路及額外的USB裝置等都需要另外設計,但已經簡化相當多的設計驗證等問題
>
![RaspberryPi_CM]({{site.baseurl}}/assets/img/RaspberryPi_CM_module.jpg){:height="150px" width="300px"}



### Jetson Nano硬件平台:  
* 市售硬件平台正值新一代芯片發售,也是Jetson nano 2019發行的第一版硬件,各個產業的終端應用場景看來,各家芯片廠已經在方案上都有著墨已經備好了AIOT的硬件.
* 官網: [Jetson-nano](https://www.nvidia.com/zh-tw/autonomous-machines/embedded-systems/jetson-nano/)

#### Jetson nano module
迎戰Raspberry Pi的殺手級終端產品應用,模組有AI圖像運算,各大知名方案公司都下海爭取各個終端產業之多樣性應用硬件,主要針對創客市場.
>
![JetsonNano_CM]({{site.baseurl}}/assets/img/JetsonNano_CM_module.jpg){:height="130px" width="200px"}



### 仿Raspberry Pi不同風格的硬件平台: 
* 市售硬件標準平台在中國也一片看好,號稱多達12種的標準硬件平台,實在太多了!但有一點不變的是大多數的OS平台語言是共用的,連微軟(Microsoft)都來卡一腳,即將推出Windows 10 Lite 或 Windows 10 IOT core來加入開發者的這個市場,會愈來愈熱鬧的.
* 介紹: [多達12款的硬件平台](https://linux.cn/article-10823-1.html)
>

