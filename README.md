# waterrat
water consumptie logging bij oostc

# wat heb ik gedaan
install raspberry pi
 > hoostnaam : waterrat
 > pwd : waar 123
ssh waterrat -l pi


install RS485
 https://www.waveshare.com/w/upload/2/29/RS485-CAN-HAT-user-manuakl-en.pdf


You will see the following:
Timestamp: 1527240783.548918        ID: 0123    S          DLC: 8    00 01 02 03 04 05 06 07


INSTALL  SAMBA
https://magpi.raspberrypi.com/articles/samba-file-server
> sudo apt-get update
> sudo apt-get upgrade
> sudo apt-get install samba samba-common-bin
> sudo mkdir -m 1777 share

--> edit samba confit
--> run /etc/init.d/samba_ac_dc restart


