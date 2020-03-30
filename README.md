# processing2

한글사용 배너 
키패트 0~9 누르면 속도가 빨라짐

<pre>
<code>
PFont f;
void setup(){
  size(800,400);
  //textSize(128);
  f = createFont("굴림", 64);
  textFont(f);
}
int i , a = 1;
void draw(){
  background(194);
  if(keyPressed)
    a = key-'0';
  text("안동대 컴공 사랑합니다.", 50, i = i+a);
  if(i>400 || i <0) 
    i =0;
}
</code>
</pre>
