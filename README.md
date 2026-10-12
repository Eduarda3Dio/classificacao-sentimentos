# Classificação de Sentimentos em Avaliações de Produtos

## Sobre o projeto

Projeto de Machine Learning desenvolvido em Python para classificar avaliações de produtos em duas categorias: **positiva** e **negativa**.
O objetivo foi explorar técnicas de Processamento de Linguagem Natural (PLN), preparar dados textuais e avaliar o desempenho de um modelo de classificação.

---

## Objetivos

- Preparar e limpar os dados para análise.
- Transformar textos em representações numéricas utilizando TF-IDF.
- Treinar um modelo de classificação com Regressão Logística.
- Otimizar hiperparâmetros utilizando GridSearchCV.
- Avaliar o desempenho do modelo com métricas de classificação.
- Investigar limitações e possíveis fontes de erro.

  ---

## Tecnologias utilizadas

- Python
- Pandas
- Scikit-learn
- TF-IDF
- Regressão Logística
- GridSearchCV
- Jupyter Notebook

---

## Etapas do projeto

1. **Preparação dos dados:** leitura do arquivo, tratamento de valores ausentes e preparação das avaliações textuais.
2. **Pré-processamento:** limpeza e normalização dos textos.
3. **Representação textual:** utilização do TF-IDF para converter as avaliações em características numéricas.
4. **Modelagem:** treinamento de um classificador baseado em Regressão Logística.
5. **Otimização:** busca de hiperparâmetros com validação cruzada por meio do GridSearchCV.
6. **Avaliação:** análise da acurácia, precisão, recall e F1-score, além da investigação dos erros de classificação.

## Resultados

| Métrica | Resultado |
|---|---:|
| Acurácia média no GridSearchCV | 86% |
| Acurácia no conjunto de teste | 84,3% |
| Recall — avaliações negativas | 74% |
| Recall — avaliações positivas | 94% |

O modelo apresentou melhor capacidade de identificar avaliações positivas do que de recuperar todas as avaliações negativas.
Essa diferença evidencia a importância de analisar métricas por classe, em vez de avaliar um classificador apenas pela acurácia geral.
Os resultados são referentes ao conjunto de dados utilizado neste estudo e não garantem o mesmo desempenho em outras bases ou em aplicações reais.

## Aprendizados

Durante o desenvolvimento, trabalhei com preparação de dados, tratamento de problemas de codificação de caracteres, transformação de textos em features numéricas, otimização de hiperparâmetros e avaliação de modelos de classificação.
O projeto também reforçou a importância de investigar a qualidade dos rótulos e compreender os erros do modelo antes de propor melhorias.

## Como executar

1. Clone ou baixe este repositório.
2. Instale as bibliotecas necessárias.
3. Abra `classificacao_sentimentos.ipynb` no Jupyter Notebook.
4. Execute as células na ordem apresentada.

O arquivo `avaliacoes.csv` deve estar disponível no caminho esperado pelo notebook.

---

**Projeto de estudo em Machine Learning e Processamento de Linguagem Natural.**
