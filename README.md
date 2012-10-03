adhoc is a command tool to make your wireless device as an Access Point,  
other device such as PC or Notebook can connect network through your wireless device.  

first you use adhoc, you must install dnsmasq following:  
  $ sudo apt-get install dnsmasq  
and kill dnsmasq server process after install it:  
  $ pkill -f dnsmasq  

then, run command to start following:  
  $ sudo ./adhoc wlan0 essid YourNetworkName key YourNetworkAccessPassword start  
stop or restart your network, you can run command:  
  $ sudo ./adhoc wlan0 stop  
  or  
  $ sudo ./adhoc wlan0 restart  

of course, you can use adhoc as a system command,  
just mv it to /usr/bin or /usr/local/bin:  
  $ sudo mv adhoc /usr/bin  
  or  
  $ sudo mv adhoc /usr/local/bin  
