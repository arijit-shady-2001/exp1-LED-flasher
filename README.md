# exp1-LED-flasher
Two LEDs connected will switch on for a second and switch for a second

void setup()
{
     pinmode(13, OUTPUT);
}
void loop()
{
     digitalWrite(13, HIGH);
     delay(1000);
     digitalWrite(13, LOW);
     delay(1000);
}
