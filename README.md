# raspberry-pi-hassio


# setup
- Goto: https://www.home-assistant.io/hassio/installation
- Download image for correct Raspberry Pi model
- Use balenaEtcher to install image on micro SD card: https://www.balena.io/etcher/
> Read if installing by Wifi. If you are installing by LAN, skip this section.
> windows: create root/CONFIG/network/my-network file and edit it using this guide: https://github.com/home-assistant/hassos/blob/dev/Documentation/network.md
> mac: if your sd card is no longer readable by mac, try different software to mount the image on the micro SD card, otherwise connect via LAN.
- Boot Raspberry Pi with image
> If raspberry pi booted properly, you should be able to see the hassio welcome screen. It may take a bit for the pi to boot and connect. This may take up to 15 mins.
- From any machine on network, see the welcome page: http://hassio.local:8123/
