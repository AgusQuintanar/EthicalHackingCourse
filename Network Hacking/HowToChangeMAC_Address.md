# How to change MAC Address

---

1- `ifconfig wlan0 down1` to disable it.
<br>
2- `ifconfing wlan0 hw ether 00:nn:nn:nn:nn:nn` to change the mac adress in memory
<br>
3- `if config wlan0 up` to enable it.
