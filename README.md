# Memory Game

Jogo da memória desenvolvido utilizando **PlatformIO**, **Arduino** e **C++**.

O jogo gera uma sequência aleatória de luzes que é apresentada ao jogador. Em seguida, o jogador deve repetir exatamente a mesma sequência utilizando os botões correspondentes. A cada rodada, um novo passo é adicionado à sequência, aumentando progressivamente a dificuldade. O jogo continua até que o jogador cometa um erro, momento em que a partida é encerrada e reiniciada.

## Objetivos de Aprendizado

Este projeto foi desenvolvido com foco no aprendizado de:

- Arduino
- C++
- Programação Orientada a Objetos (POO)
- Circuitos Eletrônicos
- Integração entre Hardware e Software

---

## Hardware

Durante o desenvolvimento, foram utilizados diversos componentes eletrônicos com o objetivo de compreender seu funcionamento e aplicação prática.

### Componentes utilizados

- 1 Arduino Uno R3 (CH340)
- 4 LEDs
- 4 Diodos retificadores (1N4007)
- 4 Resistores de 330 Ω
- 4 Botões
- 1 Resistor de 1 kΩ
- 1 Buzzer ativo 5 V
- 1 Transistor BJT NPN (2N2222)

### Esquemático do circuito

![Esquemático](img/Schematic_Memory-Game-Sheet_2026-07-03.png)

---

## Estrutura do projeto

```text
.
├── .vscode/      # Configurações do Visual Studio Code
├── img/          # Imagens do projeto
├── include/      # Arquivos de cabeçalho (.h)
├── lib/          # Bibliotecas utilizadas
├── src/          # Código-fonte principal
└── test/         # Diretório reservado para testes do PlatformIO
```

---

## Tecnologias utilizadas

- C++
- Arduino Framework
- PlatformIO
- Visual Studio Code

---

## Como executar o projeto

### Pré-requisitos

- Visual Studio Code
- Git
- Extensão PlatformIO IDE

### Clonando o repositório

```bash
git clone https://github.com/RenanSoaresSouza/Memory-Game.git
```

### Executando

1. Abra a pasta do projeto no Visual Studio Code.
2. Abra o PlatformIO.
3. Selecione a placa **Arduino Uno**.
4. Compile o projeto.
5. Faça o upload para a placa.

---

## Licença

#### Este projeto foi desenvolvido para fins de estudo e aprendizado.
![PlatformIO](https://img.shields.io/badge/PlatformIO-IDE-orange)
![Arduino](https://img.shields.io/badge/Arduino-UNO-blue)
![Language](https://img.shields.io/badge/C%2B%2B-17-blue)
![License](https://img.shields.io/badge/license-MIT-green)

