# ssd-trim-enablement
Script to enable TRIM on an SSD

This script can be run on Raspberry Pi OS with an SSD connected via the [Homerun Adapter 1](https://homerun.network/products/adapter-1.html) device. 

It would be nice to make this more generic to work on a variety of devices. Wouldn't want to make it too complex to use though. 

## Instructions

1. Download this file as `trim.sh`
2. Plug everything in (ssd, adapter, pi)
3. Boot Raspberry Pi OS
4. Open terminal and execute `chmod +x trim.sh`
5. Now run `sudo trim.sh`

## Troubleshooting tips
This isn't super well tested, so if it doesn't work for you, I recommend you just follow [these steps](https://www.jeffgeerling.com/blog/2020/enabling-trim-on-external-ssd-on-raspberry-pi) yourself. This script is based on those instructions but could have some mistakes.


