void setup() {
  frameRate(45);
  colorMode(RGB);
  size(2000, 1500);
  background(87,70,255,255);
}

void draw() {
  float a = random(0, height);
  float b = random(0, width);
  float c = random(10, 30);
  float d= random(1, 360);
  float e= random(20,255);
  float f= random(0,2000);
  float g= random(0,2000);
  float S= random(40,60);
  float B= random(100,150);
  colorMode(HSB, 360, 100, 100);
  fill(d, 40, 100);
  line(f, g, a, b);
  strokeWeight(c);
  stroke(d, S, B,e);
  fill(33, 60,100);
  ellipse(width/2, height/2, 50, 50);
}
