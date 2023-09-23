from https://rentry.co/o3c#factory-reset

this will work [web version](https://sayodevice.com) on linux

```shell
sudo wget -P /etc/udev/rules.d https://raw.githubusercontent.com/NyanArchive/Sayodevice_Drivers/main/udev/98-saybot.rules
sudo udevadm control --reload-rules
# reboot system, probably.
```

automatically fetches file using github actions

filename might be changed


