# 📊 Gestão de Eventos – ONG Vida Plena

Projeto acadêmico desenvolvido para a disciplina **Banco de Dados Visuais e Ferramentas Integradas**, com foco na criação de um banco de dados visual integrado a uma automação No-Code.

---

## 📌 Visão Geral

Este projeto tem como objetivo criar um sistema simples, funcional e escalável para o gerenciamento de eventos sociais promovidos por uma ONG fictícia chamada **Vida Plena**.

A solução foi construída utilizando ferramentas No-Code, permitindo o cadastro de beneficiários, eventos e inscrições por meio de formulário web público, além da automação de processos operacionais através da plataforma Make.

---

## 🎯 Objetivos do Projeto

- Centralizar dados de beneficiários e eventos
- Substituir planilhas manuais por um banco de dados visual
- Permitir inscrições em eventos por meio de formulário online
- Automatizar o envio de confirmação de inscrição
- Demonstrar integração entre banco de dados visual e ferramentas externas
- Aplicar conceitos de modelagem relacional e automação

---

## 🧠 Problema Abordado

A ONG Vida Plena enfrentava dificuldades como:

- Dados espalhados em planilhas
- Falta de histórico de inscrições
- Processo manual para controle de participantes
- Ausência de automações

O projeto resolve esses problemas ao criar uma estrutura centralizada, visual e automatizada.

---

## 🧱 Estrutura do Banco de Dados

O banco de dados foi modelado de forma relacional e visual, contendo três tabelas principais:

### 📘 Beneficiários
- Nome do Beneficiário
- Idade
- Email do Beneficiário
- Região
- Data de Cadastro (Created Time)

### 📕 Eventos
- Nome do Evento
- Data do Evento
- Local
- Descrição
- Data de Criação (Created Time)

### 📗 Inscrições
- Beneficiário (relacionamento)
- Evento (relacionamento)
- Data da Inscrição
- Criado em (Created Time)

A tabela **Inscrições** resolve o relacionamento **muitos-para-muitos (N:N)** entre beneficiários e eventos.

---

## 📝 Formulário Web

Foi criado um formulário público no Airtable que permite que qualquer pessoa realize a inscrição em um evento de forma online.

### Campos do formulário:
- Beneficiário
- Evento
- Data da Inscrição

O formulário gera automaticamente registros na tabela Inscrições, servindo como ponto de entrada de dados para a automação.

---

## ⚙️ Automação com Make

A automação foi desenvolvida utilizando a ferramenta **Make**, com o seguinte fluxo:

1. Monitoramento de novos registros na tabela Inscrições
2. Identificação do beneficiário inscrito
3. Recuperação dos dados do evento
4. Envio automático de e-mail de confirmação

### Benefícios da automação:
- Redução de trabalho manual
- Resposta imediata ao usuário
- Padronização da comunicação
- Integração entre sistemas

---

## 🔐 Segurança e Ética da Informação

- Utilização de dados fictícios para testes
- Controle de acesso à base no Airtable
- Permissões limitadas para integração externa
- Respeito à privacidade e boas práticas de tratamento de dados

---

## 🚀 Tecnologias Utilizadas

- **Airtable** – Banco de dados visual
- **Make** – Automação e integração
- **Formulário Web** – Entrada de dados online
- **GitHub** – Versionamento e documentação

---

## 📈 Resultados Alcançados

- Sistema funcional e integrado
- Banco de dados visual estruturado
- Automação real em funcionamento
- Inscrições online com confirmação automática
- Projeto pronto para uso acadêmico e expansão futura

---

## 📚 Contexto Acadêmico

Projeto desenvolvido como parte da avaliação da disciplina:

**Banco de Dados Visuais e Ferramentas Integradas**

---

## ✨ Considerações Finais

O projeto demonstra a aplicação prática de conceitos de banco de dados, modelagem relacional e automação, utilizando ferramentas No-Code modernas e acessíveis. A solução é escalável, de fácil manutenção e atende às necessidades propostas no desafio acadêmico.

---

## 👤 Autor

Projeto desenvolvido por:

**Marcos Detrano Rodrigues Junior**

