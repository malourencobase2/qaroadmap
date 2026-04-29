# 🧪 Base2 QA Engineer Roadmap

> **Idealizado pelo Time de Arquitetura da Base2 Tecnologia**  
> Um guia completo e interativo para evoluir sua carreira em Qualidade de Software — de Júnior a Sênior.

---

## 📖 Sobre o projeto

Este roadmap foi construído com o objetivo de auxiliar profissionais de QA a evoluírem em suas carreiras, pensando nas melhores práticas do mercado. É um documento HTML standalone — sem dependências externas de servidor — que pode ser aberto diretamente no browser ou hospedado em qualquer serviço de páginas estáticas (GitHub Pages, Netlify, Vercel).

O conteúdo é baseado no [roadmap.sh/qa](https://roadmap.sh/qa) e foi significativamente expandido e adaptado pelo Time de Arquitetura da Base2, com foco na realidade do mercado brasileiro.

---

## 🔐 Acesso

O roadmap possui autenticação por e-mail corporativo. Ao acessar, é necessário informar um e-mail com domínio `@base2.com.br`. A sessão é mantida por **7 dias** via `sessionStorage`.

---

## 🗂️ Estrutura do Roadmap

O roadmap é dividido em **3 trilhas independentes**, cada uma com conteúdo, laboratórios e recursos específicos para o nível:

### 🟢 Trilha Júnior — Fundamentos
Para quem está começando. Sem pré-requisitos técnicos, com foco em construir a base sólida.

**9 módulos · 25+ exercícios · 15+ recursos · 4 labs guiados**

| Módulo | Conteúdo |
|--------|----------|
| O que é QA? | Mindset, verificação vs. validação, pirâmide de testes |
| Tipos e Abordagens de Teste | Caixa preta, caixa branca, caixa cinza |
| Testes Manuais | Casos de teste, DevTools, compatibilidade de browsers |
| Metodologias Ágeis | Scrum, critérios de aceitação, BDD |
| Técnicas de Teste | Partição de equivalência, análise de valor limite |
| Git e Versionamento | Comandos essenciais, GitHub para QA |
| Teste Exploratório | Charter, heurísticas, sessões guiadas |
| Gestão de Bugs | Jira, MeloQA, anatomia de um bug report |
| SQL para QA | Validação de dados no banco, massa de dados |
| HTTP para QA | Status codes, métodos, headers, autenticação |
| Portfólio e Carreira | GitHub, certificações, comunidade |
| Intro à Automação | Primeiros passos com automação de testes |
| 🧠 Mentalidade QA | Papel no time, qualidade desde a análise |

### 🟠 Trilha Pleno — Automação
Para quem já tem a base e quer dominar automação, APIs e CI/CD.

**12 módulos · 35+ exercícios · 20+ recursos · 9 labs com código**

| Módulo | Conteúdo |
|--------|----------|
| Automação | Cypress, Playwright, Selenium WebDriver |
| Tipos de Teste | Smoke, regressão, testes de componente |
| Estratégias de Teste | Técnicas avançadas e pirâmide de automação |
| Acessibilidade | WCAG 2.1, axe-core, testes com leitor de tela |
| CI/CD e Pipelines | GitHub Actions, Docker headless, relatórios |
| TestRail e Gestão | Ciclos de teste, planos, MeloQA |
| Monitoramento | Allure Reports, Grafana, Sentry |
| IA para Produtividade | LLMs, Applitools, GitHub Copilot |
| Feature Flags | LaunchDarkly, Unleash, canary releases |
| Secrets e Ambientes | .env, GitHub Secrets, múltiplos ambientes |
| 🧠 Mentalidade QA | Shift-left, pipeline de qualidade, observabilidade |

### 🟣 Trilha Sênior — Arquitetura
Para QAs experientes que querem impactar estratégia, escala e liderança.

**14 módulos · 35+ exercícios · 20+ recursos · 8 labs avançados**

| Módulo | Conteúdo |
|--------|----------|
| Arquitetura de Testes | Métricas, gestão de risco, TDD/BDD avançado |
| Performance e Carga | K6, estratégia de SLOs, análise de gargalos |
| Segurança | OWASP Top 10, SAST/DAST, security no pipeline |
| Mobile Avançado | Appium avançado, Detox, cloud device testing |
| Observabilidade | Prometheus, Grafana, SLOs, root cause analysis |
| IA e Agentes | Self-healing, agentes autônomos, AI Red Teaming |
| Liderança Técnica | Mentoria, certificações, comunicação com stakeholders |
| SAFe e Escala | Qualidade em múltiplos times, DevOps, XP |
| Qualidade no SDLC | Three Amigos, design for testability, shift-right |
| Chaos Engineering | Litmus, Game Days, chaos no CI/CD |
| TestOps e QAOps | Ambientes efêmeros, TDM, sharding |
| Compliance e Regulatório | LGPD, PCI-DSS, audit trail |
| Microsserviços e Eventos | Kafka, Testcontainers, distributed tracing |
| Data Literacy | Pareto de defeitos, dashboards, predictive analytics |
| Quality Engineering | QE vs. QA, DORA metrics, influência sem autoridade |
| FinOps de Testes | Custo de CI, otimização de pipeline, ROI |
| 🧠 Mentalidade QA | Cultura de qualidade, qualidade de ponta a ponta |

---

## 📊 Números do Roadmap

| Indicador | Total |
|-----------|-------|
| Trilhas | 3 |
| Módulos (conteúdo) | 38 |
| Laboratórios práticos | 135 |
| Links de recursos | 464 |
| Artigos referenciados | 147 |
| Recursos em 🇧🇷 português | 194+ |

---

## 🚀 Como usar

Acesse: https://malourencobase2.github.io/qaroadmap/

> ⚠️ O acesso requer e-mail com domínio `@base2.com.br`.

---

## 🧩 Funcionalidades

- **Tela de login** com autenticação por e-mail corporativo (`@base2.com.br`), sessão de 7 dias
- **Página inicial interativa** com seleção de trilha por nível
- **Sidebar dinâmica** que muda conforme a trilha escolhida
- **Topbar** com botão de retorno ao início e indicador do nível atual
- **Navegação suave** entre módulos com scroll automático
- **Tabs de automação** para alternar entre frameworks (ex.: Cypress, Playwright, Selenium)
- **Responsivo** para mobile e desktop
- **Standalone** — um único arquivo HTML sem dependências externas de servidor

---

## 🛠️ Tecnologias

O roadmap é um arquivo HTML único (`index.html`) sem dependências externas de servidor. Utiliza:

- **HTML5 + CSS3** — layout com CSS Grid e Flexbox
- **JavaScript vanilla** — navegação entre seções, trilhas e autenticação
- **Google Fonts** — Sora (títulos) e Inter (corpo), carregadas via CDN
- **sessionStorage** — controle de sessão de autenticação (7 dias)

---

## 📚 Referências e Inspirações

- [roadmap.sh/qa](https://roadmap.sh/qa) — estrutura base do roadmap
- [BSTQB](https://bstqb.org.br) — certificações e syllabus em português
- [Ministry of Testing](https://www.ministryoftesting.com) — comunidade global de QA
- [Test Automation University](https://testautomationu.applitools.com) — cursos gratuitos
- [MeloQA](https://www.meloqa.com) — plataforma brasileira de gestão de testes
- [Iterasys](https://www.youtube.com/@IterasysEscola) — conteúdo em português

---

## 🤝 Contribuindo

Este roadmap é um documento vivo. Sugestões de conteúdo, correções e melhorias são bem-vindas:

1. Abra uma **Issue** descrevendo a sugestão ou problema
2. Faça um **Fork** e envie um **Pull Request** com a melhoria
3. Para sugestões de novos módulos, descreva: público-alvo, conteúdo proposto e por que é relevante para o mercado brasileiro

---

## 📄 Licença

Este projeto foi desenvolvido pelo **Time de Arquitetura da Base2 Tecnologia** e é disponibilizado para uso interno e pela comunidade de QA.

---

<div align="center">
  <strong>Base2 Tecnologia</strong> · Qualidade que destrava o crescimento.<br>
  <a href="https://www.base2.com.br">base2.com.br</a>
</div>
