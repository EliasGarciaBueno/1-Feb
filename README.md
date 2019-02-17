# 1-Feb
int verde = 13;
int amarillo = 7;
int rojo = 2;
int on = 100;
int off = 800;

void setup() {
  // put your setup code here, to run once:
pinMode(verde,OUTPUT);
pinMode(amarillo,OUTPUT);
pinMode(rojo,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(verde,HIGH);
delay (on);
digitalWrite(verde,LOW);
delay (off);
digitalWrite(amarillo,HIGH);
delay (on);
digitalWrite(amarillo,LOW);
delay (off);
digitalWrite(rojo,HIGH);
delay (on);
digitalWrite(rojo,LOW);
delay (off);

}
