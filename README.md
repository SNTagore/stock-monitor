# Stock-monitor

## About


Initial concept based on [this instructable](http://www.instructables.com/id/Transform-Raspberry-Pi-Into-a-Stock-Exchange-Monit/) and [this git repo](https://github.com/kal001/stocks) 

There will be changes made as I incoporate modifications to my tastes.

## Changes from the original fork


Changes include:
  - Readme
  - use of AlphaVantager instead of Yahoo

## Stock exchange suite for raspberry pi


These are Python scripts that allow you to **monitor stock markets**.
The scripts will save to an sqlite database the quotes of the stocks that you instruct him to periodically monitor.

Messages are **sent with Telegram**, when it is time to buy or sell a particular stock, based on a given
invesment strategy.

Requirements
------------

googlefinance
ystockquote
python-dateutil
pytz
requests
telepot

Version history
---------------


######SNTagore Version 0.0.4 - in production

Readme
Changing Yahoo to AlphaVantager

######Version 0.0.3

2016-06-12
Bugs correction

######Version 0.0.2 

2016-06-08
Initial publish version in github
