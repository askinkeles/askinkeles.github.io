---
layout: default
title: Donanım Mühendisliği
permalink: /tr/HARDWARE/
---

<div style="text-align: right;">
  <a href="../../HARDWARE/">🇺🇸 English</a> | <a href="../">🏠 Anasayfa</a>
</div>

# 🧱 Donanım Mühendisliği & Gömülü Sistemler

Bu bölüm, elektronik tasarımı, bileşen seçimi ve firmware mimarisi konusundaki teknik uzmanlığımı içerir.

## ⚡ Elektronik Bileşenler & Düşük Seviye Haberleşme
* **Yüksek Hız (SPI):** DMA (Doğrudan Bellek Erişimi) entegrasyonu ve Thread-Safe (İş parçacığı güvenli) işlemler.
  * ↳ 📂 *Referans Proje:* [**ESP32 SPI & DMA Ustalık Rehberi**](https://github.com/askinkeles/Embedded-SPI-Guide)
* **Sensör Ağları (I2C):** Çoklu slave yönetimi, zaman aşımı (timeout) kurtarma.
  * ↳ 📂 *Referans Proje:* [**Sağlam I2C Haberleşme Rehberi**](https://github.com/askinkeles/Embedded-I2C-Guide)

## 🧩 Elektronik Modüller & Endüstriyel Sensörler
* **Endüstriyel Seri Haberleşme (RS-485):** Gürültü bastırma, Ring Buffer yapıları.
  * ↳ 📂 *Referans Proje:* [**Endüstriyel UART & RS-485 Rehberi**](https://github.com/askinkeles/Embedded-UART-Guide)
* **Otomotiv & Ağır Sanayi (CAN Bus):** Donanımsal filtreleme (Mask/Code), Tahkim (Arbitration).
  * ↳ 📂 *Referans Proje:* [**ESP32 TWAI (CAN Bus) El Kitabı**](https://github.com/askinkeles/Embedded-CANBus-Guide)

## 🛠️ Gömülü Mühendislik & Firmware Mimarisi
* **Profesyonel Firmware Mimarisi:** Modüler C++ tasarım kalıpları, HAL (Donanım Soyutlama Katmanı).
  * ↳ 📂 *Referans Proje:* [**ESP32 Pro Firmware Mimarisi**](https://github.com/askinkeles/ESP32-Pro-Firmware-Architecture)
