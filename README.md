int a =600;
int a1,a2,a3,a4,a5,a6=0;
int n1,n2,n3,n4,n5,n6;void setup ()
{
Serial.begin(115200);
pinMode(11,OUTPUT);
pinMode(10,OUTPUT);
pinMode(9,OUTPUT);
pinMode(6,OUTPUT);
pinMode(5,OUTPUT);
pinMode(3,OUTPUT);}
void loop()
{
if(a1==0)
{
n1 = analogRead(A0);
}
else if(a1==1)
{
n1 = analogRead(A0);
n1=300;
}
if(n1<= a )
{
digitalWrite(11,HIGH);
a1=1;
}
else
digitalWrite(11,LOW);
delay(100);
if(a2==0)
{
n2 = analogRead(A1);
}
else if(a2==1)
{
n2 = analogRead(A1);
n2=300;
}
if(n2<= a )
{
digitalWrite(10,HIGH);
a2=1;
}
else
digitalWrite(10,LOW);
delay(100);
if(a3==0)
{
n3 = analogRead(A2);
}
else if(a3==1)
{
n3= analogRead(A2);
n3=300;
}
if(n3<= a )
{
digitalWrite(9,HIGH);
a3=1;
}
else
digitalWrite(9,LOW);
delay(100);
if(a4==0)
{
n4 = analogRead(A3);
}
else if(a4==1)
{
n4 = analogRead(A3);
n4=300;
}
if(n4<= a )
{
digitalWrite(6,HIGH);
a4=1;
}
else
digitalWrite(6,LOW);
delay(100);
if(a5==0)
{
n5 = analogRead(A4);
}
else if(a5==1)
{
n5 = analogRead(A4);
n5=300;
}
if(n5<= a )
{
digitalWrite(5,HIGH);
a5=1;
}
else
digitalWrite(5,LOW);
delay(100);
if(a6==0)
{
n6 = analogRead(A5);
}
else if(a6==1)
{
n6 = analogRead(A5);
n6=300;
}
if(n6<= a )
{
digitalWrite(3,HIGH);
a6=1;
}
else
digitalWrite(3,LOW);
delay(100);
}
