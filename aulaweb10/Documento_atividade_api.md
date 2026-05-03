# 📄 Documentação – Atividade de Projetos Back-end

## 📚 Disciplina
Projetos de Desenvolvimento Back-end  

---

## 🎯 Objetivo da Atividade

Desenvolver uma API REST utilizando **Node.js + Express**, implementar operações CRUD, realizar deploy em nuvem e documentar os endpoints utilizando o Postman.

---

## 🧠 Descrição do Projeto

O projeto consiste em uma API de gerenciamento de notas, permitindo:

- Criar notas  
- Listar notas  
- Atualizar notas  
- Excluir notas  

Os dados são armazenados em um arquivo JSON (`data.json`), simulando um banco de dados simples.

---

## 🛠️ Tecnologias Utilizadas

- Node.js  
- Express.js  
- Body-parser  
- File System (fs)  
- Postman  
- Render (deploy back-end)  
- Vercel (deploy front-end)  

---

## 📁 Estrutura do Projeto

📦 projeto-notas
 ┣ 📜 server.js
 ┣ 📜 data.json
 ┣ 📜 package.json

## 🌐 Deploy

### 🔹 Back-end
- Plataforma: Render  
- Deploy via integração com GitHub  

### 🔹 Front-end
- Desenvolvido em React  
- Publicado na Vercel  

---

## 🧪 Testes com Postman

Foi criada uma coleção contendo todas as rotas da API.

### ✔️ Operações testadas:
- GET → Listagem de notas  
- POST → Criação de notas  
- PUT → Atualização  
- DELETE → Exclusão  

### ✔️ Configurações:
- Uso de JSON no body das requisições  
- Teste de status HTTP (200, 404, etc.)  

---

## 📸 Evidências

## Listar Nota

<img width="741" height="863" alt="image" src="https://github.com/user-attachments/assets/b1cac00f-9917-49fe-acd7-9e881c7c5073" />

## Criar Nota

<img width="724" height="650" alt="image" src="https://github.com/user-attachments/assets/4fe9acf9-befe-4885-a9c5-07a3169735b7" />

## Atualizar Nota

<img width="915" height="682" alt="image" src="https://github.com/user-attachments/assets/2c9ae746-2ce2-4d89-a75f-60e88d169caa" />

## Deletar Nota

<img width="975" height="562" alt="image" src="https://github.com/user-attachments/assets/8eb000ad-c705-45b0-8102-cdc17dddcee4" />

## Interface do sistema 

<img width="1578" height="825" alt="image" src="https://github.com/user-attachments/assets/96e6ee0d-1ddd-4a7d-b7f6-1c13aab8d16a" />

---

## ⚠️ Pontos de Atenção

### 🔐 Segurança
- Não possui autenticação  
- Não há validação de dados  
- CORS liberado para qualquer origem  

### 📉 Limitações
- Uso de JSON como banco de dados  
- Não escalável para grande volume  
- Possíveis problemas de concorrência  

### 🧱 Organização do Código
- Código centralizado em `server.js`  
- Ideal separar em:
  - Rotas  
  - Controllers  
  - Serviços  

---

## 🚀 Melhorias Futuras

- Implementar banco de dados (MongoDB/MySQL)  
- Adicionar autenticação (JWT)  
- Criar validação de dados  
- Melhorar estrutura do projeto  
- Implementar logs e tratamento de erros  

---

## 📎 Links do Projeto

- 🔗 Repositório GitHub front: https://github.com/leticiamoraes92/projeto-notas-frontend
- 🔗 Repositório GitHub back: https://github.com/leticiamoraes92/projeto-notas-backend
- 🔗 Deploy Back-end (Render): https://projeto-notas-backend.onrender.com/api/notes 
- 🔗 Deploy Front-end (Vercel): https://projeto-notas-frontend.vercel.app/   

---

## 📌 Conclusão

A atividade permitiu aplicar na prática conceitos essenciais de desenvolvimento back-end, incluindo:

- Criação de API REST  
- Implementação de CRUD  
- Integração com front-end  
- Deploy em nuvem  
- Testes e documentação  

Consolidando conhecimentos fundamentais para projetos reais.
