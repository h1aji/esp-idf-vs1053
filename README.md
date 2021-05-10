# esp-open-rtos-vs1053
VS1053 Driver for esp-open-rtos.

# Configure
You have to set this config value with menuconfig.
- CONFIG_ESP_WIFI_SSID
- CONFIG_ESP_WIFI_PASSWORD
- CONFIG_ESP_MAXIMUM_RETRY
- CONFIG_GPIO_CS
- CONFIG_GPIO_DCS
- CONFIG_GPIO_DREQ
- CONFIG_GPIO_RESET
- CONFIG_SERVER_HOST
- CONFIG_SERVER_PORT
- CONFIG_SERVER_PATH

![config-1](https://user-images.githubusercontent.com/6020549/76663983-3415df00-65c6-11ea-93db-9ec83e2601df.jpg)
![config-2](https://user-images.githubusercontent.com/6020549/76663991-35dfa280-65c6-11ea-8ef4-0c2701ce6b48.jpg)

# Wiring

|VS1053||ESP32|
|:-:|:-:|:-:|
|5V|--|VIN|
|DGND|--|GND|
|MISI|--|GPIO19|
|MOSI|--|GPIO23|
|SCK|--|GPIO18|
|DREQ|--|GPIO4|
|RST|--|EN|
|CS|--|GPIO5|
|DCS|--|GPIO16|
