# Airprint_on_Ubuntu22.04

```
sudo apt install cups
```
```
sudo systemctl start cups
```
```
sudo systemctl enable cups
```
```
sudo systemctl status cups
```

```
sudo cp -Rf cupsd.conf /etc/cups/cupsd.conf
```
```
sudo systemctl restart cups
```

<br>

1. Firstly, open the “Settings“. Scroll down the left pane and choose “Printers” and you will find a green button “Add a Printer“.
<br>Once you click on the “Add a Printer” button, you will get the CUPS printer in the list. Select it and click on “Add” to add CUPS to the printers list.
<br>After doing so, it is observed that the CUPS will be added to your printer list and is ready to serve you .

2. Once the printer is added to the list, you can print any file using the CUPS printer server. Head over to the file you want to get printed. 
3. Then you can use printer on your ios.


<br>It's from:https://linuxhint.com/set-up-cups-printer-server-ubuntu-22-04/

