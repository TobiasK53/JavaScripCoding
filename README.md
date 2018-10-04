# JavaScripCoding
Place to store my codes
let x=0;
let y=0;
let spacing = 10;

function setup() {
	createCanvas(windowWidth, windowHeight);
	background(100);
}

function draw() {
//	ellipse(mouseX, mouseY, 20, 20);
	fill(25,54,36);
stroke(255);
	if (random(1)<0.5) {
		ellipse(x,y,x+spacing,y+spacing);
	 } else {
		ellipse(x,y+spacing,x+spacing,y);
	}
	x=x+spacing;
	if (x > width) {
		x = 0;
		y = y + spacing;
	}}
