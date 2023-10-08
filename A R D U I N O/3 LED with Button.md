# LED ON/OFF with BUTTON
---
**Requirement-**
1.  Arduino board (e.g., Arduino Uno)
2. One LED (any color)
3. one Resistor (220-330 ohms)
4. one Pushbutton switch
5. jumper wires and Breadboard(optional)
---
### working GIF in tinkercad.com
![GIF](https://github.com/ritikansh/IOT/assets/86471518/df2aab31-e6aa-49d8-8939-f24162b43fed)
[simulate](https://www.tinkercad.com/things/hvCTCLuYGmJ?sharecode=2vp6eaMo865inPjn1cl93usag6lG09yP11w4iPRYzc4)
---
#### Code
```c++
//problem -- ON led, when button is on. otherwise OFF. 
int led=12;
int buttonPin=2;
void setup()
{
pinMode(led,OUTPUT);
pinMode(buttonPin,INPUT_PULLUP);
}

void loop()
{
  int buttonVal = digitalRead(buttonPin);//storing button input
  //now make a condition for led on off
  if(buttonVal == LOW)
  {
    digitalWrite(led, HIGH);//on led
  }
  else
  {
    digitalWrite(led, LOW);//off led
  }
  
}
```
