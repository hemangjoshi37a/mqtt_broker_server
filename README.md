# How to create simple mqtt broker server in Ubuntu

## Step 1 : Install Mosquitto

Command : `sudo apt-get install mosquitto mosquitto-clients`

## Step 2 : Configure mosquitto 

Goto the location : `/etc/mosquitto/conf.d`

Create new file named : `default.conf`

enter the text as below in the default.conf
```
allow_anonymous true
listener 1883 
```

## Step 3 : Restart mosquitto

Command : `sudo systemctl restart mosquitto`

Check if the service is running

Command : `sudo systemctl status mosquitto`

Output :
```
● mosquitto.service - Mosquitto MQTT Broker
     Loaded: loaded (/lib/systemd/system/mosquitto.service; enabled; vendor preset: enabled)
     Active: active (running) since Wed 2022-10-19 11:52:02 IST; 1s ago
```



![https://hjlabs.in](https://hjlabs.in/wp-content/uploads/2022/05/rainbow-text-1.png "Image Title")

------------------------------------------------------------------------------

### Contact us

Mobile : [+917016525813](tel:+917016525813)
Whatsapp & Telegram : [+919409077371](tel:+919409077371)

Email : [hemangjoshi37a@gmail.com](mailto:hemangjoshi37a@gmail.com)

Place a custom order on hjLabs.in : [https://hjLabs.in](https://hjlabs.in/)

Please contribute your suggestions and corections to support our efforts.

Thank you.

Buy us a coffee for $5 ?

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=5JXC8VRCSUZWJ)

----------------------------------------------------------------------------------------

## Checkout Our Other Repositories

- [pyPortMan](https://github.com/hemangjoshi37a/pyPortMan)
- [transformers_stock_prediction](https://github.com/hemangjoshi37a/transformers_stock_prediction)
- [TrendMaster](https://github.com/hemangjoshi37a/TrendMaster)
- [hjAlgos_notebooks](https://github.com/hemangjoshi37a/hjAlgos_notebooks)
- [AutoCut](https://github.com/hemangjoshi37a/AutoCut)
- [My_Projects](https://github.com/hemangjoshi37a/My_Projects)
- [Cool Arduino and ESP8266 or NodeMCU Projects](https://github.com/hemangjoshi37a/my_Arduino)
- [Telegram Trade Msg Backtest ML](https://github.com/hemangjoshi37a/TelegramTradeMsgBacktestML)

## Checkout Our Other Products

- [WiFi IoT LED Matrix Display](https://hjlabs.in/product/wifi-iot-led-display)
- [SWiBoard WiFi Switch Board IoT Device](https://hjlabs.in/product/swiboard-wifi-switch-board-iot-device)
- [Electric Bicycle](https://hjlabs.in/product/electric-bicycle)
- [Product 3D Design Service with Solidworks](https://hjlabs.in/product/product-3d-design-with-solidworks/)
- [AutoCut : Automatic Wire Cutter Machine](https://hjlabs.in/product/automatic-wire-cutter-machine/)
- [Custom AlgoTrading Software Coding Services](https://hjlabs.in/product/custom-algotrading-software-for-zerodha-and-angel-w-source-code//)
- [SWiBoard :Tasmota MQTT Control](https://play.google.com/store/apps/details?id=in.hjlabs.swiboard)
- [Custom Token Classification or Named Entity Recognition (NER) model as in Natural Language Processing (NLP) Machine Learning](https://hjlabs.in/product/custom-token-classification-or-named-entity-recognition-ner-model-as-in-natural-language-processing-nlp-machine-learning/)

## Some Cool Arduino and ESP8266 (or NodeMCU) IoT projects

- [IoT_LED_over_ESP8266_NodeMCU : Turn LED on and off using web server hosted on a nodemcu or esp8266](https://github.com/hemangjoshi37a/my_Arduino/tree/master/IoT_LED_over_ESP8266_NodeMCU)
- [ESP8266_NodeMCU_BasicOTA : Simple OTA (Over The Air) upload code from Arduino IDE using WiFi to NodeMCU or ESP8266](https://github.com/hemangjoshi37a/my_Arduino/tree/master/ESP8266_NodeMCU_BasicOTA)  
- [IoT_CSV_SD : Read analog value of Voltage and Current and write it to SD Card in CSV format for Arduino, ESP8266, NodeMCU etc](https://github.com/hemangjoshi37a/my_Arduino/tree/master/IoT_CSV_SD)  
- [Honeywell_I2C_Datalogger : Log data in A SD Card from a Honeywell I2C HIH8000 or HIH6000 series sensor having external I2C RTC clock](https://github.com/hemangjoshi37a/my_Arduino/tree/master/Honeywell_I2C_Datalogger)
- [IoT_Load_Cell_using_ESP8266_NodeMC : Read ADC value from High Precision 12bit ADS1015 ADC Sensor and Display on SSD1306 SPI Display as progress bar for Arduino or ESP8266 or NodeMCU](https://github.com/hemangjoshi37a/my_Arduino/tree/master/IoT_Load_Cell_using_ESP8266_NodeMC)
- [IoT_SSD1306_ESP8266_NodeMCU : Read from High Precision 12bit ADC seonsor ADS1015 and display to SSD1306 SPI as progress bar in ESP8266 or NodeMCU or Arduino](https://github.com/hemangjoshi37a/my_Arduino/tree/master/IoT_SSD1306_ESP8266_NodeMCU)  

## Checkout Our Awesome 3D GrabCAD Models
- [AutoCut : Automatic Wire Cutter Machine](https://grabcad.com/library/automatic-wire-cutter-machine-1)
- [ESP Matrix Display 5mm Acrylic Box](https://grabcad.com/library/esp-matrix-display-5mm-acrylic-box-1)
- [Arcylic Bending Machine w/ Hot Air Gun](https://grabcad.com/library/arcylic-bending-machine-w-hot-air-gun-1)
- [Automatic Wire Cutter/Stripper](https://grabcad.com/library/automatic-wire-cutter-stripper-1)

## Our HuggingFace Models :
- [hemangjoshi37a/autotrain-ratnakar_1000_sample_curated-1474454086 : Stock tip message NER(Named Entity Recognition or Token Classification) using HUggingFace-AutoTrain and LabelStudio and Ratnakar Securities Pvt. Ltd.](https://huggingface.co/hemangjoshi37a/autotrain-ratnakar_1000_sample_curated-1474454086)

## Our HuggingFace Datasets :
- [hemangjoshi37a/autotrain-data-ratnakar_1000_sample_curated : Stock tip message NER(Named Entity Recognition or Token Classification) using HUggingFace-AutoTrain and LabelStudio and Ratnakar Securities Pvt. Ltd.](https://huggingface.co/datasets/hemangjoshi37a/autotrain-data-ratnakar_1000_sample_curated)

## We sell Gigs on Fiverr : 
- [code android and ios app for you using flutter firebase software stack](https://business.fiverr.com/share/3v14pr)
- [code custom algotrading software for zerodha or angel broking](https://business.fiverr.com/share/kzkvEy)
