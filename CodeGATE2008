#include <Arduino.h>

int Y,a,b,d;
void setup() { 
    pinMode(3, INPUT);
    pinMode(4, INPUT);
    pinMode(5, INPUT);
    pinMode(6, OUTPUT);
}
void loop() {
  a = digitalRead(3);
  b = digitalRead(4);
  d = digitalRead(5);

  Y = (!a&&!d)||(!b&&!d);
digitalWrite(6,Y);

}
