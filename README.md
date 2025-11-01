# 🧠 Projeto de Testes Unitários — Jogo da Memória

Este projeto foi desenvolvido com o objetivo de praticar **testes unitários** em JavaScript, utilizando o **Jest** e princípios de **TDD (Test Driven Development)**.  
O sistema consiste em um **jogo da memória interativo**, onde o jogador deve encontrar os pares de cartas iguais, com foco em testar a **lógica principal do jogo** e a **manipulação do DOM**.

---

## 🎯 Objetivo

Criar um pequeno jogo da memória em JavaScript puro e aplicar **testes unitários** nas principais funções do projeto, garantindo que cada parte da lógica funcione corretamente.

---

## ⚙️ Tecnologias Utilizadas

- **JavaScript (ES6+)**
- **HTML5 & CSS3**
- **Jest** (para testes)
- **DOM Manipulation**

---

## 🧩 Funcionalidades Principais

- Geração dinâmica das cartas na tela  
- Embaralhamento das posições a cada jogo  
- Lógica de comparação entre cartas  
- Contador de tentativas e acertos  
- Reinício automático ou manual da partida  

---

## 🧪 Testes Implementados

Os testes garantem o funcionamento correto das principais funções:

- Verificação da criação das cartas  
- Teste da função de embaralhar o array  
- Comparação de cartas (match / no match)  
- Reset do jogo  
- Interações com o DOM (simulações com `JSDOM`, se aplicável)  

---

## 📂 Estrutura do Projeto

```markdown
📦 jogo-da-memoria  
 ┣ 📂 js/  
 ┃ ┣ game.js        # Lógica principal do jogo  
 ┃ ┗ dom.js         # Manipulação dos elementos da tela  
 ┣ 📂 tests/  
 ┃ ┣ game.test.js   # Testes da lógica principal  
 ┃ ┗ dom.test.js    # Testes relacionados ao DOM  
 ┣ 📄 index.html  
 ┣ 📄 style.css  
 ┣ 📄 package.json  
 ┗ 📄 README.md  


---

## ▶️ Como Rodar o Projeto

1. **Instalar as dependências:**
   ```bash
   npm install
   npm test
