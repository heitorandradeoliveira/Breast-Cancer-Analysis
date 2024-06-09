# Projeto de Análise Exploratória e Modelagem de Classificação de Câncer de Mama

Este é um projeto de análise exploratória e modelagem de classificação de câncer de mama, utilizando a base de dados de câncer de mama do repositório de aprendizado de máquina da UCI.

## Descrição

O objetivo deste projeto é explorar a base de dados de câncer de mama, realizar uma análise exploratória dos dados, pré-processar os dados conforme necessário e construir modelos de classificação para prever a recorrência do câncer de mama com base nas características diagnósticas.

## Base de Dados

- **Fonte**: [UCI Machine Learning Repository - Breast Cancer](https://archive.ics.uci.edu/dataset/14/breast+cancer)
- **Descrição**: A base de dados contém características diagnósticas de pacientes com câncer de mama, incluindo idade, estado da menopausa, tamanho do tumor, número de linfonodos invadidos, entre outros.

## Variáveis

- **Class**: Variável alvo que indica se ocorreu recorrência do câncer de mama (no-recurrence-events = sem recorrência, recurrence-events = recorrência).
- **age**: Idade do paciente em faixas etárias (10-19, 20-29, 30-39, 40-49, 50-59, 60-69, 70-79, 80-89, 90-99 anos).
- **menopause**: Estado da menopausa do paciente (lt40 = antes dos 40 anos, ge40 = igual ou acima dos 40 anos, premeno = pré-menopausa).
- **tumor-size**: Tamanho do tumor em milímetros (0-4, 5-9, 10-14, 15-19, 20-24, 25-29, 30-34, 35-39, 40-44, 45-49, 50-54, 55-59 mm).
- **inv-nodes**: Número de linfonodos invadidos (0-2, 3-5, 6-8, 9-11, 12-14, 15-17, 18-20, 21-23, 24-26, 27-29, 30-32, 33-35, 36-39).
- **node-caps**: Se os linfonodos estão encapsulados ou não (yes = sim, no = não).
- **deg-malig**: Grau de malignidade do tumor (1, 2, 3).
- **breast**: Lado do seio afetado pelo câncer (left = esquerdo, right = direito).
- **breast-quad**: Quadrante do seio afetado pelo câncer (left-up = superior esquerdo, left-low = inferior esquerdo, right-up = superior direito, right-low = inferior direito, central = central).
- **irradiat**: Se o paciente recebeu tratamento de radioterapia ou não (yes = sim, no = não).

### Estrutura do Projeto

O projeto está organizado da seguinte forma:

```
Breast-Cancer-Analysis/
├── data/
│   ├── train.csv
│   └── test.csv
├── notebooks/
│   ├── 01_analise_descritiva.ipynb
│   ├── 02_pre_processamento.ipynb
│   └── 03_modelagem.ipynb
├── requirements.txt
└── README.md
```

## Etapas do Projeto

1. **Análise Exploratória de Dados (EDA)**:

   - Explorar a estrutura dos dados.
   - Visualizar a distribuição das características.
   - Identificar correlações entre as características.

2. **Pré-processamento de Dados**:

   - Tratar valores ausentes, se necessário.
   - Codificar variáveis categóricas, se aplicável.
   - Normalizar ou padronizar os dados, se necessário.

3. **Modelo de Classificação**:
   - Dividir os dados em conjunto de treinamento e conjunto de teste.
   - Treinar vários modelos de classificação.
   - Avaliar o desempenho dos modelos usando métricas como precisão, recall, F1-score e área sob a curva ROC (AUC-ROC).
   - Selecionar o melhor modelo com base nas métricas de avaliação.

## Como Usar Este Repositório

1. Clone este repositório em sua máquina local:

2. Navegue até o diretório do projeto:

3. Execute o código em sua plataforma preferida para análise de dados (Jupyter Notebook, Google Colab, etc.).

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para propor melhorias ou adicionar novos recursos ao projeto.

## Contato

Para qualquer dúvida ou sugestão, entre em contato com [Heitor Andrade Oliveira](mailto:heitor3344@gmail.com).
