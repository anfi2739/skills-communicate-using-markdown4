# Header 1
## sub header 
#### final words 
![Elite](https://preview.redd.it/lnn56zbiboj91.png?width=574&format=png&auto=webp&s=47c21b0a771829f4488bc5c12bbc1f30edbbbf6b)

``` javascript

let colorArray = ["red","orange","yellow","green","blue","purple"];

let squareSize = 86;



function setup() {
  createCanvas(600, 600);
}

function draw() {
  background(0);
  //86 pixes wide
  for (let i=0; i<=5; i+=1) {
    for (let j=0; j<=5; j+=1){
      fill(colorArray[j]);
      rect(12 + i*squareSize + 12*i, 12 + j*squareSize + j*12, squareSize, squareSize);
    }
  }
 
}
```
- [ ] Jump!
- [ ] Spin!
- [ ] Run!
