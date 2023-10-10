led 1

// C++ code
//

int tempo = 800;

void setup()
{
  pinMode(4,OUTPUT);
 
}

void loop()
{
  
  digitalWrite(4, HIGH);
  delay(tempo);
  
  digitalWrite(4, LOW);
  delay(tempo);
}

leds alternando 1 e 2

// C++ code
//

int tempo = 800;

void setup()
{
  pinMode(4,OUTPUT);
  pinMode(3,OUTPUT);
}

void loop()
{
  
  digitalWrite(4, HIGH);
  delay(tempo);
  
  digitalWrite(4, LOW);
  delay(tempo);
  
    
  digitalWrite(3, HIGH);
  delay(tempo);
  
  digitalWrite(3, LOW);
  delay(tempo);
}
