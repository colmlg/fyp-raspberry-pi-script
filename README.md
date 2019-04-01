# fyp-raspberry-pi-script
This repository hosts the script used on the raspberry pi which acts as a bluetooth beacon for the lecture sign in system.  
The script accepts two 2-digit hexadecimal numbers as parameters.  
These values will be broadcast as the beacon 'Major' and 'Minor' values.

```
./advertise_beacon.sh 00 01
```

The hex value for the room numbers can be retrieved from the [backend](https://github.com/colmlg/sign-in-backend) endpoint `/rooms?hex=true`
