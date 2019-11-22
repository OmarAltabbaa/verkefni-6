int sensorValue = 0;
void setup()
{
  pinMode(A0, INPUT);
  pinMode(13, OUTPUT);
}
void loop()
{
  // read the value from the sensor
  sensorValue = analogRead(A0);
  // turn the LED on
  digitalWrite(13, HIGH);
  // pause the program for <sensorValue> millseconds
  delay(sensorValue); // Wait for sensorValue millisecond(s)
  // turn the LED off
  digitalWrite(13, LOW);
  // pause the program for <sensorValue> millseconds
  delay(sensorValue); // Wait for sensorValue millisecond(s)
}
