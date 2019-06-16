# How to change the wireless mode

---

1- `ifconfig wlan0 down` to disable wireless adapter
<br>
2- `airmon-ng check kill` kills the network manager
<br>
3- `iwconfig wlan0 mode "mode"` to change wireless mode
1- `ifconfig wlan0 up` to enable wireless adapter
<br>