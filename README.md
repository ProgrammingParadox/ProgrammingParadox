I exist.

Or do I?

Nah, I'm just messing with you. 

I like to program with vanilla JavaScript, though I know python and a little bit of Arduino IDE/C++. 

_The great city of paradoxia once stood proudly in the center of a magnificent forest._

_That was before it had fallen._

_There is only one left, now. Once upon a time, he had a name. But now there was no living mind in existance capable of comprehending it. So he is simply known as Paradox..._

Thank goodness that's not me. At least, I hope I'm not a character some dude made up.

You should go read some Brandon Sanderson.

Put this into a new PJS program on Khan Academy:
```javascript
function draw(){var t=Array(16e4),Y=1600,n,i,p,m=200,d=400,f=255,a=1/f,x,y;point(m,m);point(m-1,m);point(m+1,m);this.draw=function(){this.loadPixels();p=this.imageData.data;for(y=d;y+1;y--){for(x=d;x;x--){i=x+d*y<<2;n=8-(p[i-Y-4]+p[i-Y]+p[i-Y+4]+p[i-4]+p[i+4]+p[i+Y-4]+p[i+Y]+p[i+Y+4])*a|0;t[i]=p[i]===f?n<2?0:3<n?0:t[i]:n===3?f:t[i];t[i]=t[i+1]=t[i+2]=f-t[i];t[i+3]=f;}}for(i=t.length;i;i--){p[i]=t[i];}this.updatePixels();};}
```
