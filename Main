int n = 50;
void setup() {
  size(300, 300);
}
//Setup
void draw() {
//For some reason I can't put the background here
} 
void mousePressed() {

  background(255,255,255);
  (new Balloon(mouseX,mouseY)).show();
  //creates ballom
  if (((mouseX-(n/2))<mouseX)&&((mouseX+(n/2))>mouseX)&&((mouseY-(n/2))<mouseY)&&((mouseY+(n/2)))>mouseY) {
    n += 1;
   //if click is in right place, grow balloon. I can't figure out how to keep the color the same.
  }
  if (((mouseX-(n/2))<=0)||((mouseX+(n/2))>=300)||((mouseY-(n/2))<=0)||((mouseY+(n/2))>=300)) {
    System.out.println("POP");
    n = 50;
    clear();
    // if the ballon hits the edge, pop it
}}


class Balloon {
  int myX, myY, mySize, a, b, c, d;
  Balloon(int x, int y) {
    mySize = n;
    myX = x;
    myY = y;
    a = (int)(Math.random()*256);
    b = (int)(Math.random()*256);
    c = (int)(Math.random()*256);
    d = (int)(Math.random()*256);
    fill(a,b,c,d);
    //creates the class balloon
  }
  void show() {
    ellipse(myX, myY,mySize, mySize);
  }}

