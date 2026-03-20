<div align="center">

<br/>

# 💳 PayCheck

**Agente inteligente de processamento de folhas de pagamento**

[![Status](https://img.shields.io/badge/status-em_desenvolvimento-yellow?style=flat-square)](#)
[![Vercel](https://img.shields.io/badge/deploy-Vercel-black?style=flat-square&logo=vercel)](https://vercel.com)
[![Claude API](https://img.shields.io/badge/AI-Claude_Sonnet_4-orange?style=flat-square)](https://anthropic.com)
[![License](https://img.shields.io/badge/license-MIT-blue?style=flat-square)](LICENSE)

<br/>

> *Transformando o processo manual de leitura de holerites em automação inteligente.*

<br/>

</div>

---

## 📌 Sobre

O **PayCheck** é um agente web que automatiza o processamento de folhas de pagamento. A contabilidade emite os holerites em PDF — o PayCheck lê, extrai e estrutura todos os dados necessários para o pagamento, sem digitação manual.

Desenvolvido com foco em equipes financeiras que lidam com alto volume de holerites mensais.

---

## ✨ Funcionalidades

- 📎 **Até 4 holerites simultâneos** — PDF, JPG ou PNG
- 🤖 **Extração automática via IA** de todos os campos:
  - Nome completo, CPF e cargo do colaborador
  - Banco, agência, conta e chave PIX
  - Salário base, comissões e descontos discriminados
  - **Valor líquido a pagar**
  - Competência e data de pagamento
- ⚠️ **Detecção de duplicatas** — alerta automático se houver parcelas repetidas
- 💬 **Resumo gerado** pronto para o time financeiro
- 📊 **Exportação em .txt** do relatório completo
- 🔒 **API segura no backend** — chave nunca exposta no browser

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| `HTML5 / CSS3` | Interface — Neobrutalism design |
| `JavaScript (Vanilla)` | Lógica de frontend |
| `Node.js` | Backend serverless (Vercel Functions) |
| `Claude API (Anthropic)` | Extração de dados via IA |
| `Vercel` | Deploy e hospedagem |

---

## 📁 Estrutura

```
paycheck-app/
├── index.html        # Frontend — interface do usuário
├── vercel.json       # Configuração do Vercel
├── package.json      # Dependências do projeto
└── api/
    └── analyze.js    # Backend — chamada segura à API
```

---

## 🚀 Rodando localmente

```bash
# Clone o repositório
git clone https://github.com/davi-anaia/paycheck-app

# Instale a Vercel CLI
npm i -g vercel

# Configure a variável de ambiente
echo "ANTHROPIC_API_KEY=sk-ant-sua-chave" > .env.local

# Rode localmente
vercel dev
```

---

## 🌐 Deploy

O projeto roda na **Vercel** com backend serverless. A chave de API fica segura nas variáveis de ambiente do servidor — nunca exposta no browser.

```
ANTHROPIC_API_KEY=sk-ant-...   # variável configurada no Vercel
```

---

## 🗺️ Roadmap

- [x] Interface Neobrutalism
- [x] Upload de PDF, JPG e PNG
- [x] Extração via Claude API
- [x] Detecção de duplicatas
- [x] Resumo automático para o financeiro
- [x] Backend seguro no Vercel
- [ ] Exportação em Excel
- [ ] Histórico de processamentos
- [ ] Autenticação de usuários

---

## 💡 Motivação

Desenvolvido para resolver um gargalo real: equipes financeiras abrindo holerite por holerite manualmente para coletar dados de pagamento. Com o PayCheck, esse processo é executado em segundos para múltiplos colaboradores simultaneamente.

---

## 👨‍💻 Autor

**Davi Anaia Pessoa**
Desenvolvedor Full Stack · Dev Trainee no GrupoAMP · Emprestimoney

[![LinkedIn](https://img.shields.io/badge/LinkedIn-davianaia-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/davianaia)
[![GitHub](https://img.shields.io/badge/GitHub-davi--anaia-black?style=flat-square&logo=github)](https://github.com/davi-anaia)
[![Portfolio](https://img.shields.io/badge/Portfolio-davi.dev-lime?style=flat-square)](https://davi-anaia.github.io/portfolio)

---

<div align="center">
<sub>Feito com ☕ e Claude AI</sub>
</div>
