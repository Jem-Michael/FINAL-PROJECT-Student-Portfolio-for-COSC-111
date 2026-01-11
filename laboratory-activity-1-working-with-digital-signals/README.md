# Laboratory Activity #1
## Working with Digital Signals

### Course
COSC 111 – Internet of Things

### Objective
The objective of this laboratory activity is to understand and work with basic digital signals and their behavior in digital systems.

### Description
In this activity, we explored how digital signals operate, including binary states, signal transitions, and basic digital logic concepts. The activity helped reinforce fundamental ideas used in digital electronics and IoT systems.

### Tools / Technologies Used
- (Example: Arduino)
- (Example: Breadboard)
- (Example: Digital simulation tools)

### Output

int delayTime = 1000;

void setup() {
 
  pinMode(12, OUTPUT);
  pinMode(11, OUTPUT);
  pinMode(10, OUTPUT);
  pinMode(9, OUTPUT);
  pinMode(8, OUTPUT);
}

void loop() {
  // Turn ON LEDs one by one
  digitalWrite(12, HIGH);
  delay(delayTime);
  digitalWrite(11, HIGH);
  delay(delayTime);
  digitalWrite(10, HIGH);
  delay(delayTime);
  digitalWrite(9, HIGH);
  delay(delayTime);
  digitalWrite(8, HIGH);
  delay(delayTime);

  // Turn OFF LEDs one by one
  digitalWrite(12, LOW);
  delay(delayTime);
  digitalWrite(11, LOW);
  delay(delayTime);
  digitalWrite(10, LOW);
  delay(delayTime);
  digitalWrite(9, LOW);
  delay(delayTime);
  digitalWrite(8, LOW);
  delay(delayTime);
}




### Author
Your Name
