# 硬件
- nodemcu v2
- 杜邦线 面包板
- led
- 数据线

# 软件支持
- esptool 用于刷写固件
- esp8266 的micropython 固件：https://micropython.org/download/esp8266/

# mac 查看串口
ls /dev/cu.*

# 擦除
esptool.py --port /dev/cu.wchusbserial526F0028041 erase_flash

# 刷固件
esptool.py --port /dev/cu.wchusbserial526F0028041 --baud 460800 write_flash --flash_size=detect 0 esp8266-20230426-v1.20.0.bin


# VSCODE 插件
- Micropython IDE
- Python

