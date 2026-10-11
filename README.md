# Análise de Rede Social com Grafos

Projeto 1 da disciplina Teoria e Aplicação de Grafos (Turma 01, 2026/2 - Prof. Díbio, UnB).

A proposta é pegar um pedaço real da rede de amizades do Facebook e usar grafos para
entender quem são os usuários mais influentes dessa amostra: quem tem mais conexões,
quem funciona como ponte entre grupos diferentes, quem está mais perto de todo mundo e
quem está conectado às pessoas certas.

## O que precisa ser feito

- Amostra de 404 nós sorteados do dataset [ego-Facebook da Stanford SNAP](https://snap.stanford.edu/data/egonets-Facebook.html)
  (4039 usuários, 88234 amizades no total), com todas as arestas entre eles;
- Grafo montado com NetworkX;
- Comunidades detectadas com o algoritmo de Louvain;
- As quatro medidas de centralidade pedidas no enunciado: grau, intermediação,
  proximidade e autovetor;
- Gráficos de cada métrica, com os nós mais relevantes destacados;
- Discussão dos resultados.

O notebook em [`notebook/analise_rede_social.ipynb`](notebook/analise_rede_social.ipynb)
já está com essa estrutura (uma seção por etapa, com instruções do que fazer em cada
uma) — falta implementar o código de cada parte. Dividam as seções entre os
integrantes do grupo.

## Estrutura

```
├── notebook/        # notebook com a estrutura das etapas, pronto pra ser preenchido
├── data/            # dataset original (SNAP)
├── figuras/         # onde salvar os gráficos gerados
└── requirements.txt
```

## Rodando o projeto

```bash
pip install -r requirements.txt
jupyter notebook notebook/analise_rede_social.ipynb
```

## Dataset

J. McAuley e J. Leskovec, *Learning to Discover Social Circles in Ego Networks*, NIPS 2012.
[snap.stanford.edu/data/egonets-Facebook.html](https://snap.stanford.edu/data/egonets-Facebook.html)

## Integrantes

- [Nome completo 1] - [matrícula]
- [Nome completo 2] - [matrícula]
