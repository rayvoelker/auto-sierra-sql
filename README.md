# auto-sierra-sql

## overview
This is an example of creating an automation for a query into the sierra database using the sierra sql feature.

## install instructions
* install python3 and pip3 from your distribution's package manager ```sudo apt-get install python3 python3-pip3```
* install virtualenv from pip3 ```sudo pip3 install virtualenv --upgrade```
* clone this repo ```git clone https://github.com/rayvoelker/auto-sierra-sql.git```
* move to the repo dir ```cd sierra_barcode_api/```
* create the virtualenv ```virtualenv env```
* enable virtualenv ```source env/bin/activate```
* install the required python dependencies ```pip install -r requirements.txt```
* configure the variables in the ```claims_returned.ini``` file ```mv claims_returned.ini.sample claims_returned.ini``` ```nano claims_returned.ini```
* configure the SMTP server settings for your institution in ```_send_plch_email.py```
* run the code! ```python claims_returned.py```
