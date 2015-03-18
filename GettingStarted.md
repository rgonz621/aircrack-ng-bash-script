This will set up your system for the script.

# Introduction #
You must have Xterm, Kismet, Maccahnger and of course Aircrack-ng installed.

You then must set up Kismet to use the scripts scanning ability. To do this, navigate to
: /etc/kismet and (opening with root privileges) open kismet.config. Then, you must find the source line and change it to: source=bcm43xx,mon0,Wireless

Ok, you must then cd into your folder and type: sh "Aircrack-ng BASH Script.sh"


Thats it! Now just follow the on-screen instructions!