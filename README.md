# rpi-bitcoin-ticker
Raspberry Pi I²C LCD Bitcoin Ticker

![](https://github.com/vmavromatis/rpi-bitcoin-tracker/raw/master/images/final.jpg)

# Requirements
```sudo pip install i2c_lcd```

# Add cron task
```sudo crontab -e```  
Next, append these 2 lines (replacing the path) to update the screen every 1 min:
```bash
* * * * *  /usr/bin/python /path/to/btclcd.py
@reboot    /usr/bin/python /path/to/btclcd.py
```
# Connection
Just connect the following 4 pins to your RPi:

<img src="https://github.com/vmavromatis/rpi-bitcoin-tracker/raw/master/images/i2c_lcd.jpg" width="300" height="400"><img src="https://github.com/vmavromatis/rpi-bitcoin-tracker/raw/master/images/rpi.png" width="400" height="200">


# Donate
If you aprreciate this little project feel free to buy me a coffee! :)  
144baBdC8VLajpFipmaZQughzAgLFQZfjD  
<img src="https://github.com/vmavromatis/rpi-bitcoin-tracker/raw/master/images/qr.png" width="100" height="100">
