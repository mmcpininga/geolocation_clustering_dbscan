# geolocation_clustering_dbscan
Geolocation Clustering using the DBSCAN Algorithm

O problema consiste em agrupar os dados (coordenadas de latitude e longitude) com base na sua geolocalização e respeitando as restrições.

Restrição: 1) Distância máxima de 0.8km entre os pontos e seu centróide.

A figura abaixo mostra os pontos em azul antes de aplicar o agrupamento com o algoritmo DBSCAN.

![image](https://user-images.githubusercontent.com/18504119/120047713-9e5c4900-bfeb-11eb-8fc3-3af8911081b7.png)

A figura abaixo demonstra o resultado dos clusters com cores diferentes.
Entretanto, utilizando o algoritmo DBSCAN, não foi possível respeitar a restrição da distância de 0.8km entre os pontos.

![image](https://user-images.githubusercontent.com/18504119/120853204-abc88480-c551-11eb-9d2c-efdbae99ff87.png)
