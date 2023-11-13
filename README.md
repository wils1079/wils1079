// Definir el pin al que está conectado el LED
const int pinLed = 13;

void setup() {
  // Configurar el pin del LED como salida
  pinMode(pinLed, OUTPUT);
}

void loop() {
  // Encender el LED durante 1 segundo
  digitalWrite(pinLed, HIGH);
  delay(1000);

  // Apagar el LED durante 1 segundo
  digitalWrite(pinLed, LOW);
  delay(1000);
}
