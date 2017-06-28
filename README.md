Table of contents
=================

  * [Table of contents](#table-of-contents)
  * [Screenshots](#screenshots)
  * [Installation](#installation)
  * [Tutorial](#tutorial)
  * [Credits](#credits)
    
Screenshots
===========
![](https://github.com/ktenman/flashcards/blob/master/screenshots/687474703a2f2f733030392e726164696b616c2e72752f693330392f313730312f66642f3664393231356536613237662e706e67.png?raw=true)![](http://s018.radikal.ru/i507/1701/0d/30c53c9b970e.png)
![](http://s015.radikal.ru/i330/1701/fd/9a485e5426be.png)
![](http://s020.radikal.ru/i721/1701/0b/1b13dba6c3e9.png)
![](http://s61.radikal.ru/i174/1701/6e/966a38d713fa.png)
![](http://s020.radikal.ru/i720/1701/52/871a34544d02.png)
![](http://s015.radikal.ru/i330/1701/fd/9a485e5426be.png)

Installation
============

## 1. easy install docker
-------------------
```
#!/bin/sh
set -e
# This script is meant for quick & easy install via:
sudo apt-get update
curl -sSL https://get.docker.com/ | sh
sudo apt-get install git
git clone https://github.com/ktenman/flashcards.git
cd flashcards
sh start.sh


```
https://docs.docker.com/engine/installation/
```
username: admin
password: default
```

## 2. custom password
---------------------
create config.txt
```
SECRET_KEY='O5$&2L36sVWNswHL5WoD&17Y-your-strong-secret-key-ej5!5NC5OmYaYF@B49Y645Di'
USERNAME='your-username'
PASSWORD='your-password'
```
## 3. run
--------
execute command
```
sh start.sh
```
## 4. open
---------
Sign in with your username and password.
[http://localhost](http://localhost)

Tutorial
========
Use buttons on keyboard:
* Next card: <kbd>Space</kbd> or <kbd>&rarr;</kbd> or <kbd>F5</kbd>
* Flip card: <kbd>Enter</kbd> or <kbd>	&#x2191;</kbd> or <kbd>&#x2193;</kbd>
* Known card: <kbd>S</kbd> or <kbd>M</kbd> or <kbd>K</kbd>

Credits
=======
A huge thanks goes out to all the contributors!

Peeter Normak, Alari Alev, Alex Neil, Kerttu Tihti, Elinda Tragel, John Washam


