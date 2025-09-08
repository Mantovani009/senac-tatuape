
# Aula de Eletrônica Básica com Arduino

## Projeto: Pisca LED 💡

Este projeto é o clássico **Blink** do Arduino.  
Ele faz um LED piscar em intervalos de tempo programados.

---

## Código Fonte

```cpp
/**
 * Pisca LED
 * @author Eduardo Mantovani
 */

// Função de configuração (executa uma vez)
void setup() {
  pinMode(13, OUTPUT); // Define o pino 13 como saída
}

// Função principal (repete para sempre)
void loop() {
  digitalWrite(13, HIGH); // Liga o LED
  delay(1000);            // Aguarda 1 segundo
  digitalWrite(13, LOW);  // Desliga o LED
  delay(1000);            // Aguarda 1 segundo
}

