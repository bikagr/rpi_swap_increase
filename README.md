# rpi_swap_increase

Stop Swap
> sudo dphys-swapfile swapoff

Open Swap File
> sudo nano /etc/dphys-swapfile

Replace value of swap
```
CONF_SWAPSIZE=1024
```

Enable Swap
> sudo dphys-swapfile swapon

Recreate Swap file (if dont want to restart)
> sudo dphys-swapfile setup

Restart Pi
> sudo reboot
