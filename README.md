# 📝 Estúdio Markdown — Visualizador e Editor (React)

<p align="center">
  <img src="https://i.postimg.cc/13Kw5f8L/Chat-GPT-Image-16-de-nov-de-2025-15-31-25.png" width="520" alt="Mockup Estúdio Markdown (desktop + mobile)">
</p>

**Estúdio Markdown** é um visualizador e editor online de Markdown construído em **React**. A aplicação oferece edição ao vivo, exportação para PDF, cópia do HTML e uma interface responsiva que funciona tanto no desktop quanto no celular.

🔗 **Demo (GitHub Pages):**  
👉 [Abrir Estúdio Markdown](https://nataliapastre-dev.github.io/markdown-viewer/)

---

## ✨ Funcionalidades

- Editor de Markdown com visualização em tempo real (duas colunas: código e renderizado)  
- Botão para **tema escuro / claro** (toggle)  
- **Copiar HTML** gerado a partir do Markdown  
- **Exportar PDF** (via jsPDF + autotable)  
- Integração com **remark-gfm** (suporte a tabelas, task lists, links automáticos)  
- UI responsiva: layout adaptado para desktop e mobile  
- Feedback ao usuário com alertas (SweetAlert2)

---

## 🚀 Tecnologias usadas

- **React** (Create React App / react-scripts)  
- **react-markdown** (para renderizar Markdown)  
- **remark-gfm** (extensões GitHub Flavored Markdown)  
- **jsPDF** + **jspdf-autotable** (exportar PDF)  
- **SweetAlert2** (alertas bonitos)  
- **gh-pages** (deploy no GitHub Pages)

---

## 📦 Instalação e execução local

> Pré-requisitos: Node.js e npm instalados.

```bash
# clonar o repositório
git clone https://github.com/nataliapastre-dev/markdown-viewer.git

# entrar na pasta do projeto
cd markdown-viewer

# instalar dependências
npm install

# rodar em modo de desenvolvimento
npm start
