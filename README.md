# ghost-dog-2
// Timejam
// Timejam is a 433MHz Jammer Remotely Controlled with an adjustable Time for executing a Rolljam with the Hackrf Portapack
// Jammer construction 5x433MHz Transmitter modules GND to GND , 5v joined to signal pin
// connect to Digispark output pin , 5v is connected to GPIO 53 Arduino Mega output, Input GPIO 51 from 433MHz Receiver Module

// DigisparkjammerTimer
// Code

void setup() {
pinMode(1, OUTPUT);
digitalWrite(1, HIGH);
delay (30000);
digitalWrite(1, LOW);
}
void loop () {
}
