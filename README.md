![photo_2021-04-17_08-39-17](https://user-images.githubusercontent.com/80913347/115100297-4e548600-9f59-11eb-8f78-9ee64e76b5f5.jpg)

#include <LiquidCrystal.h>
int rs=7;
int en=8;
int d4=9;
int d5=10;
int d6=11;
int d7=12;
LiquidCrystal lcd(rs,en,d4,d5,d6,d6,d7);
void setup(){
lcd.begin(16,2);
}
  // put your setup code here, to run once:



void loop() {
lcd.setCursor(0,1);
lcd.print("gyni");

}
