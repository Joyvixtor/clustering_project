# Introdução 
<p align="justify">Na descrição do projeto Clustering, a primeira etapa a ser realizada pela equipe é a escolha de um banco de dados útil do <i>UCI Machine Learning Repository</i>. O Dataset escolhido para este trabalho específico em foi oi "<i>Wine Data Set</i>. Para acessar a página principal do repositório, <a href= "https://archive.ics.uci.edu/ml/datasets/wine"> clique aqui </a>. <br>
O banco de dados em questão tem como finalidade analisar quimicamente alguns atributos de diferentes vinhos. Os dados analisados podem servir para descobrir qual é a origem exata do produto. No total,  13 variáveis foram disponibilizadas para análise,  mas a equipe escolheu apenas 2 principais para realizar o tratamento dos dados: <i>Alcohol</i> e <i>Malic Acid</i>. 

<img 
    src=images/dataset_table.png>
<br> 
Após a filtragem dos dados a serem utilizados durante o projeto, a equipe definiu quais seriam os métodos utilizados para destacar e dar sentido às informações que foram colhidas do <i>Dataset</i>. Os mecanismos de análise foram estabelecidos e as suas biblioetecas em questão. Ao longo do relatório, as definições específicas ficarão mais claras através da utilização de trechos do código e imagens dos gráficos plotados.
</p>

# Fundamentos
Os modelos utilizados para o tratamento e análise dos dados foram:

## KMeans
<b>KMeans</b> é um dos métodos de Clustering mais utilizados no procedimento de métodos para Machine Learning ou para a análise de dados. Em poucas palavras, o processo de Clustering consiste em analisar informações e definir semelhanças e diferenças entre os dados. Variáveis em um mesmo aglomerado tendem a ser semelhantes entre si, enquanto dois aglomerados diferentes apresentam desconformidades significativas. <br>
 O algoritmo KMean é responsável por estabelecer um K número de clusters a ser definido dentro de um conjunto de dados. Cada ponto de dados é vinculado a um aglomerado e, no final, um ponto centróide é estabelecido como o centro do cluster.

### Elbow Method
Para aplicar o algoritmo, o K número de clusters é uma importante variável a ser considerada antes de começar a rodar o método. Portanto, um algoritmo matemático também deve ser estabelecido para que este valor não seja escolhido arbitrariamente.<br>
O <i>Elbow Method</i> é capaz de testar a variação que ocorre entre os dados quando o número de aglomerados muda. Estes valores são plotados e o deve-se encontrar um ponto de curvatura no gráfico semelhante a um "cotovelo". 

### Silhouette Values
Além do Elbow Method, o <b>Silhouette Method</b> (ou Método Silhouette) também é uma outra possibilidade para achar o número ótimo de clusters em um conjuntod de dados. O algoritmo realiza esta operação medindo a distância de um determinado ponto de um aglomerado para outro aglomerado. A <i>range</i> do método silhouette varia de -1 para +1, onde as extremidades indicam que os pontos de cada cluster estão muito afastados, enquanto valores próximos à 0 indicam que os pontos de cada cluster estão muito próximos ou criando intersecções entre si. 

## KMedoids
## DBSCAN

# Metodologia

# Resultados

# Conclusões 