# F3188

## Notes

| CSR PIN | F3188 PIN | Notes |
| -------- | -------- |-------|
| RST# | RST |Reset pin needs min 2.4s low to shutdown the Chip. has a build in Pull-Up Resistor|
| VREGENABLE | POWER_EN |A high signal powers up the chip.|
|  |  |Its tolerant to the VBAT. Button should be connected to VBAT.|
|  |  |Can, after power up, be used for other things. Has a build in Pull-Down.|
