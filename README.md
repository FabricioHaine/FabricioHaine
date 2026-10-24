<div align="center">
  <img src="assets/banner.png" width="100%" alt="Fabricio Haine — Full Stack · Java 21 · Spring Boot · Angular 20" />

  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=18&pause=1300&color=8293FF&center=true&vCenter=true&width=660&lines=Java+21+%C2%B7+Spring+Boot+3.5+%C2%B7+Angular+20;Regras+no+backend%2C+testes+de+verdade;PostgreSQL+%2B+Flyway+%C2%B7+design+system+autoral" alt="Java 21 · Spring Boot 3.5 · Angular 20" />

  [Sobre mim](#-sobre-mim) · [Stack e ferramentas](#-stack-e-ferramentas) · [Projetos](#-projetos-em-destaque) · [Em andamento](#-em-andamento) · [Estatísticas](#-estatísticas) · [Contato](#-vamos-nos-conectar)
</div>

---

> **Tela bonita que mente não é produto — é maquete.**
> Meus repositórios existem para provar o contrário: regras no backend, testes de verdade e acabamento de interface.

## 👤 Sobre mim

Sou **Fabricio Haine**, estudante de tecnologia com um interesse que atravessa tudo que eu construo: **resolver problemas reais** — unindo lógica de programação, boas práticas de engenharia e visão de negócio. Gosto de sair do tutorial e chegar no produto: algo que alguém abre, testa, erra e continua usando.

Nos meus projetos, o princípio que me guia é que **a verdade mora no backend**: autorização decidida no servidor (nunca "escondida" no front), histórico com o ator autenticado, indicadores nascidos de consultas — e nenhum dado mockado fazendo cena. O acabamento acompanha esse rigor: estados de carregamento, erro e vazio tratados de verdade, confirmação consciente para ações destrutivas e suítes cobrindo regra e fluxo — unitário, integração e smoke test.

Também cuido do que se vê. Cada projeto tem um **design system autoral em tema dark**: os tokens `--ft-*` do FlowTask, o `Midnight` do FinanSight, o teal do DocuMind — com tipografia Inter, espaçamento consistente e a mesma voz visual de produto em todos os repositórios. Do outro lado da linha, **Python** aparece em estudos, automação e scripts de verificação.

Hoje a base é **Java 21 + Spring Boot** no backend e **Angular 20** no frontend, sobre **PostgreSQL** versionado por **Flyway**. Prefiro profundidade a amplitude: melhor um recurso sólido, testado e honesto do que dez telas de vitrine.

<details>
<summary>🇺🇸 <b>About me (English)</b></summary>

Hi! I'm **Fabricio Haine**, a technology student building real full-stack products — Java 21 + Spring Boot on the backend, Angular 20 on the frontend, with PostgreSQL versioned by Flyway. My rule of thumb: **the truth lives in the backend** — permissions decided on the server, no mocked data, honest loading/empty/error states, and tests covering both rules and flows. I also care about the product feel: authorial dark design systems built on design tokens, Inter typography and a consistent visual voice across my repositories.

</details>

## 🧰 Stack e ferramentas

**Linguagens e base web:**

![Java](https://img.shields.io/badge/Java-21-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend e dados:**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-JWT-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16%2B-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-Migra%C3%A7%C3%B5es-CC0202?style=for-the-badge)

**Frontend e qualidade:**

![Angular](https://img.shields.io/badge/Angular-20-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![PrimeNG](https://img.shields.io/badge/PrimeNG-20-0F172A?style=for-the-badge&logo=primeng&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-Visualiza%C3%A7%C3%B5es-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![JUnit 5](https://img.shields.io/badge/JUnit%205-25DC32?style=for-the-badge)
![Swagger](https://img.shields.io/badge/Swagger-OpenAPI-85EA2D?style=for-the-badge&logo=swagger&logoColor=black)

**Ferramentas:**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-CI-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Multi--stage-2496ED?style=for-the-badge&logo=docker&logoColor=white)

## 🚀 Projetos em destaque

| Projeto | O que é |
|---|---|
| **[documind](https://github.com/FabricioHaine/documind)** | Plataforma de inteligência de documentos com **RAG 100% local** — busca vetorial real com `pgvector` + índice HNSW, embeddings do `nomic-embed-text` via Ollama e **citações construídas pelo backend** a partir dos trechos efetivamente recuperados. Sem evidência suficiente, a resposta admite que não encontrou. |
| **[flowtask](https://github.com/FabricioHaine/flowtask)** | Gestão de projetos com **quadro Kanban colaborativo** e papéis OWNER/MANAGER/MEMBER decididos no backend (`404`/`403`). Drag & drop com rollback otimista, concorrência protegida por `SELECT … FOR UPDATE` + `@Version` → `409` e exclusão de projeto em cascata transacional, liberada só ao OWNER que **digitar o nome do projeto**. 54 rotas em 11 controllers, 11 tabelas e 72 testes + 42 verificações de fumaça. |
| **[FinanSight](https://github.com/FabricioHaine/FinanSight)** | **SaaS de finanças pessoais** com indicadores calculados no servidor, orçamentos, metas e exportação CSV em pt-BR — sob o design system `Midnight`, um tema dark autoral com tipografia Inter e gráficos Chart.js. |
| **[nexus-crm](https://github.com/FabricioHaine/nexus-crm)** | **CRM** de clientes e oportunidades com funil comercial e papéis ADMIN/GERENTE/VENDEDOR. Sessão por **JWT em cookie HttpOnly + CSRF de dupla submissão com rotação de token**, Docker multi-stage e **CI no GitHub Actions** — 98 verificações entre unidade, integração e fumaça. |

## 🚧 Em andamento

- **CI nos projetos principais** — pipeline no GitHub Actions rodando `mvn test` e `ng test` a cada push (o padrão já vive no nexus-crm; levar aos demais)
- **Docker completo** — Dockerfile da aplicação + `compose` com backend, frontend e banco (hoje o compose cobre só o PostgreSQL)
- **E2E de navegador** — Playwright nos fluxos críticos do Kanban: arrastar cartão, convites e exclusão com confirmação textual
- **E-mail transacional** — SMTP real para convites e notificações, além da recuperação de senha

## 📊 Estatísticas

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=FabricioHaine&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=080E19&title_color=8293FF&icon_color=A5B4FC&text_color=C9D1D9" />
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=FabricioHaine&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=FFFFFF&title_color=111C2E&icon_color=5B6BE0&text_color=1F2937" alt="Estatísticas FabricioHaine" />
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs?username=FabricioHaine&layout=compact&langs_count=6&hide_border=true&bg_color=080E19&title_color=8293FF&text_color=C9D1D9" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs?username=FabricioHaine&layout=compact&langs_count=6&hide_border=true&bg_color=FFFFFF&title_color=111C2E&text_color=1F2937" alt="Linguagens mais usadas" />
</picture>

<br /><br />

<img height="185" src="https://streak-stats.demolab.com?user=FabricioHaine&hide_border=true&background=080E19&stroke=26354B&ring=8293FF&fire=A5B4FC&currStreakNum=E8EDF7&currStreakLabel=8293FF&sideNums=C9D1D9&sideLabels=96A4BA&dates=96A4BA" alt="Sequência de contribuições" />

<br /><br />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FabricioHaine/FabricioHaine/output/github-contribution-grid-snake-dark.svg" />
  <img width="100%" src="https://raw.githubusercontent.com/FabricioHaine/FabricioHaine/output/github-contribution-grid-snake.svg" alt="Snake das contribuições" />
</picture>

</div>

## 📫 Vamos nos conectar?

<p align="center">
  <b>Aberto para conversar sobre backend, produto e engenharia de software.</b><br /><br />
  <a href="https://www.linkedin.com/in/fabricio-haine-1423923a5/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=FabricioHaine&style=for-the-badge&color=8293FF&label=VISITANTES" alt="Contador de visitas ao perfil" />
  <br /><sub>Do problema real ao produto que não finge funcionar.</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:080E19,100:5B6BE0&height=110&section=footer" width="100%" alt="" />
