# LED ON/OFF with external LED

------


![blinkingLightGIF](https://github.com/ritikansh/IOT/assets/86471518/0dff11a8-91a7-4c05-9290-3ef2cc44b9ba)

------

[Start Simulation](https://www.tinkercad.com/things/6VxhXHXtKos)

```c++

void setup()
{
  pinMode(8, OUTPUT);
}

void loop()
{
  digitalWrite(8, HIGH);
  delay(1000); 
  digitalWrite(8, LOW);
  delay(1000);
}
```
