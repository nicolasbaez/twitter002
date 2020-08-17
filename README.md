## twitter002 | #つぶやきProcessing 
https://twitter.com/nicolasbaez/status/1228101950429855744?s=20

![twitter](https://github.com/nicolasbaez/twitter002/blob/master/twitter002.gif)
```processing
float x=0; void setup(){ size(512,256,P3D); } void draw(){ background(0); translate(256,128,192); rotateX(radians(x)); rotateY(radians(x/2)); rotateZ(radians(x/4)); stroke(255); fill(map(sin(radians(x)),-1,1,0,192),96,96); sphereDetail(9); sphere(80); x++; }
````
