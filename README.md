wpa2-peap-ca
============

WPA2-PEAP template for Wicd, which includes CA Certificate.

To use this template in your computer, download the file wpa2-peap-ca 
and put it in /etc/wicd/encryption/templates/, then edit file 
/etc/wicd/encryption/templates/active and insert "wpa2-peap-ca" 
(without quotation marks).
Now you need to delete file /var/run/wicd/wicd.pid and restart wicd 
deamon with this command: sudo wicd restart.
You can see the new encryption template in Wicd's GUI.
