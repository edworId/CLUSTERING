# Segmentação de Clientes com Clustering - Análise de Consumo de Energia

## Descrição do Projeto

Este projeto tem como objetivo realizar uma segmentação de clientes baseada em seus padrões de consumo de energia utilizando técnicas de Aprendizado Não Supervisionado, especificamente Clustering. A análise explora a redução de dimensionalidade com **PCA** (Análise de Componentes Principais) e a criação de grupos com o algoritmo **K-means**.

## Objetivos
- Realizar análise exploratória do consumo de energia dos clientes.
- Aplicar **PCA** para reduzir a dimensionalidade dos dados e otimizar o desempenho.
- Implementar o algoritmo **K-means** para segmentar os clientes em grupos.
- Determinar o número ideal de clusters utilizando a **Curva de Elbow**.
- Avaliar a qualidade dos clusters usando o **Silhouette Score**.
- Gerar um **Cluster Map** para visualização dos agrupamentos.

## Tecnologias Utilizadas
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Metodologia

1. **Análise Exploratória de Dados (EDA)**: Inicialmente, os dados de consumo de energia foram analisados para identificar padrões e outliers.
2. **Redução de Dimensionalidade com PCA**: Utilizamos a técnica de **PCA** para reduzir as dimensões dos dados e manter apenas os componentes mais relevantes para o clustering.
3. **Definição de Clusters com K-means**: O algoritmo **K-means** foi aplicado para agrupar os dados. Através da **Curva de Elbow**, determinamos o número ideal de clusters, seguido da avaliação da qualidade dos agrupamentos com o **Silhouette Score**.
4. **Visualização dos Clusters**: Um **Cluster Map** foi gerado para facilitar a interpretação dos grupos formados.

## Resultados

- O número ideal de clusters foi identificado com base na Curva de Elbow.
- O **Silhouette Score** validou a coesão e separação adequadas dos grupos formados.
- O **Cluster Map** apresentou visualmente os diferentes segmentos de clientes.
