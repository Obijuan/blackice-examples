#-- Commands for using apio with mystorm blackice


### Build
apio build --fpga iCE40-HX4K-TQ144 --size 8k --pack tq144:4k --type hx

### Upload
cat hardware.bin > /dev/ttyUSB0
