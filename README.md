# 🎵 Projeto Arduino: Tocador de Músicas

Este projeto permite que você toque músicas famosas usando um **Arduino** e um **buzzer piezoelétrico**. As músicas são codificadas diretamente nos arquivos `.ino` e podem ser ativadas por botão.

---

## 🎶 Músicas Incluídas

- **Megalovania** – Toby Fox (Undertale)  
  🔗 Ouça no Spotify
- **Tema do Mario Bros**
- **Tema do Sonic**
- **Tema do Minecraft**

---

## 🧰 Materiais Necessários

- 1x Placa Arduino (Uno, Nano, etc.)
- 1x Buzzer piezoelétrico
- 1x Botão (push-button)
- 1x Resistor de 10kΩ (para o botão)
- Jumpers
- Protoboard

---

## 🔌 Esquema de Ligação

- **Buzzer**: conectado ao pino **D10**
- **Botão**: conectado ao pino **D8** com resistor de pull-down

---

## 🧠 Como Funciona

Cada música está codificada como uma sequência de comandos `tone()` que reproduzem notas musicais com durações específicas.  
Ao pressionar o botão, o Arduino inicia a execução da música correspondente.

---

## 📁 Organização do Projeto

- `Megalovania.ino` – Código completo da música Megalovania
- `Mario.ino` – Código do tema do Mario
- `Sonic.ino` – Código do tema do Sonic
- `Minecraft.ino` – Código do tema do Minecraft

---

## ➕ Como Adicionar Novas Músicas

1. Crie um novo arquivo `.ino`.
2. Defina as notas musicais com `#define` ou use uma biblioteca como `pitches.h`.
3. Use `tone(buzzer, NOTE, duration)` para tocar cada nota.
4. Adicione lógica de ativação (botão, sensor, etc.).

---

## 📚 Recursos Úteis

- Documentação Arduino tone()
- Conversor de notas para frequências
- Arduino IDE

---

## 📝 Licença

Este projeto é de uso livre para fins educacionais e não comerciais.  
Créditos das músicas aos respectivos compositores e desenvolvedores.

