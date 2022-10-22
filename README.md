# ESPHome AirGradient config

This is a [ESPHome](https://esphome.io/) config for the [AirGradient DIY Pro Presoldered Kit](https://www.airgradient.com/open-airgradient/shop/#!/DIY-Pro-Kit-Pre-Soldered/p/476627519/category=0).

## Usage
1. Setup the [esphome cli](https://esphome.io/guides/getting_started_command_line.html)
2. Download / pick a font for the display, adjust the yaml config accordingly
3. Connect a usb cable from where the CLI will run to the esp8266 d1_mini
4. Put wifi SSID and password in secrets.yaml
5. Run esphome to flash the esp8266
    ```sh
    esphome run airgradient.yaml
    ```