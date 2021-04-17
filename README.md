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
