## Docker: Utilização Prática no Cenário de Microsserviços

###  Descrição do Projeto

Este repositório foi criado como parte do desafio da DIO para aplicar os conceitos de **Docker e Microsserviços**.
O objetivo é demonstrar, de forma teórica e organizada, como seria a implementação de uma estrutura de microsserviços utilizando containers Docker para banco de dados, API e proxy reverso.

---

### 🧱 Estrutura Planejada

```
📦 docker-microservices-lab
 ┣ 📁 api/
 ┣ 📁 db/
 ┣ 📁 proxy/
 ┣ 📄 docker-compose.yml
 ┗ 📄 README.md
```

* **db/** → Container MySQL
* **api/** → Serviço Node.js ou Python simulando uma API
* **proxy/** → NGINX configurado como proxy reverso
* **docker-compose.yml** → Arquivo de orquestração dos containers

---

### ⚙️ Conceito de Funcionamento

1. O container **MySQL** armazena os dados.
2. O container **API** faz requisições e responde com as informações do banco.
3. O container **NGINX** atua como proxy reverso, direcionando o tráfego para a API.
4. O **Docker Compose** gerencia os três containers em conjunto.

---

### 🧠 Tecnologias

* Docker
* Docker Compose
* NGINX
* MySQL
* Node.js (simulação da API)

---

###  Objetivo do Desafio

Replicar e compreender um cenário de microsserviços em containerização, com foco na independência entre aplicações e infraestrutura, seguindo boas práticas do mercado de TI.

---

### ✍️ Autora

Desenvolvido por **Letícia Montenegro** 💻
Formação Cloud e DevOps | DIO

---

#### 💬 Observação

Este repositório contém a estrutura e documentação teórica do projeto, pois não foi possível executar containers por limitações de hardware. O foco está na organização, conceito e entendimento dos serviços em um ambiente de microsserviços.

---


