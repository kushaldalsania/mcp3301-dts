# mcp3301-dts
Beaglebone Device tree overlay for MCP3301

### Tested for Beaglebone Green running kernel 4.14.108-ti-r113

### Compilation
Best way to compile device tree is to:
1. clone [bb.org-overlays](https://github.com/beagleboard/bb.org-overlays)
2. copy dts file to `bb.org-overlays/src/arm/`
3. Compile. For example: `make src/arm/BB-SPI1-GPIO-CS-MCP3301-00A0.dts`