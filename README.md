## twitter010 | #つぶやきProcessing 
https://twitter.com/nicolasbaez/status/1281076392910880771?s=20

![twitter](https://github.com/nicolasbaez/twitter010/blob/master/twitter010.gif)
```processing
float i,r,x,y,w=512;void setup(){size(512,512);}void draw(){fill(0,18);rect(0,0,w,w);y-=2;colorMode(HSB,w);fill(r,w,w);for(i=0;i&lt;3;i+=0.2){circle(r*cos(i)+x,r*sin(i)+y-map(sin(map(y,w/2,0,0,3)),0,1,0,w/2),random(9));r+=0.2;}if(y&lt;0){x=random(w);y=w*0.64;r=0;}}
```
