reverseip
=========

reverseip.py - Reverse IP lookup - Find domains on the same server

Usage: reverseip.py [options]

Options:  

  -h, --help                  - show this help message and exit  
  -t TARGET, --target=TARGET  - Domain or IP to reverse IP lookup  
  -p PROXY, --proxy=PROXY     - HTTPS proxy to use  
  -a AGENT, --agent=AGENT     - Custom User Agent  

Examples:  

reverseip.py --target domain.com  
reverseip.py --target domain.com --proxy 192.168.0.1:8080  
reverseip.py --target domain.com --agent "Googlebot/2.1 (+http://www.googlebot.com/bot.html)"  
                        


Screenshot:

http://i.imgur.com/Z8b6VLs.png
