# Badger Lake Automations

## Base Unit (Raspberry Pi Zero WH)

The Raspberry Pi Zero series are much smaller than the primary Pi models.  They have a single core CPU instead of the quad core CPUs found on the primary models, but they also use much less power (.6W idle vs 2W and 1.5W under load vs 5W).

The W means that it has built-in WiFi and th H means that the GPIO headers are pre-installed/soldered to the board.

[Amazon Link (Quick Start Kit)](https://www.amazon.com/DIGISHUO-Pi-Zero-WH-Pre-Soldered/dp/B0BWT2CBJT/ref=sr_1_5?crid=S5PYY3JQYN4G&dib=eyJ2IjoiMSJ9.S0nv3nYiRnZdm96eKHJiJur6dxA5J56jNnwPHbBmTgXKkPSapg1_hbnlLp5vBv4xJD7z9xZ8kckhS-JtrVMPBqjLjmpvfID6l2riB9mvX0bueA516xo6aUd9lqXRRjyhGKQxV6SLstIoJ-2E8v5r5wQvW6G70GbiH9aIECj30lzn2hlc8H1qqFVY9dAZQxpCJvseljmBEqSs0n5JXx_7dzhV_0fpn5kJQh0WHGPZRx8.eWMGMCjBHtCLtTch76-iRXFhwaS_uEAFukx_gsdd5Vk&dib_tag=se&keywords=pi%2Bzero%2Bkit%2Bsoldered%2Bheaders&qid=1715572799&sprefix=pi%2Bzero%2Bkit%2Bsoldered%2Bheader%2Caps%2C150&sr=8-5&th=1)

All Raspberry Pi variants run a full OS.  Several Linux distributions are available with high compatibility and documentation of how to use all of the hardware features.  For the W models, it is common to run the OS headless without a window manager/desktop environment (command line only).  It is easy to setup features like an SSH server, moderm Python and associatied libraries/modules to interact with the hardwarre.

## Satellite Units (ESP-32 or variants)
* Arduino compatible
* can run micro Python
* many code eaxampes online/highly supported
* digital and analog GPIO
* very low power use, can have timed sleep mode for lower power use
* supports WiFi

[S2 Mini Amazon Link](https://www.amazon.com/Alinan-V1-0-0-ESP32-S2FN4R2-ESP32-S2-MicroPython/dp/B0B28LMBKD/ref=sr_1_5?crid=237B2STDTTLLZ&dib=eyJ2IjoiMSJ9.wz6SHWqGd5j0_MxPKEdv6uHtda7rZ3i7mktBPQ7h54qLeF0E27_D_9rOO-cgrF6OJEOXPelPm0ZctvwFF8hkPsGnKLuxBk_Hv3D6sk_c_k0ATDSEzytms_4wvuKWU-MZ7EW9yD8ITnW5BAbN4TG0xFpReAFt-uDGQD9g2UaTNg03TyDVBZiOfes24h89iQRJW_Sm3lYN9vo9cyZBC2KufxZAgr_ufbfHZwgm2zY5ZKiWR5qhBO3-VA0_PhjYFX4S_DZ9lDGWHQbfFGqZgY9BEfH20BZdI73N35rrzuDtefo.N7mRKb0NzWb7tqseQ_o8VBXwGb3ofr6DRMzh_WsYMMo&dib_tag=se&keywords=esp32&qid=1715924295&s=industrial&sprefix=esp32%2Cindustrial%2C134&sr=1-5&th=1)

## Sensors and Accessories

### GPIO Connectivity

[Female to Female Dupont Jumper Wire](https://www.amazon.com/Solderless-Multicolored-Electronic-Breadboard-Protoboard/dp/B09FP2QC95/ref=sr_1_9?crid=2OYJA2JVBCRDL&dib=eyJ2IjoiMSJ9.ZM40wq855MSOx2S-DNpAlsKk_dMAWIJw0rQw0JhGmLEevx8zkeyq0CJICMNSGzrCVlg_UpTWt7tOa52l-XGDcWWPTKCWtVR3saBGpuCu47KcfzNCSP2dbdtKJJLYwHlVMo9j4wfoejqqluzGBUToFRRTYuyXnu5AG0SnX4iD2qfGTzm0wI9BIzdMlgkKjVkFHp57jThNS7Ga_hSmAMYRLSXEwiSWKiOZpkmcMdGELHdowEKjqwtUCzPkbY6mmGIBNN5R6c_mgaqOnDCpVzNl6eGV5S3T_9EIVykVLD0zD8g.cLcqFrzvdek687HYaIb8sfKmfoTttMe_cekCsPuy4Ds&dib_tag=se&keywords=ELEGOO%2BMulticolored%2BDupont%2BWire%2Bfemale%2Bfemale&qid=1715574043&s=industrial&sprefix=elegoo%2Bmulticolored%2Bdupont%2Bwire%2Bfemale%2Bfemale%2Cindustrial%2C94&sr=1-9&th=1)
[Dupont/JST Connectors](https://www.amazon.com/Mesee-Connector-Assortment-Crimping-Connectors/dp/B09TPHY27V/ref=sr_1_63?crid=2Y7KY2E5ENN9Z&dib=eyJ2IjoiMSJ9.m90g_44b2aak96T9iOuSvkJVSQ2rDw7ZyJPGww-895j59urlVUfjKRMRtXVloyUTK81hpsY1rLQEnDnOsdrppIDFN1M4ZG47782uYaQsCu3aqaB1UyWQa8AMSWgwlEWePL4o4YKCRBZdNWH-c4ODM6hCOxVR33EFOfPprOOpwKTtXvMEWI8qcIQtIPpUZP7w.qbo2-GuG04VetMR4djpmW2NbuSvCkajQTEcFQzc_HDg&dib_tag=se&keywords=2+row+header+connectors&qid=1715573510&sprefix=2+row+header+connector%2Caps%2C154&sr=8-63)
[More Connectors](https://www.amazon.com/Mesee-Connector-Assortment-Crimping-Connectors/dp/B09TPHY27V/ref=sr_1_3?crid=249NVFPFC9ZQH&dib=eyJ2IjoiMSJ9.Ycw1IKcR0A0UWdxXhQT8n8WWg70Qxh2miaiLgbhXj4FjbvFi39aRgpaznsEIXmMYokseo8cgQTgu8zlL9dnonszuaKWD_uK3waET5prrz3BqvfW91S73psEsjUw8WKx2AsERzyofg8ZXoy_8QCRns8dNEyOR9QvYFxCbSrqT-EB_IAcePCRjn_nlX8YMEgobr6Ba2ssQ0m_Wf3tuz14J1m3_CDKdVQKSMcBk-A_heMA.JeZ1rl-Dzjw0mqo3wNH7i-DxKfR34FJJR6HspEYr4cY&dib_tag=se&keywords=dual+row+dupont+connectors&qid=1715574218&sprefix=dual+row+dupont+connectors%2Caps%2C187&sr=8-3)

### 4 Channel Realay Module

This board has four relays that ca nbe switched with 5V logic.  Many have successfully swtiched these using the 3.3v logic levels availble directly from the Raspberry Pi GPIO and ESP-32 GPIO.  The module also has the ability to optically couple the switching of the relays.  The relays can switch up to 250VAC @10A or 30VDC @10A, although it is recommened to run much lower loads through these.

[Amazon Link](https://www.amazon.com/ELEGOO-Channel-Optocoupler-Compatible-Raspberry/dp/B09ZQS2JRD?th=1)

### Ultrasonic Sonar Distance Sensor (HC-SR04)

* 2cm to 4m sensing range
* digital trigger
* measurement is proportional to the time the measurement line stays high (time between L->H and subsequent H->L transisitions)
working Vcc is 5VDC but many have had success using 3.3VDC directly from Pi or ESP-32

[Amazon Link](https://www.amazon.com/dp/B07L68X65N/ref=sspa_dk_detail_2?pd_rd_i=B07L68X65N&pd_rd_w=yJKf3&content-id=amzn1.sym.f734d1a2-0bf9-4a26-ad34-2e1b969a5a75&pf_rd_p=f734d1a2-0bf9-4a26-ad34-2e1b969a5a75&pf_rd_r=X1KBW7P8C627G3CQ08TT&pd_rd_wg=QiwV7&pd_rd_r=9e472271-3ac5-4ebc-936a-dec2f2c6e921&s=industrial&sp_csd=d2lkZ2V0TmFtZT1zcF9kZXRhaWw&th=1)

[Whitesheet](https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf)

[Example Arduino GitHub Repo](https://github.com/sparkfun/HC-SR04_UltrasonicSensor)

### LoRa Radio Module (Heltec V3)

* supports wifi
* supports bluetooth
* supports LoRa (LongRange radio)
- can transmit small text messsages over several miles with line of sight
- supports [Meshtastic](https://meshtastic.org/) firmware for automatic mesh network creation
- runs on 915Mhz ISM band
- completely decentralized (no separate infrastructure or cell network required)
* ESP-32 based
- firmware can be changed
- can fork and add features to open source firmware like Meshtastic

[Amazon Link](https://www.amazon.com/dp/B08629526P?psc=1&ref=ppx_yo2ov_dt_b_product_details)
