# Dark_Web_Crawler
Program to scrape websites in the dark web

Use the following to install the tor service and use it:
1.  sudo apt install tor
2.  sudo vi /etc/tor/torrc (you can use vi but i prefer to use nano - a more basic text editor)
3.  find "#ControlPort 9051" and uncomment it
4.  find "#CookieAuthentication 1" and uncomment it, also change the 1 to a 0
5.  restart the tor service using this command sudo /etc/init.d/tor restart


Use this command to run the program

torify python3 crawl.py 'link'        or      torify ./crawl.py 'link'
