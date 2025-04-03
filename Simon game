# Microcontroller-code-
This repository showcases a dynamic implementation of the classic Simon Game, challenging players' memory and cognitive skills through progressively complex sequences. Developed with robust, modular code, it exemplifies interactive programming excellence. A perfect blend of entertainment and technical precision.
  Author -Basavaraj k chikki
// Defining LED'S Pins
const int BLUE_LED = 13;
const int GREEN_LED = 12;
const int RED_LED = 11;
const int YELLOW_LED = 10;

// Defining PUSHBUTTON'S Pins
const int BLUE_BUTTON = 9;
const int GREEN_BUTTON = 8;
const int RED_BUTTON = 7;
const int YELLOW_BUTTON = 6;

//Defining BUZZER
const int BUZZER = 3;

// Frequency of buzzer for different colours 
/* Green = 415 Hz
    Red = 310 Hz
    Yellow = 252 
    Blue = 209 Hz 
*/

//Defining frequency for different colours
const int GREEN_FREQ =415;
const int BLUE_FREQ =209;
const int RED_FREQ =310;
const int YELLOW_FREQ =252;

void setup() {
//Declaring LED Pins
pinMode(BLUE_LED,OUTPUT);
pinMode(RED_LED,OUTPUT);
pinMode(GREEN_LED,OUTPUT);
pinMode(YELLOW_LED,OUTPUT);

//Declaring PUSHBUTTON'S Pins
pinMode(BLUE_BUTTON,INPUT);
pinMode(GREEN_BUTTON,INPUT);
pinMode(RED_BUTTON,INPUT);
pinMode(YELLOW_BUTTON,INPUT);

//Declaring BUZZER
pinMode(BUZZER,OUTPUT);
}


void loop() {
  //Condition to switch on each led 
  if(!digitalRead(BLUE_BUTTON))
  {
    digitalWrite(BLUE_LED,HIGH);
    tone(BUZZER,GREEN_FREQ,6);         // Use tone function

  }
  else{
    digitalWrite(BLUE_LED,LOW);
  }
  if(!digitalRead(GREEN_BUTTON))
  {
    digitalWrite(GREEN_LED,HIGH);
    tone(BUZZER,BLUE_FREQ,6);          // Use tone function

  }
  else{
    digitalWrite(GREEN_LED,LOW);
  }
if(!digitalRead(RED_BUTTON))                   
  {
    digitalWrite(RED_LED,HIGH);
    tone(BUZZER,RED_FREQ,6);        // Use tone function

  }
  else{
    digitalWrite(RED_LED,LOW);
  }
  if(!digitalRead(YELLOW_BUTTON))
  {
    digitalWrite(YELLOW_LED,HIGH);
    tone(BUZZER,YELLOW_FREQ,6);        // Use tone function

  }
  else{
    digitalWrite(YELLOW_LED,LOW);
  }
}
