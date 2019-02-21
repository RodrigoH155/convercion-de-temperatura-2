# convercion-de-temperatura-2
function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
	var tempMtyC= 13;
	tempMtyF = celsiousToF(tempMtyC);
	console. log(tempMtyF);
	
	}
function celsiusToF(tempC) {
	var tempF;
	tempF = (9/5)*tempC+32 


var p;
function setup() {
  createCanvas(400, 400);
	p = new Pelota();
}

function draw() {
  background(220);
}
class Pelota{
	constructor(){
		this.x =200 ;
		this.y = 200;
		this. tam = 50;
	}	
	mostrar(){
		ellipse(this.x,this.y,this.tam, this.tam)
		}
	moverX(){
		this.x = this.x 
}
	}
	
	
	
	
	
	
	function setup() {
  createCanvas(400, 400);
}

function draw() {
  background(220);
	var x = 5
	var y = factorial(x);
}
function factorial(x){
	var res;
	if (num = 0){
		res = 1;
		
	}
	else{ 
		res= num*factorial(num -1);

	}
	return res;
	}
