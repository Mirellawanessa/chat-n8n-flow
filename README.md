# 🎯 Projeto n8n: Agente de Chat com Registro no Google Sheets

### 🔗 Acesso ao Agente  
[👉 Acesse aqui o chatbot](https://mirellawanessa.app.n8n.cloud/webhook/fd79a997-d21f-4621-84d2-70d5458ddafb/chat)

---

## 🧠 Objetivo

Automatizar o recebimento de mensagens de chat, registrar essas mensagens em uma planilha no Google Sheets e utilizar um agente de IA para respostas inteligentes e contextuais.

---

## 🖼️ Visão Geral do Fluxo no n8n

> **Imagem do fluxo:**  
> ![Fluxo n8n](CAMINHO_DA_IMAGEM)

---

## 🔄 Etapas do Fluxo

### 1. **📩 When Chat Message Received**
- Webhook que captura mensagens enviadas pelos usuários.

### 2. **✏️ Edit Fields**
- Ajusta/transforma os campos recebidos (ex: timestamp, texto limpo).

### 3. **📊 Google Sheets**
- Conexão com uma planilha para registro das interações.
- Modo: `append: sheet`.

### 4. **🤖 AI Agent**
- Agente de IA com ferramentas integradas:
  - **Groq Chat Model:** LLM para gerar respostas.
  - **Simple Memory:** memória contextual de conversas.
  - **Wikipedia + Calculadora:** ferramentas auxiliares para enriquecer as respostas.

### 5. **⛔ No Operation, Do Nothing**
- Finaliza o fluxo sem ação adicional.

---

## 📁 Armazenamento

- As interações são registradas em tempo real no Google Sheets.
- Permite auditoria, análise de dados e geração de relatórios.

---

## 🌐 Tecnologias Utilizadas

- **n8n:** Plataforma de automações.
- **Webhook:** Para receber dados em tempo real.
- **Google Sheets API:** Para armazenamento.
- **LLM (Groq):** Respostas com IA.
- **Memória e Ferramentas externas:** Para contexto e suporte.

---

## ✅ Benefícios

- Automação 100%.
- Fácil expansão e personalização.
- Histórico completo de conversas.
- Suporte à IA e ferramentas externas.

---

## 👩‍💻 Desenvolvedora

<p>
  <img 
    align="left" 
    width="80" 
    src="https://github.com/Mirellawanessa/DIO-Trilha-Java-Basico/blob/main/GitHub/imagens/User.jpeg?raw=true"
  />
  <p>&nbsp;&nbsp;&nbsp;Mirella Wanessa<br>
  &nbsp;&nbsp;&nbsp;
  <a href="https://github.com/Mirellawanessa">GitHub</a>&nbsp;|&nbsp;
  <a href="https://www.linkedin.com/in/mirellawanessa/">LinkedIn</a>&nbsp;|&nbsp;
  <a href="https://www.instagram.com/itsmirella._/">Instagram</a>
  &nbsp;|&nbsp;</p>
</p>

---

⌨️ with 💜 by [Mirella Wanessa](https://github.com/Mirellawanessa)


