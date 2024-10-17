# Projeto Blink com Arduino


## Parte 1:

### Código no Arduino - Blink SOS

<div align="center">
<sub>Figura 1 — Codigo <a href="#c6"></a></sub> </br>
<img src="Stuff\ArduinoCodigo.png"><br>
</div><br>

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

<div align="center">
<sub>Figura 2 — Conectado <a href="#c6"></a></sub> </br>
<img src="Stuff\ArduinoProvaDeConec.gif"><br>
</div><br>

#### GIF 2 - LED SOS

<div align="center">
<sub>Figura 3 — LED SOS <a href="#c6"></a></sub> </br>
<img src="Stuff\ArduinoBlink.gif"><br>
</div><br>

## Parte 2:

#### Tinkercad LED:

https://www.tinkercad.com/things/g7UzLWMLHPT/editel?sharecode=Z_hGcwTE1IkRkq3N6PnkrC91PSOE7MZ6lG5RG3Bglmw