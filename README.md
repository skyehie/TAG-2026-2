# Análise de Rede Social com Grafos

Projeto 1 — Teoria e Aplicação de Grafos, Turma 01, 2026/2, Prof. Díbio (UnB).

## Objetivo

Analisar uma amostra de 404 nós do grafo de amizades do Facebook ([dataset
ego-Facebook, SNAP](https://snap.stanford.edu/data/egonets-Facebook.html)),
aplicando métricas de grafos para identificar nós de maior influência e detectar
comunidades.

## Estrutura

```
├── notebook/
│   └── analise_rede_social.ipynb   # notebook principal, organizado por blocos
├── data/
│   └── facebook_combined.txt       # dataset original (SNAP)
├── figuras/                        # gráficos gerados
└── requirements.txt
```

## Blocos de trabalho

| Bloco | Conteúdo | Depende de |
|---|---|---|
| 1 — Dados e grafo | Coleta, amostragem dos 404 nós | — |
| 2 — Métricas | Comunidades (Louvain), centralidades | Bloco 1 |
| 3 — Visualizações | Gráficos por métrica e por comunidade | Bloco 2 |
| 4 — Análise | Discussão dos resultados | Blocos 2 e 3 |

Cada bloco corresponde a uma seção do notebook, com especificação técnica. Blocos 1
e 2 já estão implementados; Blocos 3 e 4 seguem como estrutura vazia. O Bloco 3 pode
ser dividido por métrica entre os integrantes.

## Rodando o projeto

```bash
pip install -r requirements.txt
jupyter notebook notebook/analise_rede_social.ipynb
```

## Dataset

J. McAuley e J. Leskovec, *Learning to Discover Social Circles in Ego Networks*,
NIPS 2012. [snap.stanford.edu/data/egonets-Facebook.html](https://snap.stanford.edu/data/egonets-Facebook.html)

## Integrantes

- [Carlos Roberto] - [251004385]
- [Gabrielly Batista] - [251004400]
- [Helena Miranda] - [251004302]
