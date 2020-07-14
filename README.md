# twitter002
#つぶやきProcessing float x=0; void setup(){ size(512,256,P3D); } void draw(){ background(0); translate(256,128,192); rotateX(radians(x)); rotateY(radians(x/2)); rotateZ(radians(x/4)); stroke(255); fill(map(sin(radians(x)),-1,1,0,192),96,96); sphereDetail(9); sphere(80); x++; }
