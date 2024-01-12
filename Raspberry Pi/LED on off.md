# LED ON / OFF Online Simulation 
Source Code
```python
import RPi.GPIO as GPIO
import time
GPIO.setmode(GPIO.BCM)
GPIO.setwarnings(False)
GPIO.setup(18,GPIO.OUT)
while True:
   GPIO.output(18,GPIO.HIGH)
   time.sleep(1)
   GPIO.output(18,GPIO.LOW)
   time.sleep(1)

```
## Gif 
![LED ON OFF Raspberry Pi](https://github.com/ritik712prasad/IOT/assets/86471518/1cac3954-9b6b-4990-b9d0-d3faf755919d)


