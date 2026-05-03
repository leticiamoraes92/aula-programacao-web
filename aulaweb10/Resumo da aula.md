# 📚  Projetos Back-end

## 🎯 Objetivo
Desenvolver uma API REST utilizando Express.js, aplicar operações CRUD, realizar deploy e documentar a API.

---

## 🧠 Conceitos Principais

### 🔹 Back-end e Frameworks
- Utilização de frameworks como Express.js
- Organização do código (MVC / camadas)
- Separação de responsabilidades

### 🔹 Protocolo HTTP
- Comunicação entre cliente e servidor
- Stateless (sem memória entre requisições)

#### Métodos HTTP:
- GET → Buscar dados  
- POST → Criar dados  
- PUT/PATCH → Atualizar dados  
- DELETE → Remover dados  

---

## 📦 JSON
- Formato leve para troca de dados
- Estrutura em objetos e arrays
- Utilizado como armazenamento no projeto

---

## ⚙️ API REST com Express

### 📁 Estrutura
- `server.js` → servidor  
- `data.json` → armazenamento  

### 🔄 CRUD

| Método | Rota | Função |
|--------|------|--------|
| GET | /api/notes | Listar notas |
| POST | /api/notes | Criar nota |
| GET | /api/notes/:id | Buscar por ID |
| PUT | /api/notes/:id | Atualizar |
| DELETE | /api/notes/:id | Excluir |

---

## 🌐 Deploy
- Back-end → Render  
- Front-end → Vercel  
- Integração com GitHub  

---

## 🧪 Testes e Documentação

### Postman:
- Testar endpoints  
- Criar coleções  
- Documentar API  
- Automatizar testes  

---

## ⚠️ Pontos de Atenção

### 🔐 Segurança:
- Sem autenticação  
- Sem validação de dados  
- CORS liberado  

### 📉 Limitações:
- Uso de JSON não escalável  
- Problemas com muitos dados  
- Sem controle de concorrência  

### 🧱 Organização:
- Código concentrado em `server.js`  
- Ideal separar em:
  - Rotas  
  - Controllers  
  - Serviços  

---

## 📌 Conclusão

A aula apresentou na prática:

- Criação de API REST  
- Implementação de CRUD  
- Integração com front-end  
- Deploy em nuvem  
- Testes com Postman  

Base essencial para desenvolvimento back-end.
