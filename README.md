🎵 Análise e Predição da Popularidade Musical no Spotify

Sobre o projeto

Este projeto investiga características associadas à popularidade de músicas na plataforma Spotify, utilizando técnicas de análise exploratória de dados e Machine Learning. O objetivo é identificar padrões presentes nas faixas musicais e avaliar a capacidade de modelos de classificação em distinguir músicas consideradas hits das demais.

A partir de um conjunto de dados com mais de 1 milhão de registros, foram realizadas etapas de exploração, tratamento, seleção de atributos e treinamento de modelos preditivos.

Objetivos

* Explorar as características e a distribuição dos dados musicais;
* Investigar variáveis potencialmente associadas à popularidade das faixas;
* Identificar padrões entre atributos musicais e a classificação de hits;
* Desenvolver e avaliar modelos de Machine Learning para classificação.

Dataset

O conjunto de dados utilizado reúne informações sobre músicas do Spotify, incluindo atributos relacionados às faixas, popularidade e características musicais.

* Quantidade de registros: 1.182.354
* Período abrangido: 1957–2023
* Fonte: Dataset de músicas do Spotify

Metodologia

O desenvolvimento do projeto foi dividido nas seguintes etapas:

1. Análise exploratória dos dados (EDA): investigação da distribuição das variáveis, gêneros, valores ausentes, outliers e correlações.
2. Pré-processamento: preparação dos dados e seleção de atributos utilizados nos experimentos.
3. Definição da variável-alvo: criação da variável binária is_hit, considerando hits as faixas com track_popularity superior a 50.
4. Modelagem: aplicação de algoritmos de Machine Learning para classificação.
5. Avaliação: análise do desempenho dos modelos utilizando conjuntos de treinamento, validação e teste.

Modelos utilizados

* Logistic Regression
* Random Forest Classifier

Tecnologias e ferramentas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

Reprodutibilidade

Os experimentos foram executados localmente em uma máquina com as seguintes especificações:

* Sistema operacional: Windows 11
* Memória RAM: 16 GB
* Random seed: 42

A semente aleatória foi mantida fixa em 42 durante os experimentos, visando proporcionar maior consistência e facilitar a reprodução dos resultados.


Projeto acadêmico desenvolvido como parte da disciplina de Ciência de Dados.
