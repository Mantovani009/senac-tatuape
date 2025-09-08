# Aula de Eletrônica Básica com Arduino  

## 1. Estrutura básica de um código Arduino

Um programa (também chamado de **sketch**) no Arduino sempre tem duas funções principais:

```cpp
void setup() {
  // Aqui vai o código que roda apenas uma vez,
  // quando o Arduino é ligado ou resetado.
}

void loop() {
  // Aqui vai o código que roda continuamente,
  // em repetição infinita.
}
****
