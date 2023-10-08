# LED ON/OFF with BUILTIN_LED


![Tinkercad GIF](https://github.com/ritikansh/IOT/assets/86471518/acaaf7f3-06bf-45af-8ada-c5a2ad0d2eee)
```c++
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1 sec
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000);
}
```
