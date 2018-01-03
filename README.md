# F3188

## Notes

| CSR PIN | F3188 PIN | Notes |
| -------- | -------- |-------|
| RST# | RST |Reset pin needs min 2.4s low to shutdown the Chip. has a build in Pull-Up Resistor|
| VREGENABLE | POWER_EN |A high signal powers up the chip.|
|  |  |Its tolerant to the VBAT. Button should be connected to VBAT.|
|  |  |Can, after power up, be used for other things. Has a build in Pull-Down.|
| ? | VCC | Not sure if connected directly to a pin on the CSR8645 |
| VBAT | VBAT | seems to be direclty connected to VBAT |
| SPI_PCM# | SPI_PCM | High for SPI operation|
| | | LOW for PCM operation|
