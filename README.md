# Algoritmo KNN  - Trabalho Módulo 1

## Por: Matheus Mendonca Lopes, Otávio Santos, Raphael Griffoni, Vinícius Leôncio

Base de dados usada: <https://gist.githubusercontent.com/guilhermesilveira/4d1d4a16ccbf6ea4e0a64a38a24ec884/raw/afd05cb0c796d18f3f5a6537053ded308ba94bf7/car-prices.csv>

Compreendendo a base de dados: <br>![Tabela](src/tabela.jpg "Tabela")<br>

- A primeira coluna contém o ID de cada veículo. Essa informação não será necessária para a classificação.
- **milhas_por_ano**: representa quantas milhas em média o carro andou por ano.
- **ano_do_modelo**: representa o ano de fabricação do veículo.
- **preco**: representa o preço do veículo.
- **vendido**: rótulo de classificação para o algoritmo.
<br><br>
Para trabalhar com a lista, as milhas_por_ano e ano_do_modelo serão utilizados para calcular as milhas rodadas no total, para ser possível realizar o cálculo da distância euclidiana.
<br><br>
**INFO:**<br>
Os dados são embaralhados a cada vez que o programa é executada, garantindo o funcionamento do dataset como um todo e dos filtros internos. São utilizados 500 dados após a remoção dos outliers.<br>
O filtro de outliers se mostrou necessário, pois há uma faixa de classificações estatisticamente inconsistente, como mostra o gráfico abaixo:<br>![Grafico](src/graph.jpg "Grafico")
