# pulse-audio-share

https://superuser.com/questions/605445/how-to-stream-my-gnu-linux-audio-output-to-android-devices-over-wi-fi

pactl list | grep "Monitor Source" 

chmod 755 pashare
./pashare start
netstat -nlt | grep 8000 
telnet 127.0.0.1 8000
