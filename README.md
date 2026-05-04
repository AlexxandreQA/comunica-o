# 📌 Comunicação de Incidente - Parabank

Este repositório contém a documentação de um incidente identificado durante testes no sistema **Parabank**.

## 🐞 Descrição do problema

Durante a execução do caso de teste **CT-002 - Abertura de nova conta poupança**, foi identificado um comportamento inesperado no fluxo de criação de conta.

Após a tentativa de abertura de uma nova conta poupança, a mensagem de confirmação **“Conta aberta”** não é exibida corretamente, gerando incerteza sobre a conclusão da operação.

---

## 📂 Estrutura dos arquivos

* `bug-report-enc14.md` → Contém o relatório completo do bug (detalhes técnicos, passos, impacto, evidências e sugestão)
* `slack-message-enc14.md` → Mensagem resumida simulando comunicação rápida com o time via Slack

---

## 🧪 Caso de teste relacionado

**CT - 002 - Abertura de nova conta poupança**

**Pré-requisito:**

* Usuário já cadastrado
* Saldo mínimo de 90 euros

**Fluxo testado:**

1. Login no sistema
2. Acesso à funcionalidade "Abrir nova conta"
3. Seleção da opção de conta poupança
4. Confirmação da operação

---

## ⚠️ Impacto

* Falta de feedback claro para o usuário
* Possível retrabalho ou múltiplas tentativas
* Comprometimento da experiência do usuário

---

## 🚀 Objetivo

Demonstrar a importância da comunicação clara de incidentes, tanto de forma detalhada (bug report) quanto de forma objetiva (mensagem Slack), simulando um cenário real do dia a dia de QA.

---

## 👨‍💻 Autor

AlexandreQA
