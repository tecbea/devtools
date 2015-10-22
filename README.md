
Developer Tools
===============

This page is for tips for great stuff on internet, usefull for developers.


Github
------
* [Markdown basics] (https://help.github.com/articles/markdown-basics/) -- `github markdown basics`
* [QGit] (http://linoxide.com/ubuntu-how-to/install-qgit-viewer-ubuntu-14-04/)
* [Got Proxy] (http://xmodulo.com/how-to-use-git-behind-proxy-on-ubuntu.html)

Github Commands
-------------
* git init -- `init a git server`
* git status -- `git status`
* git add . -- `stage a folder `
* git log -- `check git log`
* .gitignore -- `git ignore file`
* git branch 'mybranch' -- `git create a branch`
* git chekcout 'mybranch' -- `git swap to a branch`
* git chekcout master -- `git swap to master`
* git merge mybranch -- `git merge mybranch to master`
* git clone https://github.com/tecbea/devtools.git -- `git clone a git from a url repo`
* git push -- `puch changes to server, after stage and commit`
* git fetch -- `get changes from remote server`



Cassandra
---------
Cassandra is great to work when using a lot of writes.
Some tips on tunning and support.


* [Compaction](http://www.datastax.com/dev/blog/when-to-use-leveled-compaction) -- `When to Use Leveled Compaction`


Security
---------
* nmap -Pn <host> -- `display open ports on a host`

Wifi sniffer
---------
* sudo apt-get install kismet -- `ubuntu wifi sniffer`

* goto uau
sudo ifconfig wlan0 down
sudo iwconfig wlan0 mode monitor
iwconfig wlan0
sudo ifconfig wlan0 up
sudo tcpdump -i wlan0 -n -w file.cap

* back to normal
sudo ifconfig wlan0 down
sudo iwconfig wlan0 mode managed
sudo ifconfig wlan0 up
iwconfig wlan0


* sudo apt-get install wavemon -- `ubuntu wifi sniffer`
* watch -n 1 iwconfig wlan0 -- ``
* wavemon -i wlan0 -- ``



Java
----

Javascript libs
---------------
* [mapdata](http://code.highcharts.com/mapdata/) -- `highcharts maps`
* [leafletjs] (http://leafletjs.com/examples/geojson.html) -- ` maps, geojson`
* [visjs] (http://visjs.org/) -- Hierarchical Layout 
* [d3js wrapper] (http://c3js.org/) -- c3.js




