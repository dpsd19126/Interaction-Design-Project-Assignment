# Lesson: Interaction Design

### First and Last Name: Karyotis Konstantinos, Alexandros Sotidis
### University Registration Number: dpsd19049, dpsd19126 
### GitHub Personal Profile: https://github.com/dpsd19049, https://github.com/dpsd19126

# Introduction
Interactive-Art
# Summary
Design Brief:


Στόχος μας είναι να σχεδιάσουμε ένα διαδραστικό σύστημα αναπαραγωγής ήχου με δυνατότητα αυξομείωσης της έντασης,επιλογής ταχύτητας αναπαραγωγής καθώς  και αυξομείωση της έντασης φωτεινής πηγής κατά της διάρκεια που ο χρηστής θα αναπαράγει/ακούει μουσική ώστε η διαδικασία να γίνει πιο ευχάριστη.Η δραστηριότητα θα λαμβάνει χώρο στο οικιακό περιβάλλον του χρηστή(σαλόνι/υπνοδωμάτιο).Ο χρόνος λειτουργιάς αντιστοιχεί ανάλογα την διάρκεια του κάθε τραγουδιού.


# 1st Deliverable

Target group:
	Οι χρηστές μας είναι άνθρωποι της ηλιακής ομάδας 1996-2010(gen-z) οι οποίοι έχουμε παρατηρήσει ότι περνάνε ένα μεγάλο μέρος της μέρας τους ακούγοντας μουσική.
  Φύλο:Αγόρια /Κορίτσια
	Ηλικια:12-25ετων	
	Χώρα :Ελλάδα

Activities 
	Ο χρηστής βρίσκεται στο οικιακό του χώρο και πιο συγκεκριμένα στο σαλόνι του και χαλαρώνει. 
	Επιλεγεί το είδος μουσικής που θέλει να ακούσει.
	Απολαμβάνει την μελώδια της μουσικής.

Context
	Physical: Οικιακό περιβάλλον 
	Social: Ατομική δραστηριότητα 
	Organizational:Δεν επηρεάζει οργανωσιακά τον χρηστή.


Τechnologies: 
	Input:Πάτημα κουμπιών
	Output:Φωτεινές ενδείξεις με εναλαγή εντασης,ηχος
	Communication: οπτικοαουστικά 
	Content: Arduino Uno,  Resistor,breadboard,Buzzer,LED,Potentiometer



# 2nd Deliverable
*Information architecture*


![image](https://user-images.githubusercontent.com/100956044/167307330-6e792521-4f9f-4073-b716-3a79a0834279.png)




*User Interaction*

User->Sound maker->Arduino->Light


Το τεχνούργημα μας έχει ψυχαγωγικό χαρακτήρα.Ο χρηστής εισέρχεται στο χώρο που είναι τοποθετημένο το αντικείμενο, πιθανόν στο σαλόνι του.Επιλέγεται κάποιο τραγούδι,το σύστημα αναπαράγει τον ήχο  και ανάλογα με την ένταση εφαρμόζει την αντίστοιχη ένταση στα φωτά led.Ο χρηστής παράλληλα μπορεί εάν επιθυμεί να αυξομειώσει την ένταση της μουσικής η να αλλάξει την ταχύτητα αναπαραγωγή της.Τέλος υπάρχει η δυνατότητα διακοπής της μουσικής όταν επικρατούν καταστάσεις νυκτός.


*Interface design*


Hardware Required

1       Arduino Uno	

2	Breadboard (generic)

3      Buzzer

4     Photo resistor  

5     LED (generic)  

6      Single Turn Potentiometer- 10k ohms

7     SparkFun Pushbutton switch 12mm

8     2*  Resistor 10k ohm

9    2*	Resistor 560 ohm

10    12*  Jumper wires (generic)



	
	

Software:Javascript,c++



# 3rd Deliverable 


SCENARIO



Ο Μπάμπης μετά από μια σκληρή μέρα στη δουλειά γυρνάει στο σπίτι του εξουθενομένος. Κάθεται στο σαλόνι του για μερικά λεπτά στον καναπέ του στο σαλόνι. Δίπλα στο τραπεζάκι του υπάρχει η συσκευή με την οποία ακούει μουσική. Για να ξεκινήσει να παίζει πρέπει να υπάρχει φως. Ανοίγει το φως και ξεκινά να παίζει το αγαπημένο του κομμάτι. Ο Μπάμπης τώρα χαλαρώνει και ταυτόχρονα ακούει την μουσική του.





STORYBOARD




![storyboard](https://user-images.githubusercontent.com/100956044/172960634-35bbe153-cb4c-469e-8840-0d1d3e5ffdd1.jpg)



PROTOTYPE




![20220610_020825](https://user-images.githubusercontent.com/100956044/172960802-c643d26e-886b-45a7-a24c-56328a2de950.jpg)




![Στιγμιότυπο οθόνης (164)](https://user-images.githubusercontent.com/100956044/172961049-c22775e9-933b-4104-8a34-6f6f4f7df94d.png)



CODE

#define  a3f    208     // 208 Hz
#define  b3f    233     // 233 Hz
#define  b3     247     // 247 Hz
#define  c4     261     // 261 Hz MIDDLE C
#define  c4s    277     // 277 Hz
#define  e4f    311     // 311 Hz    
#define  f4     349     // 349 Hz 
#define  a4f    415     // 415 Hz  
#define  b4f    466     // 466 Hz 
#define  b4     493     // 493 Hz 
#define  c5     523     // 523 Hz 
#define  c5s    554     // 554 Hz
#define  e5f    622     // 622 Hz  
#define  f5     698     // 698 Hz 
#define  f5s    740     // 740 Hz
#define  a5f    831     // 831 Hz 

#define rest    -1

int piezo = 7;
int led = 9;
int button = 2;
int sensor = A0;

volatile int beatlength = 100; // determines tempo
float beatseparationconstant = 0.3;

int threshold;

int a; // part index
int b; // song index
int c; // lyric index

boolean flag;

// Parts 1 and 2 (Intro)

int song1_intro_melody[] =
{c5s, e5f, e5f, f5, a5f, f5s, f5, e5f, c5s, e5f, rest, a4f, a4f};

int song1_intro_rhythmn[] =
{6, 10, 6, 6, 1, 1, 1, 1, 6, 10, 4, 2, 10};

// Parts 3 or 5 (Verse 1)

int song1_verse1_melody[] =
{ rest, c4s, c4s, c4s, c4s, e4f, rest, c4, b3f, a3f,
  rest, b3f, b3f, c4, c4s, a3f, a4f, a4f, e4f,
  rest, b3f, b3f, c4, c4s, b3f, c4s, e4f, rest, c4, b3f, b3f, a3f,
  rest, b3f, b3f, c4, c4s, a3f, a3f, e4f, e4f, e4f, f4, e4f,
  c4s, e4f, f4, c4s, e4f, e4f, e4f, f4, e4f, a3f,
  rest, b3f, c4, c4s, a3f, rest, e4f, f4, e4f
};

int song1_verse1_rhythmn[] =
{ 2, 1, 1, 1, 1, 2, 1, 1, 1, 5,
  1, 1, 1, 1, 3, 1, 2, 1, 5,
  1, 1, 1, 1, 1, 1, 1, 2, 1, 1, 1, 1, 3,
  1, 1, 1, 1, 2, 1, 1, 1, 1, 1, 1, 4,
  5, 1, 1, 1, 1, 1, 1, 1, 2, 2,
  2, 1, 1, 1, 3, 1, 1, 1, 3
};

char* lyrics_verse1[] =
{ "We're ", "no ", "strangers ", "", "to ", "love ", "", "\r\n",
  "You ", "know ", "the ", "rules ", "and ", "so ", "do ", "I\r\n",
  "A ", "full ", "commitment's ", "", "", "what ", "I'm ", "thinking ", "", "of", "\r\n",
  "You ", "wouldn't ", "", "get ", "this ", "from ", "any ", "", "other ", "", "guy\r\n",
  "I ", "just ", "wanna ", "", "tell ", "you ", "how ", "I'm ", "feeling", "\r\n",
  "Gotta ", "", "make ", "you ", "understand", "", "\r\n"
};

// Parts 4 or 6 (Chorus)

int song1_chorus_melody[] =
{ b4f, b4f, a4f, a4f,
  f5, f5, e5f, b4f, b4f, a4f, a4f, e5f, e5f, c5s, c5, b4f,
  c5s, c5s, c5s, c5s,
  c5s, e5f, c5, b4f, a4f, a4f, a4f, e5f, c5s,
  b4f, b4f, a4f, a4f,
  f5, f5, e5f, b4f, b4f, a4f, a4f, a5f, c5, c5s, c5, b4f,
  c5s, c5s, c5s, c5s,
  c5s, e5f, c5, b4f, a4f, rest, a4f, e5f, c5s, rest
};

int song1_chorus_rhythmn[] =
{ 1, 1, 1, 1,
  3, 3, 6, 1, 1, 1, 1, 3, 3, 3, 1, 2,
  1, 1, 1, 1,
  3, 3, 3, 1, 2, 2, 2, 4, 8,
  1, 1, 1, 1,
  3, 3, 6, 1, 1, 1, 1, 3, 3, 3, 1, 2,
  1, 1, 1, 1,
  3, 3, 3, 1, 2, 2, 2, 4, 8, 4
};

char* lyrics_chorus[] =
{ "Never ", "", "gonna ", "", "give ", "you ", "up\r\n",
  "Never ", "", "gonna ", "", "let ", "you ", "down", "", "\r\n",
  "Never ", "", "gonna ", "", "run ", "around ", "", "", "", "and ", "desert ", "", "you\r\n",
  "Never ", "", "gonna ", "", "make ", "you ", "cry\r\n",
  "Never ", "", "gonna ", "", "say ", "goodbye ", "", "", "\r\n",
  "Never ", "", "gonna ", "", "tell ", "a ", "lie ", "", "", "and ", "hurt ", "you\r\n"
};

void setup()
{
  pinMode(piezo, OUTPUT);
  pinMode(led, OUTPUT);
  pinMode(button, INPUT_PULLUP);
  pinMode(sensor, INPUT);
  attachInterrupt(digitalPinToInterrupt(button), getFaster, FALLING);
  digitalWrite(led, LOW);
  Serial.begin(9600);
  flag = false;
  a = 4;
  b = 0;
  c = 0;
  threshold = analogRead(sensor) + 250;
}

void loop()
{
  int sensorreading = analogRead(sensor);
  if (sensorreading < threshold) { // if bright, play
    flag = true;
  }
  else if (sensorreading > threshold) { // if dark, pause
    flag = false;
  }

  // play next step in song
  if (flag == true) {
    play();
  }
}

void play() {
  int notelength;
  if (a == 1 || a == 2) {
    // intro
    notelength = beatlength * song1_intro_rhythmn[b];
    if (song1_intro_melody[b] > 0) {
      digitalWrite(led, HIGH);
      tone(piezo, song1_intro_melody[b], notelength);
    }
    b++;
    if (b >= sizeof(song1_intro_melody) / sizeof(int)) {
      a++;
      b = 0;
      c = 0;
    }
  }
  else if (a == 3 || a == 5) {
    // verse
    notelength = beatlength * 2 * song1_verse1_rhythmn[b];
    if (song1_verse1_melody[b] > 0) {
      digitalWrite(led, HIGH);
      Serial.print(lyrics_verse1[c]);
      tone(piezo, song1_verse1_melody[b], notelength);
      c++;
    }
    b++;
    if (b >= sizeof(song1_verse1_melody) / sizeof(int)) {
      a++;
      b = 0;
      c = 0;
    }
  }
  else if (a == 4 || a == 6) {
    // chorus
    notelength = beatlength * song1_chorus_rhythmn[b];
    if (song1_chorus_melody[b] > 0) {
      digitalWrite(led, HIGH);
      Serial.print(lyrics_chorus[c]);
      tone(piezo, song1_chorus_melody[b], notelength);
      c++;
    }
    b++;
    if (b >= sizeof(song1_chorus_melody) / sizeof(int)) {
      Serial.println("");
      a++;
      b = 0;
      c = 0;
    }
  }
  delay(notelength);
  noTone(piezo);
  digitalWrite(led, LOW);
  delay(notelength * beatseparationconstant);
  if (a == 7) { // loop back around to beginning of song
    a = 1;
  }
}

void getFaster() { // decrease beat length in order to increase tempo
  beatlength = beatlength / 2;
  if (beatlength < 20) { // loop back to original tempo
    beatlength = 100;
  }
}



# Conclusions



# Sources
