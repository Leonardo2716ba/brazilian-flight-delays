# ✈️ Previsão de Atrasos de Voos no Brasil com IA

Este projeto tem como objetivo aplicar **técnicas de Inteligência Artificial** para prever **atrasos em voos domésticos no Brasil**, utilizando dados reais do [Brazilian Flights Dataset (OSF)](https://osf.io/hw3v2/). É uma atividade desenvolvida como parte da **Avaliação 02** da disciplina **BCC325 – Inteligência Artificial** da **UFOP**, sob orientação do professor **Jadson Castro Gertrudes**.

## 🎯 Objetivo

Criar um modelo de aprendizado de máquina capaz de prever se um voo terá atraso, com base em dados históricos como:
- Companhia aérea
- Aeroporto de origem e destino
- Data e horário de partida
- Duração prevista do voo
- Situação climática (se disponível)

## 🧠 Técnica Utilizada

Foi utilizada a abordagem de **Aprendizado de Máquina supervisionado**, com modelos de **classificação binária**.

### Modelos testados:
- Regressão Logística
- Random Forest
- XGBoost

## 🗃️ Dataset

**Fonte:** Brazilian Flights Dataset – OSF  
**Período:** Janeiro a Dezembro de 2019  
**Formato:** CSV  
**Link:** [https://osf.io/hw3v2/](https://osf.io/hw3v2/)

## ⚙️ Etapas do Projeto

1. **Carregamento e limpeza dos dados**
2. **Criação da variável alvo** (atraso ≥ 15 minutos)
3. **Codificação de variáveis categóricas**
4. **Divisão entre treino e teste (80/20)**
5. **Treinamento de modelos**
6. **Avaliação com métricas padrão**

## 📈 Métricas de Avaliação

- Acurácia
- Precisão
- Recall
- F1-Score
- Matriz de confusão
- Curva ROC e AUC

## 🛠️ Tecnologias

- Python 3.11+
- Pandas
- Scikit-Learn
- XGBoost
- Matplotlib / Seaborn

## 📁 Organização do Repositório

```
.
├── data/
│   └── voos_2019.csv              # Arquivo convertido do .RData
├── notebooks/
│   └── exploracao_dados.ipynb     # Análise exploratória inicial
│   └── modelo_classificacao.ipynb # Treinamento e avaliação dos modelos
├── src/
│   └── pre_processamento.py       # Funções de limpeza e transformação
│   └── modelos.py                 # Modelos de ML usados no projeto
├── relatorio.pdf                  # Relatório técnico final (máx. 8 páginas)
├── poster.png                     # Pôster da apresentação
└── README.md                      # Este arquivo
```

## 👨‍👩‍👧‍👦 Equipe

- Leonardo Gomes ([@seuuser](https://github.com/seuuser))
- Nome 2
- Nome 3
- Nome 4
- Nome 5

## 📌 Apresentação

A apresentação do pôster será realizada em **13 de agosto de 2025**, conforme cronograma da disciplina.

---

> Projeto acadêmico da disciplina **BCC325 – Inteligência Artificial**  
> Instituto de Ciências Exatas e Biológicas – ICEB  
> Universidade Federal de Ouro Preto – UFOP
