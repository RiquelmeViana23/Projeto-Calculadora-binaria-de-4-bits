# 🧮 Calculadora Binária de 4 Bits com ULA — Logisim

Projeto desenvolvido como parte da disciplina de Lógica Digital no curso de Ciência da Computação, com o objetivo de aplicar conceitos de aritmética binária e circuitos lógicos em uma calculadora funcional construída no simulador **Logisim**.

---

## 📚 Sobre o Projeto

A calculadora binária de 4 bits foi construída com circuitos lógicos **manuais**, utilizando portas **AND, OR, XOR, NOT**, além de **somadores completos, subtratores completos, multiplicador**, e um **divisor (pré-fabricado)**. Também utilizamos **multiplexadores 4x1** e **displays de 7 segmentos** para converter os resultados binários em formato decimal.

A calculadora é capaz de realizar as seguintes operações:

- ✅ Soma
- ✅ Subtração
- ✅ Multiplicação
- ✅ Divisão (usando componente pronto do Logisim)

---

## 🛠️ Tecnologias Utilizadas

- [Logisim](http://www.cburch.com/logisim/)
- Conceitos de:
  - Aritmética Binária
  - Portas lógicas: AND, OR, NOT, XOR
  - Somadores e subtratores completos
  - Multiplicação binária por somas parciais
  - MUX 4x1 (multiplexadores)
  - ULA personalizada
  - Displays de 7 segmentos
  - Comparadores

---

## ⚙️ Estrutura do Circuito

### 🧠 ULA (Unidade Lógica e Aritmética)
Responsável por reunir as quatro operações e integrá-las em um único bloco. Utiliza um **MUX 4x1 de 8 bits** para selecionar a operação correta, com base no código de controle binário inserido (`00`, `01`, `10`, `11`).

### ➕ Somador Completo
Circuito com 4 bits usando lógica com XOR, AND e OR. Controla corretamente o **carry in** e **carry out** para somas encadeadas.

### ➖ Subtrator Completo
Também com 4 bits e portas lógicas combinadas. Usa **borrow in** e **borrow out** para representar subtrações em cascata.

### ✖️ Multiplicador Binário
Implementado manualmente, baseado em somas parciais e deslocamento de bits. Produz resultado com 8 bits.

### ➗ Divisor
Devido à sua complexidade, foi utilizado o **divisor padrão do Logisim**, com lógica de detecção de divisão por zero (LED de erro).

### 🎚️ MUX 4x1 de 8 Bits
Seleciona qual operação será enviada à saída. Cada bit é controlado por MUXs de 1 bit e os seletores determinam a operação ativa.

### 🔢 Displays de 7 Segmentos
Recebem os valores binários e os convertem para decimal, representando **unidades, dezenas e centenas**.

### 🔍 Comparador Binário
Verifica se dois valores binários são iguais. Se forem, um LED acende como indicação de igualdade.

---

## 🚀 Como Executar

1. Abra o arquivo `.circ` no **Logisim**
2. Insira dois valores binários nas entradas
3. Selecione a operação desejada com os **bits de controle**:
   - `00` → Soma
   - `01` → Subtração
   - `10` → Multiplicação
   - `11` → Divisão
4. Visualize os resultados nos **displays binários** e **decimais**

---

## 👥 Integrantes do Grupo

- Alexi Dias Amâncio  
- Bruno Leite Saldanha  
- Luan Dias Portela  
- **Riquelme Viana de Almeida**  
- Victor Gustavo Miranda de Jesus  

**Orientador:** Prof. Manoel Moraes

---

## 📘 Referências

- [Multiplicador Binário de 4 Bits no Logisim](https://www.youtube.com/watch?v=NuCxB-z_ksk)  
- [Subtrator Binário em Logisim: Passo a Passo](https://www.youtube.com/watch?v=04XtWPRMXaU)  
- [Live sobre Implementação de ULA no Logisim](https://www.youtube.com/live/DsXT82zyh9E)  
- [Como Implementar Calculadora Binária no Logisim](https://www.youtube.com/watch?v=O34KquoMpT0)

---

## 📝 Licença

Este projeto foi desenvolvido exclusivamente para **fins acadêmicos e educacionais**.
