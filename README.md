# 🛍️ Segmentação de Clientes de Shopping com K-Means

![Status](https://img.shields.io/badge/status-conclu%C3%_A_do-brightgreen)

## 📄 Descrição do Projeto

Este projeto de **Aprendizado Não Supervisionado** utiliza o algoritmo **K-Means** para realizar a segmentação de clientes de um shopping center. O objetivo é identificar grupos (clusters) distintos de clientes com base em sua renda anual e pontuação de gastos, transformando dados brutos em insights estratégicos para a criação de campanhas de marketing personalizadas.

## 📊 Dataset

O dataset utilizado foi o "Mall Customer Segmentation Data", obtido na plataforma Kaggle. Ele contém dados demográficos e de consumo de 200 clientes.

*   **Link para o Dataset:** [Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
*   **Features Utilizadas:** `Annual Income (k$)` e `Spending Score (1-100)`.

## 🛠️ Ferramentas e Técnicas Utilizadas

*   **Linguagem:** Python 3
*   **Bibliotecas:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
*   **Algoritmo:** `KMeans` do Scikit-learn.
*   **Técnica Chave:** O **Método do Cotovelo (Elbow Method)** foi utilizado para determinar o número ótimo de clusters (K), resultando na escolha de **K=5**.

## 📈 Resultados: Os 5 Segmentos de Clientes

A aplicação do K-Means revelou 5 perfis de clientes claros e acionáveis:

*   **Cluster 3 (Alvos Ideais):** Clientes com alta renda e alta pontuação de gastos. O grupo mais valioso para o shopping, ideal para programas de fidelidade VIP.
*   **Cluster 2 (Poupadores Ricos):** Clientes com alta renda, mas que gastam pouco. Um grupo com grande potencial a ser explorado com marketing de luxo e serviços exclusivos.
*   **Cluster 1 (Público Geral):** O maior grupo, com renda e gastos médios, representando o cliente mediano do shopping.
*   **Cluster 0 (Jovens Gastadores):** Clientes com baixa renda, mas que gastam muito. Prováveis alvos para tendências, fast fashion e entretenimento.
*   **Cluster 4 (Cautelosos):** Clientes com baixa renda e baixa pontuação de gastos, focados em compras essenciais e promoções.

![Visualização dos Clusters](link_para_seu_grafico.png) 
*(Dica: Você pode tirar um print do seu gráfico de clusters, fazer o upload para o repositório e colocar o link aqui para que ele apareça no README)*

## 🚀 Como Executar o Projeto

1.  Clone este repositório.
2.  Instale as dependências listadas em um arquivo `requirements.txt`.
3.  Execute o notebook `analise_segmentacao_clientes.ipynb` em um ambiente Jupyter.
