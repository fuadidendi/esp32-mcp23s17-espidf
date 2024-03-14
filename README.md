<div align="center">

# ESP32 MCP23S17 DRIVER

</div>

## Folder contents

The project **esp32-mcp23017-espidf** contains one source main file in C language [main.c](main/main.c). The file is located in folder [main](main).

This project give an example how to access mcp23017 via SPI interface. You can find the detail about mcp23s17 from [mcp23s17 datasheet](https://ww1.microchip.com/downloads/en/devicedoc/20001952c.pdf).

This ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt
├── include
│   └──  mcp23s17.h
├── main
│   ├── CMakeLists.txt
│   ├── main.c
│   └── mcp23s17.c
└── README.md                  This is the file you are currently reading
```
