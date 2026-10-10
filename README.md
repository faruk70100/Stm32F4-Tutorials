# STM32F4 Discovery Tutorials 🚀

Bu depo, STM32F4 Discovery geliştirme kartını kullanarak adım adım pratik yapmak, çevresel birimleri (peripherals) ve RTOS yapılarını öğrenmek amacıyla hazırladığım örnek projeleri ve eğitim içeriklerini barındırmaktadır.

## 🛠️ Kullanılan Araçlar ve Teknolojiler

* **Donanım:** STM32F4 Discovery Board (STM32F407VGT6)
* **IDE & Derleyici:** STM32CubeIDE
* **Kütüphane:** STM32F4xx HAL (Hardware Abstraction Layer) / C & C++

---

## 📂 Depo İçeriği ve Projeler

Depo içerisindeki her bir klasör belirli bir konuyu veya çevresel birimi ele almaktadır:

| Klasör Adı | Açıklama |
| :--- | :--- |
| **`led_blinking`** | Temel GPIO çıkış konfigürasyonu ve gecikme (delay) ile LED yakıp söndürme uygulaması. |
| **`Buton_Using`** | GPIO giriş konfigürasyonu, buton okuma ve pull-up/pull-down direnç mantığı. |
| **`external_interrupt`** | Harici kesmeler (EXTI) kullanarak buton basmalarına anlık tepki verme uygulaması. |
| **`ADC_Pull_For_Conversion`** | ADC (Analog-to-Digital Converter) biriminin polling (yoklama) yöntemiyle analog veri okuması. |
| **`ADC_Poll_Conversion_Interrupt`** | ADC okuma işlemlerinin kesme (interrupt) destekli ve polling kombinasyonuyla yönetilmesi. |
| **`DMA_Memory`** | DMA (Direct Memory Access) kullanarak işlemciyi yormadan bellek ve veri transferi yapılması. |
| **`PWM_Motor_Controller`** | Timer modülleri kullanılarak PWM (Pulse Width Modulation) sinyali üretimi ve motor kontrolü. |
| **`Rtos_1`** | FreeRTOS temelleri, görev (task) oluşturma ve çoklu görev yönetimine giriş uygulaması. |

---

## 🚀 Başlarken

Projeleri kendi bilgisayarınızda çalıştırmak için izlemeniz gereken adımlar:

1. Depoyu klonlayın:
   ```bash
   git clone [https://github.com/faruk70100/Stm32F4-Tutorials.git](https://github.com/faruk70100/Stm32F4-Tutorials.git)
