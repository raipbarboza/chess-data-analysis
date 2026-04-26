# chess-data-analysis

Análise de partidas de xadrez usando a API do chess.com — coleta, limpeza e insights com Python e pandas.

---

## O que esse projeto faz

Coleta automaticamente todas as partidas do usuário **raizeraaa** via API pública do chess.com, estrutura os dados em um DataFrame e gera análises sobre padrões de jogo.

## Principais descobertas

- **Tilt confirmado** — acurácia cai de 73% para 60% após a primeira derrota do dia
- **Melhor abertura** — Indian Game com 90% de vitória em 10+ partidas
- **Performance por cor** — brancas 51.4% vs pretas 47.7%
- **4076 partidas** coletadas entre 2022 e 2026

## Tecnologias

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

## Notebooks

| Notebook | Descrição |
|---|---|
| `01_coleta_chesscom.ipynb` | Coleta via API chess.com |
| `02_parsing_pgn.ipynb` | Parsing e estruturação dos dados |
| `03_analise_profunda.ipynb` | Tilt detection, aberturas e tempo |
| `04_dashboard.ipynb` | Visualizações e gráficos |

## Como executar

```bash
git clone https://github.com/raipbarboza/chess-data-analysis.git
cd chess-data-analysis
pip install -r requirements.txt
```

---

## Projetos relacionados

🔗 [carbontrack-br](https://github.com/raipbarboza/carbontrack-br) — Pipeline de risco de carbono de empresas brasileiras

🔗 [python-esg-studies](https://github.com/raipbarboza/python-esg-studies) — Fundamentos de Python aplicados a dados ESG

---

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rai-pereira-barboza-01a90a262)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/raipbarboza)
