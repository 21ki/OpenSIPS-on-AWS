# OpenSIPS-on-AWS

![Alt text](http://www.icalleasy.com/images/opensips-aws.png "OpenSIPS on AMAZON EC2") 

#Licensing Information: READ LICENSE

#Project source can be downloaded from
##https://github.com/chanon-m/opensips-on-aws.git

#Author & Contributor

Chanon Mingsuwan

Reported bugs or requested new feature can be sent to chanonm@live.com

#How to run a file
* Install OpenSIPS and RTPProxy

* Download files to your server

```

# git clone https://github.com/chanon-m/opensips-on-aws.git

```

* Make a file executable and install opensips.cfg

```

# cd ./opensips-on-aws
# chmod 755 install.sh
# ./install.sh

```

* Start RTPProxy and OpenSIPS

##Testing

#### SIP Phone Configuration
  * User ID = 16265947887
  * Domain = 52.8.42.41
  * Password = 818885566
  * Authorization name = 16265947887
 
#### Dial Plan
  * USA = 1-XXX-XXX-XXXX 
  * Voicemail = 500
