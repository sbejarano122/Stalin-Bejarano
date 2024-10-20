int led1 = 12;
int led2 = 8;
int led3 = 4;
int pulsador = 2;

void setup()
{
  pinMode(pulsador, INPUT);
  pinMode(led1, OUTPUT);
  pinMode(led2, OUTPUT);
  pinMode(led3, OUTPUT);
}

void loop()
{
  if (digitalRead(pulsador) == HIGH)
  {
    digitalWrite(led1, HIGH);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    delay(4000);
    digitalWrite(led1, LOW);

    digitalWrite(led2, HIGH);
    digitalWrite(led1, LOW);
    digitalWrite(led3, LOW);
    delay(2000);
    digitalWrite(led2, LOW);

    digitalWrite(led3, HIGH);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    delay(5000);
    digitalWrite(led3, LOW);
  }
}
