# TG — Ciência de Dados para Negócios

**Autora:** Stefanie Mayumi Inacio Kobayashi Resende
**Curso:** Tecnologia em Ciência de Dados para Negócios, Fatec Votorantim
**Semestre:** 6º (2026/2)
**Orientação:** Prof. Dr. Hélio Rubens Jacintho Pereira Junior e Profa. Dra. Rosana Helena Nunes

---

## Título

> **Da Estratégia ao Impacto: Uma Jornada de Ciência de Dados Orientada a Valor Social e de Negócios**

Este Trabalho de Graduação é um **Portfólio Integrador**. Ele reúne os seis Projetos Integradores do curso e mostra como as competências foram se somando, do entendimento de negócio à implantação de soluções analíticas com impacto social.

📄 **Versão final:** [`01_Documento_ABNT/TG_Stefanie_Mayumi_Inacio_Kobayashi_Resende_2026.pdf`](01_Documento_ABNT/TG_Stefanie_Mayumi_Inacio_Kobayashi_Resende_2026.pdf)

---

## Estrutura de Pastas

```
TG/
├── 01_Documento_ABNT/
│   ├── TG_Stefanie_..._2026.pdf    ← versão final do TG (exportada do Google Docs)
│   ├── figuras/                    ← imagens usadas nas figuras do TG
│   └── Resumo_Simposio_Fatec.md    ← resumo para o simpósio
├── 02_Evidencias_PI/
│   ├── PI1_Negocios/               ← Easy Cooking: relatório, pitch deck, apresentação
│   ├── PI2_Visualizacao/           ← Easy Cooking: relatório e apresentação (BI)
│   ├── PI3_Analise_I/              ← PGA × RAA Fatec: relatório e apresentação
│   ├── PI4_Analise_II/             ← Violência contra a mulher (DDM): relatório, guia, scripts
│   ├── PI5_Projetos_I/             ← Hotspots preditivos (DDM): relatório, app, guias
│   └── PI6_Projetos_II/            ← Classificação histórica por zona: figuras e telas do app
├── 03_Projetos_Extras/             ← certificados, artigos, projetos pessoais
├── 04_Apresentacao_Banca/          ← slides finais da defesa
├── Manual_TG_CDN_v1-3_revisada.pdf ← manual do TG do curso
└── RESUMO-TEMPLATE-A.docx          ← modelo de resumo da Fatec
```

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
- `Relatório - Easy Cooking.pdf`: relatório final do projeto
- `Pitch Deck - Easy Cooking.pdf`: proposta de valor
- `Apresentação Final.pdf`: apresentação do semestre

### PI2 — Visualização de Dados
- `Relatório - Easy Cooking.pdf`: relatório com dashboards e análises
- `Apresentação Final PI.pdf`: apresentação final

### PI3 — Análise de Dados I
- `PI3 - Relatório.pdf`: análise PGA × RAA 2024 da Fatec Votorantim e proposta de ETL
- `PI 3 - Apresentação.pdf`: apresentação dos resultados

### PI4 — Análise de Dados II
- `Analise de Violencia Contra a Mulher_Relatorio.pdf`: relatório técnico
- `Apresentação_Analise de Violencia Contra a Mulher.pdf`: apresentação dos resultados
- `Guia de Uso – Análise de Ocorrências….pdf` (e `.docx`): manual do dashboard para gestores
- `One Pager_PI4.pdf`: síntese executiva
- `README.md`: documentação do projeto
- `scripts/`: `Script_ddm.py` e `Script_produtividade.py`
- `Guia de Uso.txt` e `Vídeo - Pitch.txt`: links do guia online e do vídeo

### PI5 — Projetos em Ciência de Dados I

**Documentos institucionais**
- `Kick-off - PI5.pdf`: apresentação de kick-off
- `Relatório de Divergências - Delegacia.pdf`: divergências encontradas nos dados da delegacia
- O formulário inicial, as atas de reunião e o termo de cooperação institucional foram assinados, mas não estão neste repositório porque contêm dados pessoais.

**Entregáveis técnicos e acadêmicos**
- `Relatório - PI5.pdf`: relatório técnico-científico
- `Apresentação - PI5.pdf`: slides da defesa
- `Apresentacao_Modelo.pdf`: arquitetura do modelo preditivo
- `Guia de Uso - PI5.pdf`: manual da aplicação web
- `Deploy Guide - PI5.pdf`: hospedagem e implantação

**Figuras do pipeline**
- `app_preview.png`, `top15_bairros.png`, `heatmap_mes_periodo.png`, `features_temporais.png`, `importancia_features.png`, `comparacao_modelos.png`, `arvore_decisao.png`

🌐 App: [pifatec.useconectai.com.br](https://pifatec.useconectai.com.br/)

### PI6 — Projetos em Ciência de Dados II
- `01` a `06`: figuras do relatório final (pipeline no Databricks)
- `07` a `10`: telas do aplicativo no Databricks Apps
- `LEIA-ME.txt`: origem e data de cada imagem

💻 Código: [github.com/MayKobayashi/PI6-Classificacao-Violencia](https://github.com/MayKobayashi/PI6-Classificacao-Violencia)

---

## Perfil

**Stefanie Mayumi Inacio Kobayashi Resende**
Coordenadora de Dados e BI | Cientista de Dados em formação

- Atuação em startup de tecnologia, com foco em Business Intelligence e arquitetura de dados
- Portfólio: [maykobayashi.github.io](https://maykobayashi.github.io)

`Python` · `SQL` · `Google BigQuery` · `Databricks` · `Looker Studio` · `Power BI` · `ETL` · `Machine Learning` · `Design Thinking`

---

*Última atualização: novembro de 2026, 6º semestre (versão final do TG)*
