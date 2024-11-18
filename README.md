# p5-js-3<!DOCTYPE html>
<html lang="en">
  <head>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.3/p5.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.9.3/addons/p5.sound.min.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="utf-8" />

  </head>
  <body>
    <main>
    </main>
    <script src="sketch.js"></script>
  </body>
</html>
function setup() {//função, preparar o que qu realizar
  createCanvas(600, 600);// criar canvas,um uporte para pintura
  background("white")//fundo ou tela branca
}

function draw() {//desenhar
  stroke("blue")//muda a cor do traço que cntorna o retângulo para azul
  fill("red")//muda a cor do retângulo para vermelho
  
  //console.log(mouseIsPressed)//para aber e o mouse está pressionado
  
  if(mouseIsPressed){//se o mouse estiver pressionado, execute o que está entre as chaves
     rect(mouseX, mouseY, 20, 35)//retângulo, local onde ele está e seu tamanho, o local varia de acordo com a variável mouse
 }
}
