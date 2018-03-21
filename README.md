# Ugly-green

makeGreen();
makePin();
drawGolfball();
function makeGreen() {
  penUp();
  moveTo(80, 371);
  penRGB(50, 205, 50, 1);
  penDown();
  turnRight(90);
  penWidth(200);
  moveForward(160);
  penUp();
}
function makePin() {
  moveTo(87, 340);
  penDown();
  penWidth(10);
  turnLeft(90);
  penColor("black");
  dot(15);
  penColor("white");
  moveForward(100);
  penColor("red");
  penWidth(30);
  turnRight(120);
  moveForward(35);
  turnRight(120);
  moveForward(35);
  turnRight(120);
  moveForward(35);
  penUp();
}
function drawGolfball() {
  moveTo(216, 400);
  penDown();
  penColor("white");
  dot(5);
  penUp();
  moveTo(160, 214);
}
