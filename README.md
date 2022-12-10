# Airprint_on_Ubuntu22.04
https://linuxhint.com/set-up-cups-printer-server-ubuntu-22-04/



```
sudo apt install cups
sudo systemctl start cups
sudo systemctl enable cups
sudo systemctl status cups
```

sudo cp -Rf cupsd.conf /etc/cups/cupsd.conf

sudo systemctl restart cups



