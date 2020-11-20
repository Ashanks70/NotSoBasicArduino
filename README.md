# NotSoBasicArduino
 The follwing files are my second foray into Arduino
 
 
## Table of Contents
* [Table of Contents](#TableOfContents)
* [Limited Blink](#Limited_Blink)
* [HelloFunctions](#HelloFunctions)
* [NewPing](#NewPing)
---

## Limited_Blink

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
 /*

*/
int times = 0;
void setup() {
  Serial.begin(9600);
  pinMode(12, OUTPUT);
}

void loop() {
  if (times < 5) {
    digitalWrite(10, HIGH);

    Serial.println(times);
    delay(250);
    digitalWrite(10, LOW);

    delay(250);
    times++;

  }
```
I limited the number of times by inserting a variable and limiting it based on the variable.

### Evidence
[Limited Blink on Arduino Create](https://create.arduino.cc/editor/aengineeringj/261c9003-b5b8-4bf9-befd-18bfec091bdd/preview)

### Images
!(LED)[LED.png]
### Reflection
This one was rather easy, I just had to remember some of the syntax.
## HelloFunctions

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

## NewPing

### Description & Code
Description goes here

Here's how you make code look like code:

```C++
Code goes here
```
Talk about how the code works, here....

### Evidence
link goes here

### Images
draw it yourself, take a picture, make a fritzing, whatever you want to EFFECTIVELY communicate how its put together.

### Reflection

