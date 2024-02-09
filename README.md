# "Drink Water" Reminder
This program will remind you for drinking water after a particular interval of time (you can set it in program) using OS's notification system.

# Requirements
First we need pyler module which will help us to use os's notification system
```
pip install plyer
```
( repository: https://github.com/kivy/plyer ) &  
  
Secondly we need **time** module, which is inbuilt with python.

# Project Codes
```python
import time
from plyer import notification

if __name__ == "__main__":
    while True:
        notification.notify(title='Drink Water Now!!!', message='Your body is composed of about 60% water. The functions of these bodily fluids include digestion, absorption, circulation, creation of saliva, transportation of nutrients, and maintenance of body temperature.',  app_icon="your_notification_icon_image.ico", timeout=8)
        time.sleep(60*60)
```
Yes, that's it.  
Modify the notification according to your need & enjoy !!!
