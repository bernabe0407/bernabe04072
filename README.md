lavra;

function setup() {
  createCanvas(400, 400);

  palavra = palavraAleatoria();
  
}

function palavraAleatoria() {
  
  let palavras = ["Caminhante", "Caminho", "Caminha"];
  
  return random(palavras);
}

function inicializaCores() {
  
  background("white");
  fill("black");
  textSize(64);
  textAlign(CENTER, CENTER);
}

function d
