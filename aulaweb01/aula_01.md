## Aula 01 — Apresentação da Disciplina e Introdução à Programação Web

## 🎯 Objetivo da aula
Apresentar a disciplina de Programação Web, o plano de ensino e uma visão geral dos temas do semestre, além de orientar a 1ª atividade prática em grupo.

---

## Apresentação da turma 

![2](https://github.com/user-attachments/assets/23824061-41ee-4426-8adc-480c62fb2773)

Discussão inicial com a turma sobre:
- 💼 experiências profissionais na área   
- 🚀 expectativas após o curso
- 🎮 hobbies / passatempo

---

## Estrutura da disciplina (plano de aulas/ensino)

<img width="1366" height="555" alt="image" src="https://github.com/user-attachments/assets/0092d86d-d110-40f0-865e-7f97eb8878b4" />

O plano de ensino inclui:
- ✅ objetivos de aprendizagem
- 📌 ementa
- 🗂️ conteúdo programático
- 🧑‍🏫 metodologia de ensino
- 🛠️ recursos didáticos
- 📝 avaliação
- 📚 bibliografia

---

##  Tópicos introdutórios apresentados

### 1) Versionamento e Deploy

**Versionamento:** controlar e registrar mudanças no código com Git (commits, branches e merges) para manter histórico, facilitar colaboração e permitir voltar versões.
**Deploy:** publicar a aplicação em um servidor/serviço (staging/produção), de preferência automatizado por CI/CD (ex.: GitHub Actions) para testar, buildar e entregar a cada atualização na branch principal.

- 🎨 Conexão entre design e tecnologias web para criar interfaces funcionais
- 🧾 Controle de versões: histórico de mudanças para colaborar e recuperar versões
- 🌿 Branches: desenvolvimento paralelo
- 🚀 Deploy: importância, métodos e ambientes (dev/prod)
- 🧰 Plataformas: GitHub, GitLab, Bitbucket
- 🤖 Boas práticas: CI/CD, deploy automatizado e monitoramento

### 2) Arquitetura de um site (escopo e UX/UI)

<img width="1500" height="693" alt="image" src="https://github.com/user-attachments/assets/d7b8138f-fb25-4153-9a3e-6d21a6c51937" />

**Arquitetura de um site** é planejar **o que** ele vai ter e **como** o usuário vai usar.
**Escopo:** define objetivo, público, páginas/funcionalidades, regras/limites e métricas de sucesso.  
**UX:** organiza jornadas e fluxos para ser fácil, rápido, acessível e responsivo.  
**UI:** define o visual (layout, cores, tipografia e componentes) com consistência.
  
- 🧠 Definição de escopo e estrutura do projeto
- 👀 Importância para UX/UI
- 🔄 Validação de ideias e melhoria contínua
- 🧪 Protótipos com ferramentas de design/prototipação

### 3) JavaScript (Vanilla JS)

<img width="612" height="497" alt="image" src="https://github.com/user-attachments/assets/3e1dba6d-5285-4d03-8c56-4d349b29d6a4" />

**Vanilla JS** é o JavaScript “puro”, sem frameworks/bibliotecas (como React, Vue ou Angular).  
Ele é usado para **dar interatividade** às páginas: manipular o **DOM**, responder a **eventos**, validar **forms**, consumir **APIs** e atualizar conteúdo sem recarregar a página.

## Principais conceitos 🧠
- **Variáveis e tipos:** `let`, `const`, strings, numbers, arrays, objects.
- **Funções:** declaração, arrow functions, parâmetros e retorno.
- **DOM:** selecionar e alterar elementos (`querySelector`, `classList`, `innerText`, `style`).
- **Eventos:** cliques, teclado, envio de formulário (`addEventListener`).
- **Assíncrono:** `Promise`, `async/await`, `fetch` para requisições.
- **Módulos:** organizar código com `import/export` (quando suportado no projeto).

## Vantagens ✅
- Leve, rápido para projetos pequenos e ótimo para aprender a base do front-end.

- ⚡ Linguagem essencial no front-end
- 🍦 “Vanilla JS”: JS puro (sem bibliotecas)
- 🧩 Usos: manipular páginas, lógica de interface e comunicação com servidores

### 4) Servidores, hospedagem e CMS

<img width="800" height="450" alt="image" src="https://github.com/user-attachments/assets/474063f9-dad2-4686-800a-cf12c6673b58" />

## Servidores 🖥️
Computadores (físicos ou na nuvem ) que **armazenam e executam** um site/app, respondendo às requisições dos usuários (HTTP/HTTPS ).

## Hospedagem 🌐
É o **serviço** que disponibiliza seu site na internet. Pode incluir:
- **Armazenamento** 
- **Banco de dados** 
- **Domínio e DNS** 
- **SSL**
- **Escalabilidade** e backups 
Tipos comuns: **compartilhada** , **VPS** , **dedicada**  e **cloud**.

## CMS (Content Management System) 🧩
Sistema para **criar e gerenciar conteúdo** (páginas, posts, imagens) sem programar tanto.
Exemplos: **WordPress** , **Joomla** , **Drupal** .  
Vantagens: atualização fácil , plugins  e temas .  
Atenção: exige manutenção/segurança  e pode ficar pesado dependendo do uso .

- 🏢 Conceitos de infraestrutura e hospedagem
- 🧱 CMS: criar/gerenciar sites com menos código
- 🧩 Plugins, personalização e criação de páginas

### 5) Website builders

<img width="787" height="630" alt="image" src="https://github.com/user-attachments/assets/71ccf9b1-f47b-4bae-a8a2-35b702370cc8" />

**Website builders** são plataformas que permitem **criar sites sem programar** (ou com pouco código), usando **arrastar e soltar** , templates e configurações prontas ⚙️.

## O que normalmente oferecem 🛠️
- Templates prontos e responsivos
- Editor visual (drag-and-drop) 
- Hospedagem e domínio integrados 
- SEO básico 
- Formulários e integrações 
- E-commerce (em alguns planos) 

## Vantagens ✅
- Rápido para colocar no ar 
- Fácil de manter e atualizar 
- Bom para sites simples (portfólio, institucional, landing page) 

## Limitações ⚠️
- Menos liberdade de personalização 
- Dependência da plataforma (lock-in) 
- Pode ficar caro conforme cresce 
- Performance/recursos avançados podem ser limitados 

### 6) Frameworks front-end

<img width="1200" height="630" alt="image" src="https://github.com/user-attachments/assets/59a6e352-a4e1-43d0-924d-24c9d935ec70" />

**Frameworks (e bibliotecas) front-end** são ferramentas que ajudam a **construir interfaces** de forma mais organizada e rápida, com componentes reutilizáveis e melhor manutenção do código.

## Para que servem 🛠️
- Criar **interfaces dinâmicas** (SPAs) 
- Reaproveitar **componentes** (botões, cards, páginas) 
- Gerenciar **estado** e dados da tela 
- Melhorar organização, escalabilidade e produtividade 

## Exemplos populares 🌟
- **React**  (biblioteca)
- **Vue** 
- **Angular** 
- **Svelte** 

## Vantagens ✅
- Desenvolvimento mais rápido 
- Código mais reutilizável 
- Melhor para projetos médios/grandes 
- Ecossistema grande (rotas, formulários, UI, testes) 

## Desvantagens ⚠️
- Curva de aprendizado 
- Configuração/estrutura do projeto pode ser mais complexa 
- Dependência do framework e atualizações 

- 📦 Benefícios e conceito
- ⭐ Exemplos: React, Vue, Angular
- 🧩 Componentes reutilizáveis
- 🧭 Rotas, estado e integração com APIs

### 7) Frameworks back-end

<img width="805" height="428" alt="image" src="https://github.com/user-attachments/assets/932666d4-446d-45ce-8d46-0ef37a7c1065" />

**Frameworks back-end** são ferramentas que ajudam a criar a **parte do servidor** de um sistema: regras de negócio, APIs, autenticação e acesso ao banco de dados.

## Para que servem 🛠️
- Criar **APIs** (REST/GraphQL) 
- Gerenciar **rotas** e requisições HTTP 
- Implementar **autenticação/autorização** 
- Conectar com **banco de dados** (ORM/queries) 
- Ajudar com **segurança**, validações e logs 

## Exemplos populares 🌟
- **Node.js:** Express, NestJS 
- **Python:** Django, Flask, FastAPI 
- **Java:** Spring Boot 
- **C#:** ASP.NET Core 
- **PHP:** Laravel 
- **Ruby:** Ruby on Rails 

## Vantagens ✅
- Desenvolvimento mais rápido 
- Estrutura pronta e organizada 
- Recursos de segurança e boas práticas embutidas 
- Facilita manutenção e crescimento do projeto 

## Desvantagens ⚠️
- Curva de aprendizado 
- Pode trazer “peso” extra para projetos bem simples 
- Depender do ecossistema/atualizações do framework 

- 🧠 Organização e produtividade no desenvolvimento
- 🧱 Padrões: MVC e APIs REST
- 🗄️ Integração com banco de dados
- 🔐 Autenticação e segurança

###  8) Banco de Dados NoSQL

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/814aacc3-3083-40ae-bd13-1103788ac952" />

**NoSQL** (Not Only SQL) é um tipo de banco de dados que **não depende do modelo relacional tradicional** (tabelas com linhas/colunas). Ele é muito usado quando precisamos de **flexibilidade**, **escala** e **alto desempenho** com grandes volumes de dados.

## Características principais 🧩
- **Esquema flexível** (dados podem variar de um registro para outro) 
- **Escalabilidade horizontal** (distribuir em vários servidores) 
- Boa performance para certos tipos de consultas e cargas 

## Tipos comuns 🔎
- **Documentos** 📄 (ex.: MongoDB) — dados em JSON/BSON.
- **Chave-valor** 🔑 (ex.: Redis) — rápido para cache e sessões.
- **Colunar** 🧱 (ex.: Cassandra) — ótimo para grandes volumes e alta disponibilidade.
- **Grafos** 🕸️ (ex.: Neo4j) — ideal para relacionamentos complexos.

## Vantagens ✅
- Flexível para mudanças rápidas 
- Escala bem para muitos acessos 
- Bom para dados semi-estruturados (JSON) 

## Desvantagens ⚠️
- Pode ter menos suporte a **joins** e consultas complexas 
- Consistência pode variar (dependendo do modelo) 
- Modelagem exige pensar diferente do relacional 

- 🧩 Não-relacional (não depende de tabelas fixas)
- 🧷 Schema flexível (dados variáveis)
- 📈 Escalabilidade horizontal (distribuir em vários servidores)

---

## Dica destacada: Portfólio

<img width="1393" height="980" alt="image" src="https://github.com/user-attachments/assets/f2ad5d5c-7e39-4ae3-9bbd-72a001fb3e1f" />

Um **portfólio** é uma vitrine dos seus **melhores trabalhos e habilidades** para mostrar o que você sabe fazer, principalmente para vagas, clientes ou faculdade.

## O que colocar 🧩
- **Sobre você** 👤: quem é, área de interesse e objetivo.
- **Habilidades** 🛠️: tecnologias, ferramentas e conhecimentos.
- **Projetos** 🚀: 3 a 6 projetos bem apresentados (descrição, prints, link e o que você fez).
- **Experiência e formação** 🎓: resumo do que é mais relevante.
- **Contato** 📩: e-mail, LinkedIn e GitHub.

## Como organizar os projetos 📌
- **Título + objetivo** do projeto
- **Tecnologias usadas** 
- **O que você desenvolveu** (sua contribuição)
- **Links**: repositório no GitHub e demo (se tiver)
- **Resultados/aprendizados** 

A aula reforça a importância de ter um portfólio de projetos web para:
- 🧠 mostrar habilidades práticas
- 📝 facilitar avaliação
- 💼 aumentar chances em estágio/emprego
- 📈 incentivar evolução contínua

---

##  Critérios de avaliação

<img width="1280" height="1280" alt="image" src="https://github.com/user-attachments/assets/ee1ad996-31e5-426a-aaa3-77c8494b9469" />

📌 Fórmula: **(P1 × 0,25) + (P2 × 0,25) + ((PJ + AT) × 0,25)**
- 📝 P1: Prova 1
- 📝 P2: Prova 2
- 🧑‍💻 PJ: Projeto
- ✅ AT: Atividades

---

Atividade (Aula 01)

<img width="740" height="740" alt="image" src="https://github.com/user-attachments/assets/6f17e2cb-3903-462e-9fdd-d51482a6a203" />

1. 👨‍👩‍👧‍👦 Formar grupos de **3 a 5 pessoas** (mesmo grupo nas semanas seguintes)
2. 💡 Elaborar propostas de projetos para apresentar ao professor
3. 🧑‍💻 Criar repositório no GitHub e fazer um **resumo em Markdown (.md)** da Aula 01
4. 🔎 Escolher **3 sites** e analisar tecnologias utilizadas; usar **Miro** para representar visualmente e salvar a imagem no repositório

---

## Referências bibliográficas
O material indica livros/temas sobre:
- 🌐 desenvolvimento web (HTML/CSS/JS/PHP)
- 🟩 Node.js e APIs / web services
- 🎨 frameworks e libs (ex.: Bootstrap/Angular)
- 🧠 práticas ágeis (ex.: Extreme Programming)
