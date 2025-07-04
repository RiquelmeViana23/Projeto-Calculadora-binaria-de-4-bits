# 🧮 Calculadora Binária de 4 Bits com ULA — Logisim

Projeto desenvolvido como parte da disciplina de Lógica Digital no curso de Ciência da Computação, com o objetivo de aplicar conceitos de aritmética binária e circuitos lógicos em uma calculadora funcional construída no simulador **Logisim**.

## 📚 Sobre o Projeto

A calculadora binária de 4 bits foi construída com circuitos lógicos **manuais** utilizando **portas AND, OR, XOR, NOT, multiplexadores, somadores completos, subtratores, multiplicadores** e um **divisor (pré-fabricado)**. A ULA (Unidade Lógica e Aritmética) desenvolvida executa as seguintes operações:

- ✅ Soma
- ✅ Subtração
- ✅ Multiplicação
- ✅ Divisão (componente pronto do Logisim)

O resultado é exibido tanto em **binário** quanto em **decimal** com **displays de 7 segmentos** que representam unidade, dezena e centena.

## 🛠️ Tecnologias Utilizadas

- [Logisim](http://www.cburch.com/logisim/) — Simulador de circuitos digitais
- Conceitos de:
  - Aritmética binária
  - Portas lógicas (AND, OR, NOT, XOR)
  - Somador e subtrator completo
  - Multiplexadores (MUX 4x1)
  - ULA personalizada

## 🧪 Funcionalidades

- Entradas de dois números binários de 4 bits
- Saída em binário e decimal
- Seletor de operação aritmética via código binário:
  - `00` → Soma
  - `01` → Subtração
  - `10` → Multiplicação
  - `11` → Divisão
- Tratamento de erros (ex: divisão por zero)
- Decodificação e conversão de valores para 7 segmentos

## 📷 Imagens do Projeto

*(Insira aqui imagens ou GIFs do circuito se desejar)*

## 👨‍💻 Como Executar

1. Faça o download do [Logisim](http://www.cburch.com/logisim/)
2. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/calculadora-binaria-logisim.git
