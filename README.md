# analise-cluster
Este repositório contém uma atividade da disciplina de 'Mineração de Dados' que tem como objetivo aplicar e comparar diferentes algoritmos de clusterização (K-Means e Agglomerative Clustering) em um conjunto de dados, analisando os clusters encontrados.


Atividade 1
1) Qual a quantidade de clusters? 4 clusters
2) Quantos pontos há em cada cluster? KMeans: [100, 100, 100, 100]; AgglomerativeClustering: [100, 100, 100, 100]
3) Qual foi o coeficiente de Silhouette? KMeans: 0.8105; AgglomerativeClustering: 0.8105
4) Qual foi o coeficiente de Davies Bouldin? KMeans: 0.2607; AgglomerativeClustering: 0.2607
5) Há diferença na performance dessas métricas se utilizar o KMeans ou o AgglomerativeClustering? Não, a performance foi a mesma em todos os coeficientes.

Atividade 2
1) Qual a quantidade de clusters? 3 clusters
2) Quantos pontos há em cada cluster? KMeans: [1499, 2000, 1001]; AgglomerativeClustering: [2000, 1499, 1001]
3) Qual a pureza dos clusters? KMeans: 0.9998; AgglomerativeClustering: 0.9998
4) Qual o coeficiente de Jaccard? KMeans: 0.0000; AgglomerativeClustering: 0.3331
5) Qual o coeficiente de Rand? KMeans: 0.9998; AgglomerativeClustering: 0.9998
6) Qual o coeficiente de Fowlkes Mallows? KMeans: 0.9997; AgglomerativeClustering: 0.9997
7) Há diferença na performance dessas métricas se utilizar o KMeans ou o AgglomerativeClustering? Sim, tem uma diferença no Coeficiente de Jaccard. Isso indica uma "troca de rótulos" (label switching) pelos algoritmos sobre a coluna 'label'.
8) Faça uma análise das caracteristicas de cada grupo e apresente em sala.
Cluster 0 (1499 pessoas): Homens Jovens Adultos (19-29), Solteiros, com Filhos, Baixa Renda.
Cluster 1 (2000 pessoas): Mulheres Adultas (30-99), Casadas, sem Filhos, Média Renda.
Cluster 2 (1001 pessoas): Homens Jovens (0-18), Solteiros, com Filhos, Média-Baixa Renda.
