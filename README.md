# Tac-metro
// Pino de saída do sinal
const int pinoSinal = 9; 

void setup() {
  // Configura o pino como saída
  pinMode(pinoSinal, OUTPUT);
  
  // Gera uma onda quadrada de 100 Hz no pino selecionado
  tone(pinoSinal, 100); 
}

void loop() {
  // O sinal roda em segundo plano, o loop fica livre.
}

Conta giros
