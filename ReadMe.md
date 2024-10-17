# Projeto Blink com Arduino


## Parte 1:

### Código no Arduino - Blink SOS
![](Stuff\ArduinoCodigo.png)

```
const int Led = 13;

void setup() {
pinMode (Led, OUTPUT);

}

void loop() {
digitalWrite (Led, HIGH);
delay(200);
digitalWrite (Led, LOW);
delay(100);
digitalWrite (Led, HIGH);
delay(200);
digitalWrite (Led, LOW);
delay(100);
digitalWrite (Led, HIGH);
delay(200);
digitalWrite (Led, LOW);
delay(100);


digitalWrite (Led, HIGH);
delay(1000);
digitalWrite (Led, LOW);
delay(100);
digitalWrite (Led, HIGH);
delay(1000);
digitalWrite (Led, LOW);
delay(100);
digitalWrite (Led, HIGH);
delay(1000);
digitalWrite (Led, LOW);
delay(100);
}

```

### Arduino
#### GIF 1 - Conectado
![](Stuff\ArduinoProvaDeConec.gif)

#### GIF 2 - LED SOS
![](Stuff\ArduinoBlink.gif)

