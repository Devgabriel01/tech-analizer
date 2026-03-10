# 🔬 Tech Debt Analyzer

Uma ferramenta interativa para análise e gestão de dívida técnica em projetos de software. Desenvolvida para Tech Leads e times de desenvolvimento que precisam visualizar, priorizar e remediar débitos técnicos de forma estruturada.

![HTML](https://img.shields.io/badge/HTML-5-orange) ![CSS](https://img.shields.io/badge/CSS-3-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow) ![License](https://img.shields.io/badge/license-MIT-green)

---

## ✨ Funcionalidades

- **📋 Checklist interativo** — 31 itens organizados em 6 categorias de avaliação
- **📊 Dashboard visual** — Score global, radar chart, barras de progresso e métricas-chave
- **🗺️ Roadmap automático** — Gerado com base nos itens pendentes, dividido em 3 horizontes de tempo
- **⚡ Zero dependências** — Arquivo HTML único, roda no navegador sem instalação

---

## 🗂️ Categorias Avaliadas

| Categoria | Itens |
|---|---|
| 🏗️ Arquitetura & Design | Separação de responsabilidades, dependências circulares, ADRs... |
| 💻 Qualidade de Código | Cobertura de testes, linting, código morto, nomenclatura... |
| ⚙️ Infraestrutura & DevOps | CI/CD, ambientes, IaC, monitoramento, rollback... |
| 📦 Dependências & Segurança | Vulnerabilidades, secrets, lock files, licenças... |
| 📝 Documentação | README, OpenAPI, runbooks, onboarding... |
| 🔄 Processo & Time | Code review, Definition of Done, bus factor... |

---

## 🚀 Como usar

1. Abra o arquivo `tech-debt-analyzer.html` no seu navegador
2. Na aba **Checklist**, marque os itens que já estão resolvidos no seu projeto
3. Vá para o **Dashboard** para visualizar o diagnóstico por categoria
4. Consulte o **Roadmap** para ver o plano de remediação priorizado automaticamente

Nenhuma instalação ou servidor necessário — é só abrir o arquivo.

---

## 📊 Como o Score é calculado

O score de saúde técnica é a porcentagem de itens resolvidos sobre o total:

```
Score = (itens resolvidos / total de itens) × 100
```

| Score | Status |
|---|---|
| 75–100% | ✅ Boa saúde |
| 50–74% | ⚠️ Atenção necessária |
| 25–49% | 🔶 Alto risco |
| 0–24% | 🔴 Crítico — ação imediata |

---

## 🗺️ Horizontes do Roadmap

Os itens pendentes são priorizados por impacto e organizados em:

- **🔥 Urgente (0–30 dias)** — Itens de alto impacto e baixo esforço
- **⚡ Curto Prazo (1–3 meses)** — Melhorias importantes com esforço médio
- **🔭 Longo Prazo (3–6 meses)** — Refatorações estruturais de alto esforço

---

## 📁 Estrutura do Projeto

```
/
└── tech-debt-analyzer.html   # Aplicação completa (HTML + CSS + JS)
└── README.md                 # Este arquivo
```

---

## 🛠️ Tecnologias

- HTML5 + CSS3 + JavaScript puro (sem frameworks)
- Google Fonts — [Syne](https://fonts.google.com/specimen/Syne) + [Space Mono](https://fonts.google.com/specimen/Space+Mono)
- Canvas API para o radar chart

---

## 📄 Licença

MIT — fique à vontade para usar, adaptar e distribuir.
