# OK1012A_LS1012A_EC20
LS1012A / OK1012A EC20  GSM modem


Forlinx OK1012A, official image of ubuntu 

18.
# in progress
The offical kernal comes with EC20 driver.
<br>
![pic](pic/ls1012_a.png)<br>
<br>

need to add a file
/et/udhcpc/default.script
<br>
![pic](pic/udhcpc_ls1012.png)<br>
<br>

Run quectel-CM V1.6.3.2
<br>
![pic](pic/ls1012c.png)<br>
<br>
force change DNS for ping<br>
echo "nameserver 8.8.8.8" > /etc/resolv.conf<br>
<br>
![pic](pic/ls1012_e.png)<br>
<br>
