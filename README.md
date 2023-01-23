# HomeAssistantUtilies
Home Assistant Utilities
1. ble_sensor_gen.ipynb - YAML generator for Xiaomi LYWSD03MMC thermometer
## Instructions:
 fill in "data" variable with key-value pairs for devices. The key is the name and the value is the mac of the device(you can get them from tasmota console):
 `data = {
"livingroom":"ATCxxxxxx",
"dorm":"ATCxxxxxx",
"kitchen":"ATCxxxxxx",
}`