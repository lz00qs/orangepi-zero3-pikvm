# orangepi-zero3-pikvm
## Intro
This is a pikvm port based on OrangePi Zero3 with a bom cost of less than 200 RMB.
You can learn about pikvm in their [official repo](https://github.com/pikvm/pikvm).

## What is working
- [x] KVMD basic PiKVM software package
- [x] USB video capture (MS2109, MS2130)
- [x] USB virtual keyboard and mouse
- [x] USB virtual massive storage
- [x] ATX power control
- [x] OLED module system info display
- [ ] WiFi/BT module is not working. Because of the use of a module(Cdtech 20U5622) from a small Chinese manufacturer, driver adaptation has not yet been achieved.

## How to make it
### Software
Not only can you download the image directly from releases, but you can also use this [repo](https://github.com/lz00qs/orangepi-zero3-pikvm-builder) to build a flashable image yourself.
Then use the balenaetcher or dd to burn the image to the TF card.

### Hardware
See this [repo](https://github.com/lz00qs/orangepi-zero3-pikvm-hardware) to get all the PCB and printable 3D models.

Just to remind you, if your motherboard doesn't set the USB power to be on all the time, then you need to DIY a Type-C cable to separate the Orange Pi Zero3 Type-C's power and data.

## Future development
- [ ] Replace copy build system with patch build system
- [ ] WiFi/BT module

## Contributions

@lz00qs

## License

GPL V3.0
