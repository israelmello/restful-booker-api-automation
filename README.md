# Restful Booker API Automation

![API Tests](https://github.com/israelmello/restful-booker-api-automation/actions/workflows/api-tests.yml/badge.svg)

Projeto de automação de testes de API desenvolvido para demonstrar práticas de **QA Automation**, utilizando **Postman**, **Newman** e integração contínua através do **GitHub Actions**.

O objetivo do projeto é validar os principais fluxos da API **Restful Booker**, aplicando testes funcionais, validações de contrato, regras de negócio e execução automatizada em pipeline CI/CD.

---

## 🚀 Tecnologias utilizadas

- Postman
- Newman
- JavaScript
- REST API
- GitHub Actions
- Newman HTML Reporter
- Node.js
- Git/GitHub

---

# 📌 Cenários automatizados

## Authentication

### Criar token

Valida:

- Criação de token de autenticação
- Status code esperado
- Estrutura da resposta

---

## Booking

Fluxos automatizados:

- Criar reserva
- Consultar reserva
- Atualizar reserva
- Excluir reserva

---

# ✅ Validações implementadas

A suíte de testes possui validações como:

### HTTP

✔ Status Code  
✔ Response Time  
✔ Headers  
✔ Content-Type  

### Contrato da API

✔ Campos obrigatórios  
✔ Estrutura do JSON  
✔ Tipos de dados retornados  

### Regras de negócio

✔ Comparação entre Request e Response  
✔ Validação dos dados enviados  
✔ Validação dos dados retornados  

---

# ⚙️ Execução local

## Instalar dependências

```bash
npm install
```

## Executar testes

```bash
npm test
```

## Gerar relatório HTML

```bash
npm run report
```

Após a execução, o relatório estará disponível em:

```
reports/report.html
```

---

# 🔄 Pipeline CI/CD

O projeto possui integração com GitHub Actions.

A cada execução do workflow:

```
Push
 |
GitHub Actions
 |
Instalação das dependências
 |
Execução Newman
 |
Execução dos testes API
 |
Geração do relatório HTML
 |
Upload do Artifact
```

---

# 📊 Evidências

O pipeline gera um relatório HTML contendo:

- Resultado dos testes
- Requests executadas
- Tempo de resposta
- Status das validações

O relatório fica disponível como Artifact dentro da execução do GitHub Actions.

---

# 📂 Estrutura do projeto

```
restful-booker-api-automation/

├── .github/
│   └── workflows/
│       └── api-tests.yml

├── docs/

├── postman/
│   ├── collections/
│   └── environments/

├── reports/
│   └── report.html

├── package.json
└── README.md
```

---

# 🎯 Objetivo profissional

Este projeto demonstra conhecimentos em:

- Testes automatizados de API
- Criação de cenários de teste
- Validação de respostas HTTP
- JavaScript aplicado ao QA
- Ferramentas de automação
- Integração contínua (CI/CD)

---

## Autor

**Israel Mello**

QA Analyst | QA Automation

GitHub:
https://github.com/israelmello