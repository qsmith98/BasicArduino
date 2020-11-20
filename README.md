# BasicArduino
I'm going to learn how to use an Arduino, and make awesome things with it!


## TableofContents
* [TableOfContents](#TableOfContents)
* [HelloArduino](#HelloArduino)
* [FiniteLEDBlink](#FiniteLEDBlink)

## HelloArduino

### Description & Code

```C++
void setup() {

  pinMode(13, OUTPUT);      // Set pin 13 to output
  
Serial.begin(9600);

 Serial.println("Hello World");}


 

void loop() {

 
 digitalWrite(13, HIGH);   // Turn on the LED

 Serial.println("Blink");
 
  delay(2000);              // Wait for two seconds

  digitalWrite(13, LOW);    // Turn off the LED
  
  delay(2000
  );              // Wait for two seconds}

```

### Evidence
[Here is my code on Arduino Create] I dont know how to put my code from regular arduino on to here

### Image or Wiring
<img src="http://troybaverstock.com/wp-content/uploads/2019/04/arduino-servo-button-red-green-RGB-LED-wiring-diagram.png" width="300px" /> 

Image credit belongs to [Troy Baverstock](https://troybaverstock.com/learn/fritzing-circuit-diagrams/)

### Reflection
I learned that you have to put text inside the brackets of the void setup and also how to just basically code a blink

## FiniteLEDBlink

### Description & Code

```C++
int counter = 0;
int maxnum = 6;

void setup() {

  pinMode(13, OUTPUT);      // Set pin 13 to output
  
Serial.begin(9600);

}


 

void loop() {
   
    if (counter == 4){
       Serial.println(4);
    }if (counter == 3){
       Serial.println(3);
    }if (counter == 2){
       Serial.println(2);
    }if (counter == 1){
       Serial.println(1);
    }if (counter == 5){
      Serial.println(5);
    }
    if (counter < maxnum - 1 ){
 digitalWrite(13, HIGH);   // Turn on the LED
 
  delay(250);              // Wait for two seconds

  digitalWrite(13, LOW);    // Turn off the LED
  
  delay(250
  );              // Wait for two seconds
counter++;        // adds to the counter
     }
}

```

### Evidence
int counter = 0;
int maxnum = 6;

void setup() {

  pinMode(13, OUTPUT);      // Set pin 13 to output
  
Serial.begin(9600);

}


 

void loop() {
   
    if (counter == 4){
       Serial.println(4);
    }if (counter == 3){
       Serial.println(3);
    }if (counter == 2){
       Serial.println(2);
    }if (counter == 1){
       Serial.println(1);
    }if (counter == 5){
      Serial.println(5);
    }
    if (counter < maxnum - 1 ){
 digitalWrite(13, HIGH);   // Turn on the LED
 
  delay(250);              // Wait for two seconds

  digitalWrite(13, LOW);    // Turn off the LED
  
  delay(250
  );              // Wait for two seconds
counter++;        // adds to the counter
     }
}
### Image or Wiring

### Reflection
I learned that the code int++; changes the int that you assing during the setup. I also learned about if statements in code.
