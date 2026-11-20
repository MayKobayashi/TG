# TG — Ciência de Dados para Negócios

**Autora:** Stefanie Mayumi Inacio Kobayashi Resende
**Curso:** Tecnologia em Ciência de Dados para Negócios, Fatec Votorantim
**Semestre:** 6º (2026/2)
**Orientação:** Prof. Dr. Hélio Rubens Jacintho Pereira Junior e Profa. Dra. Rosana Helena Nunes

---

## Título

> **Da Estratégia ao Impacto: Uma Jornada de Ciência de Dados Orientada a Valor Social e de Negócios**

Este Trabalho de Graduação é um **Portfólio Integrador**. Ele reúne os seis Projetos Integradores do curso e mostra como as competências foram se somando, do entendimento de negócio à implantação de soluções analíticas com impacto social.

📄 **Versão final:** [`TG_Stefanie_Mayumi_Inacio_Kobayashi_Resende.pdf`](01_Documento_ABNT/TG_Stefanie_Mayumi_Inacio_Kobayashi_Resende.pdf)

---

## Estrutura de Pastas

```
TG/
├── 01_Documento_ABNT/
│   ├── TG_Stefanie_Mayumi_Inacio_Kobayashi_Resende.pdf  ← versão final do TG
│   └── figuras/                 ← as 8 figuras do TG (Figura01 a Figura08)
├── 02_Evidencias_PI/
│   ├── PI1_Negocios/            ← Easy Cooking: relatório, pitch deck e apresentação
│   ├── PI2_Visualizacao/        ← Easy Cooking: relatório e apresentação (BI)
│   ├── PI3_Analise_I/           ← PGA × RAA Fatec: relatório e apresentação
│   ├── PI4_Analise_II/          ← Violência contra a mulher (DDM): relatório, guia e scripts
│   ├── PI5_Projetos_I/          ← Hotspots preditivos (DDM): relatório, guias e figuras
│   └── PI6_Projetos_II/         ← Classificação histórica por zona: relatório, guias e figuras
├── 03_Projetos_Extras/
│   └── certificados/            ← cursos e eventos de 2024 em diante
├── 04_Apresentacao_Banca/       ← slides da defesa
└── Manual_TG_CDN_v1-3_revisada.pdf  ← manual do TG do curso
```

Os arquivos seguem o padrão `PI<n>_<Tipo>` (ex.: `PI5_Relatorio.pdf`, `PI6_Guia_de_Uso.pdf`).

---

## Matriz de Evidências do Portfólio (MEP)

| PI | Semestre | Tema | Contexto | Tecnologias | Evidências | O que comprova |
|----|----------|------|----------|-------------|------------|----------------|
| PI1 | 1º (2024/1) | Compreensão do Negócio | Easy Cooking (projeto próprio) | Design Thinking, Canvas (Canva) | [`PI1_Negocios/`](02_Evidencias_PI/PI1_Negocios/) | Análise de stakeholders, Canvas da Proposta de Valor, mapeamento de dores do cliente |
| PI2 | 2º (2024/2) | Visualização de Dados | Easy Cooking (projeto próprio) | Power BI | [`PI2_Visualizacao/`](02_Evidencias_PI/PI2_Visualizacao/) | Dashboard e análise visual para decisão |
| PI3 | 3º (2025/1) | Análise de Dados I | Fatec Votorantim | Python, Figma, proposta de ETL | [`PI3_Analise_I/`](02_Evidencias_PI/PI3_Analise_I/) | Análise PGA × RAA, proposta de ETL, painel de gestão |
| PI4 | 4º (2025/2) | Análise de Dados II | DDM Sorocaba e Votorantim / SSP-SP | Python, Google BigQuery, Looker Studio | [`PI4_Analise_II/`](02_Evidencias_PI/PI4_Analise_II/) | Pipeline ETL, data warehouse, dashboard operacional |
| PI5 | 5º (2026/1) | Projetos em Ciência de Dados I | DDM Sorocaba e Votorantim / SSP-SP | Python, XGBoost, Streamlit, Google BigQuery | [`PI5_Projetos_I/`](02_Evidencias_PI/PI5_Projetos_I/) | Pipeline preditivo de ponta a ponta, app web em produção |
| PI6 | 6º (2026/2) | Projetos em Ciência de Dados II | Sorocaba / SSP-SP, Censo 2022, SEADE | Databricks, Delta Lake, MLflow, Databricks Apps | [`PI6_Projetos_II/`](02_Evidencias_PI/PI6_Projetos_II/) | Classificação histórica por zona, validação estatística, LGPD |

---

## Evidências por PI

### PI1 — Compreensão do Negócio

💻 Repositório: [github.com/MayKobayashi/PI1-Easy-Cooking](https://github.com/MayKobayashi/PI1-Easy-Cooking)

- `PI1_Relatorio.pdf`: relatório final do projeto
- `PI1_Pitch_Deck.pdf`: proposta de valor
- `PI1_Apresentacao.pdf`: apresentação do semestre

### PI2 — Visualização de Dados

💻 Repositório: [github.com/MayKobayashi/PI2-Easy-Cooking-Dashboards](https://github.com/MayKobayashi/PI2-Easy-Cooking-Dashboards)

- `PI2_Relatorio.pdf`: relatório com dashboards e análises
- `PI2_Apresentacao.pdf`: apresentação final

### PI3 — Análise de Dados I

💻 Repositório: [github.com/MayKobayashi/PI3-Automacao-PGA-RAA](https://github.com/MayKobayashi/PI3-Automacao-PGA-RAA)

- `PI3_Relatorio.pdf`: análise PGA × RAA 2024 da Fatec Votorantim e proposta de ETL
- `PI3_Apresentacao.pdf`: apresentação dos resultados

### PI4 — Análise de Dados II

💻 Repositório: [github.com/MayKobayashi/PI4-Violencia-Mulher-DDM](https://github.com/MayKobayashi/PI4-Violencia-Mulher-DDM)

- `PI4_Relatorio.pdf`: relatório técnico
- `PI4_Apresentacao.pdf`: apresentação dos resultados
- `PI4_Guia_de_Uso.pdf`: manual do dashboard para gestores
- `PI4_One_Pager.pdf`: síntese executiva
- `PI4_Video_Pitch.txt`: link do vídeo de pitch
- `scripts/`: `PI4_script_ddm.py` e `PI4_script_produtividade.py`

### PI5 — Projetos em Ciência de Dados I

💻 Repositório: [github.com/MayKobayashi/PI5-Hotspots-Violencia](https://github.com/MayKobayashi/PI5-Hotspots-Violencia)

- `PI5_Kick_off.pdf`: apresentação de kick-off
- `PI5_Relatorio.pdf`: relatório técnico-científico
- `PI5_Apresentacao.pdf`: slides da defesa
- `PI5_Guia_de_Uso.pdf`: manual da aplicação web
- `PI5_Deploy_Guide.pdf`: hospedagem e implantação
- Figuras: `PI5_app_preview.png`, `PI5_top15_bairros.png`, `PI5_heatmap_mes_periodo.png`, `PI5_features_temporais.png`, `PI5_importancia_features.png`, `PI5_comparacao_modelos.png`, `PI5_arvore_decisao.png`

O formulário inicial, as atas de reunião e o termo de cooperação institucional foram assinados, mas não estão neste repositório porque contêm dados pessoais.

🌐 App: [pifatec.useconectai.com.br](https://pifatec.useconectai.com.br/)

### PI6 — Projetos em Ciência de Dados II

💻 Repositório: [github.com/MayKobayashi/PI6-Classificacao-Violencia](https://github.com/MayKobayashi/PI6-Classificacao-Violencia)

- `PI6_Relatorio.pdf`: relatório final
- `PI6_Apresentacao.pdf`: slides da banca
- `PI6_Guia_de_Uso.pdf`: manual do aplicativo
- `PI6_Deploy_Guide.pdf`: implantação no Databricks
- `PI6_01` a `PI6_06`: figuras do relatório (pipeline no Databricks)
- `PI6_07` a `PI6_10`: telas do aplicativo no Databricks Apps

---

## Formação Complementar e Projetos Extras

### Certificados

Em [`03_Projetos_Extras/certificados/`](03_Projetos_Extras/certificados/), nomeados por `ano-mês - instituição - curso`:

| Data | Instituição | Curso / evento |
|------|-------------|----------------|
| 2025-05 | Udemy | Yellow Belt Lean Seis Sigma: Fundamentos Essenciais (4h) |
| 2025-08 | Prefeitura de Tapiraí e Agência Inova | Hackathon Tapiraí (50h) |
| 2025-10 | Aspire Institute | Aspire Leaders Program (40h) e carta de reconhecimento |
| 2025-12 | DIO | Módulo IA e Arquitetura de Dados (9h) |
| 2025-12 | DIO e Microsoft | Aceleração IA e Arquitetura de Dados (6h) |
| 2025-12 | DIO | Mentoria Arquitetura Unificada de Dados com Microsoft Fabric e Power BI (2h) |
| 2026-04 | USP ESALQ | Introdução ao Machine Learning com Python |
| 2026-05 | Stanford University | Code in Place (Python) |
| 2026-05 | Fatec | Comunicação Oral no I Simpósio de Ciência de Dados das Fatecs |
| 2026-06 | PycodeBR | Imersão IA Builders: Workflow de Desenvolvimento com IA Assistida (6h) |
| 2026-08 | Aspire Institute | Leadership Accelerator Powered by AI (LAPA) |
| 2026-09 | USP ESALQ | Liderança 5.0: IA e Habilidades Humanas na Gestão de Equipes |

### Projetos pessoais

- 💻 [radar-de-vagas](https://github.com/MayKobayashi/radar-de-vagas): agente agendado com Claude que busca vagas, avalia a aderência ao perfil e envia um resumo com currículo adaptado
- 💻 [transcricao-de-aulas](https://github.com/MayKobayashi/transcricao-de-aulas): gravação, transcrição local com whisper.cpp e resumo de aulas com IA
- 🌐 [Além do Dataset](https://alemdodataset.com.br): canal de divulgação sobre dados e tecnologia
- 🌐 [Portfólio pessoal](https://maykobayashi.github.io)

---

## Perfil

**Stefanie Mayumi Inacio Kobayashi Resende**
Coordenadora de Dados e BI | Cientista de Dados em formação

- Atuação em startup de tecnologia, com foco em Business Intelligence e arquitetura de dados
- Portfólio: [maykobayashi.github.io](https://maykobayashi.github.io)

`Python` · `SQL` · `Google BigQuery` · `Databricks` · `Looker Studio` · `Power BI` · `ETL` · `Machine Learning` · `Design Thinking`

---

*Última atualização: novembro de 2026, 6º semestre (versão final do TG)*
