# 🚀 Guia Prático de Node.js com IA (NotebookLM)

## 📌 Contexto

Este projeto foi desenvolvido com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa utilizando o NotebookLM.

O tema escolhido foi:

👉 **Node.js aplicado na construção de APIs REST**

A ideia foi utilizar IA não apenas para obter respostas, mas como suporte para:
- Estruturar conhecimento
- Validar conceitos
- Simular cenários reais de desenvolvimento

---

## 🎯 Objetivos

- Consolidar conhecimentos em Node.js voltado para backend
- Entender a criação e estruturação de APIs REST
- Aprender boas práticas utilizadas no mercado
- Desenvolver habilidade de engenharia de prompts
- Criar um material reutilizável para estudos futuros

---

## 📚 Curadoria de Fontes

As seguintes fontes foram utilizadas no NotebookLM:

1. https://nodejs.org/en/docs  
2. https://expressjs.com/  
3. https://developer.mozilla.org/pt-BR/docs/Web/HTTP/Methods  
4. https://restfulapi.net/  
5. https://www.freecodecamp.org/news/nodejs-api-tutorial/

---

## 🤖 Engenharia de Prompts

### 🔹 Prompt 1 – Introdução ao Node.js

Explique o que é Node.js e como ele funciona no backend

### 🔹 Prompt 2 – Estrutura de API

Como estruturar uma API REST em Node.js usando Express?

### 🔹 Prompt 3 – Erros comuns

Quais são os erros mais comuns ao criar APIs REST em Node.js?

### 🔹 Prompt 4 – Projeto prático

Crie uma API REST completa em Node.js com Express

---

## ⚠️ Cicatrizes

- Prompts genéricos geram respostas superficiais  
- Especificar contexto melhora o resultado  
- Pedir exemplos de código é essencial  

---

## 📘 Miniguia de Estudo

### 🧠 Resumo

Node.js é um ambiente de execução JavaScript no servidor, ideal para APIs REST devido ao seu modelo assíncrono.

---

### ⚙️ Exemplo

```js
const express = require('express');
const app = express();

app.use(express.json());

app.get('/', (req, res) => {
  res.send('API rodando');
});

app.listen(3000);
```

---

## 👨‍💻 Autor

Bruno Mota
