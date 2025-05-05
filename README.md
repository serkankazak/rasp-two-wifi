### How to setup two wifi on raspberry pi?

```
nmcli connection show

sudo nmcli connection clone <ID_OF_OLD_CONFIGURATION> new_conf

sudo nmcli connection edit new_conf

	set 802-11-wireless.ssid <SECOND_SSID>
	set 802-11-wireless-security.psk <PASSWORD>
	save persistent
	quit
```

https://www.youtube.com/watch?v=49LSgdXCdEM

[![demo](http://img.youtube.com/vi/49LSgdXCdEM/0.jpg)](http://www.youtube.com/watch?v=49LSgdXCdEM "demo")
