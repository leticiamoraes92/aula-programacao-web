# 📚 Resumo – Introdução a Frameworks Front-end

## 🔹 Frameworks Front-end
São ferramentas que facilitam o desenvolvimento de interfaces web, oferecendo estrutura pronta, organização e reutilização de código.

### ✔️ Vantagens:
- Mais produtividade  
- Código organizado  
- Reutilização de componentes  
- Manutenção facilitada  

---

## 🔹 Framework vs Biblioteca

- *Framework:* controla o fluxo da aplicação (ex: Angular, Vue)  
- *Biblioteca:* você controla quando usar (ex: React)  

---

## 🔹 React
- Biblioteca criada pelo Facebook  
- Baseada em componentes reutilizáveis  
- Usa Virtual DOM → mais desempenho  

### 📌 Conceitos:
- *useState:* controla dados  
- *useEffect:* executa efeitos (ex: API)  
- *JSX:* mistura HTML com JavaScript  

---

## 🔹 DOM e Virtual DOM
- DOM = estrutura da página  
- Virtual DOM = versão otimizada usada pelo React  
- Atualiza apenas o necessário  

---

## 🔹 Node.js e NPM
- *Node.js:* permite rodar JavaScript fora do navegador  
- *NPM:* gerencia bibliotecas e dependências  

---

## 🔹 Criando Projeto React

```bash
npx create-react-app meu-projeto
cd meu-projeto
npm start
# 🚀 Projeto React – Atividade Frameworks Front-end

# 📌 Descrição

Este projeto foi desenvolvido como atividade da disciplina de Desenvolvimento Web, com o objetivo de aplicar conceitos de **frameworks front-end**, utilizando a biblioteca React.

---

# 🎯 Objetivo

Criar uma aplicação React contendo múltiplas funcionalidades, demonstrando o uso de componentes, estado e integração com API.

---

# 🧩 Funcionalidades

## ✔️ To-Do List
- Adição de tarefas  
- Remoção de tarefas  
- Gerenciamento de estado com `useState`  

---

## ✔️ Contador de Cliques
- Incremento e decremento  
- Atualização dinâmica da interface  

---

## ✔️ Jogo da Velha
- Tabuleiro 3x3  
- Alternância entre jogadores (X e O)  
- Verificação de vencedor  
- Reinício do jogo  

---

## ✔️ Calculadora
- Operações básicas (+, -, *, /)  
- Entrada dinâmica  
- Cálculo automático  

---

## ✔️ Buscador de CEP
- Consumo de API (ViaCEP)  
- Retorno de endereço e cidade  

---

# 🛠️ Tecnologias Utilizadas

- React  
- JavaScript  
- HTML  
- CSS  
- Node.js  
- NPM  

---

# 📂 Estrutura do Projeto

src/
 ├── components/
 │   ├── Header.js
 │   ├── Todo.js
 │   ├── Contador.js
 │   ├── JogoVelha.js
 │   ├── Calculadora.js
 │   └── Cep.js
 ├── App.js
 ├── App.css

