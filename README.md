# eloferreiraaa
  function setup() {
  createCanvas(800, 800);
  background("purple");
}

  function draw() {

  stroke("black");
  fill ("red");

 // console.log(mouseIsPressed); 
  
  if (mouseIsPressed) {
  rect (mouseX, mouseY, 20, 35);
  }
}
  
