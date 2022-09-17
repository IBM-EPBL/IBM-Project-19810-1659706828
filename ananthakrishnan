int t=2;
int e=3;
void setup()
{
  Serial.begin(9600);
  pinMode(t,OUTPUT);
  pinMode(e,INPUT);
  pinMode(13,OUTPUT);
  pinMode(12,OUTPUT);
}
void loop ()
{
  digitalWrite(t,LOW);
  digitalWrite(t,HIGH);
  delayMicroseconds(10);
  digitalWrite(t,LOW);
  float dur = pulseIn(e,HIGH);
  float dis = (dur*0.0343)/2;
  Serial.print("distance     : ");
  Serial.println(dis);
  double a = analogRead(A0);
  Serial.print("Analog value : ");
  Serial.println(a);
  digitalWrite(13,HIGH);
  Serial.print(" LED STATUS  : ");
  Serial.println("LED GLOW");
  tone(12,30,1000);
  
}
  
