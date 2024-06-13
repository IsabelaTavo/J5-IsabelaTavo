# J5-IsabelaTavo
function setup() {
  createCanvas(700, 700);
  background("rgb(179,179,252)");
}
   
  function draw() {
    
  stroke ("220");
  fill ("rgb(241,165,165)");

 // console.log(mouseIsPressed);

  if (mouseIsPressed){
  rect(mouseX, mouseY, 15, 20);}
  
}
