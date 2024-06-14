# Aula-alura
function setup() {
  createCanvas(1000, 1000);
   background("250");
}

function draw() {
 
  
 stroke("pink")
fill("pink")

  if (mouseIsPressed) {
  rect(mouseX, mouseY, 10, 20);
  }

}
