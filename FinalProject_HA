int led1 = 2; // led for 5 mins or less
int led2 = 3; // led for 5-10 mins
int led3 = 4; // led for 10-15 mins
int led4 = 5; // led for 15-20 mins
int led5 = 6; // led for more than 20 mins

int emailApp = 7; // set digital pin 9 to email stats
int textApp = 8; // set digital pin 10 to text stats = 12
int instagramApp = 9; // set digital pin 8 to instagram stats = 8.5
int snapchatApp = 10; // set digital pin 11 to twitter stats = 17.1
int facebookApp = 11; // set digital pin 12 to facebook = 27
int twitterApp = 12; // set digital pin 13 to twitter
int netflixApp = A0; // set analog 0 pin to snapchat = 17 
int linkedinApp = 13; // set analog 1 pin to youtube = 9.58
int youtubeApp = A1; // set analog 2 pin to linkedin 9.8
//int gameApp = A3; // set analog 4 pin to game

// read the digital pin state, conversion for serial print
int instaState;
int emailState;
int textState;
int twitterState;
int facebookState;
int snapchatState;
int youtubeState;
int linkedinState;
int netflixState;

void setup() {
  // set up LEDs for OUTPUT
  pinMode(2, OUTPUT);
  pinMode(3, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(4, OUTPUT);
  pinMode(5, OUTPUT);
  pinMode(6, OUTPUT);
  
  // set up remaining pins for input
  pinMode(8, INPUT);
  pinMode(9, INPUT);
  pinMode(10, INPUT);
  pinMode(11, INPUT);
  pinMode(12, INPUT);
  pinMode(13, INPUT);
  pinMode(A0, INPUT);
  pinMode(A1, INPUT);
  pinMode(A2, INPUT);
  pinMode(A3, INPUT);
  
  // begin serial communication
  Serial.begin(9600);
}

void loop() {
// set up for digital read in serial for debugging
instaState = digitalRead(instagramApp);
emailState = digitalRead(emailApp);
textState = digitalRead(textApp);
twitterState = digitalRead(twitterApp);
facebookState = digitalRead(facebookApp); 
snapchatState = digitalRead(snapchatApp);
youtubeState = analogRead(youtubeApp);
linkedinState = digitalRead(linkedinApp);
netflixState = analogRead(netflixApp);

//Serial.print("Email ");
//Serial.println(emailState);
//delay(100);
//Serial.print("Text ");
//Serial.println(textState);
//delay(100);
//Serial.print("Instagram ");Serial.println(instaState);
//delay(100);
//Serial.print("snapchatState ");
//Serial.println(snapchatState);
//delay(100);
//Serial.print("Facebook ");
//Serial.println(facebookState);
//delay(100);
//Serial.print("Twitter ");
//Serial.println(twitterState);
//delay(100);
//Serial.print("Netflix ");
//Serial.println(netflixState);
//delay(100);
//Serial.print("LinkedIn ");
//Serial.println(linkedinState);
//delay(100);
//Serial.print("Games ");
//Serial.println(gameState);
//delay(100);

  if (emailState == HIGH) { // emailApp is on dig 7 
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (textState == HIGH) { // text is on dig 8
    digitalWrite(led1, HIGH);
    digitalWrite(led2,HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
   
  if (instaState == HIGH) { // instagram is on dig 9
    digitalWrite(led1, HIGH);
    digitalWrite(led2,HIGH);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (snapchatState == HIGH) { // snapchat is on dig 10
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, HIGH);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (facebookState == HIGH) { // facebook is on dig 11
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, HIGH);
    digitalWrite(led5, HIGH);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW); 
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (twitterState == HIGH) { // twitter is on dig 12
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, HIGH);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (netflixState > 1000) { // netflix is on A0
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, HIGH);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (linkedinState == HIGH) { // reminder - 13
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
  
  if (youtubeState > 1000) { // reminder - A2
    digitalWrite(led1, HIGH);
    digitalWrite(led2, HIGH);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
    delay(1000);
    digitalWrite(led1, LOW);
    digitalWrite(led2, LOW);
    digitalWrite(led3, LOW);
    digitalWrite(led4, LOW);
    digitalWrite(led5, LOW);
  }
 
}
