int led = 3;
int sespin = 2;
void setup() {
  pinMode(led, OUTPUT);
  pinMode(sespin, INPUT);
  

}

void loop() {
  int sesdegeri =digitalRead(sespin);

  if (sesdegeri == HIGH)
  {
    digitalWrite(led, HIGH);
  }
  else {
    digitalWrite(led, LOW);
  }
  
}
