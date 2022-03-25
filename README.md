# Machine-Learning-introdu-o-a-classifica-o-com-SKLearn
Machine Learning (ou aprendizado de máquina) é uma inteligência artificial que permite que computadores tomem decisões com a ajuda de algoritmos. Esses algoritmos reconhecem padrões e se tornam capazes de fazer predições. De forma bem simples, o Machine Learning se baseia na construção e no uso de algoritmos que “aprendem” a partir dos dados.

Falamos que uma máquina “aprende” com os dados quando ela consegue melhorar seu desempenho com o aumento de informação recebida. Dessa forma, utilizam-se observações e soluções calculadas anteriormente para realizar previsões de problemas utilizando dados distintos dos já observados.

É importante salientar que problemas como “escolher o aluno com a maior nota de Estatística da turma” ou “Verificar o produto mais recorrente dentre as compras dos clientes de um supermercado” não se tratam de problemas da área do Machine Learning. Esses problemas não utilizam dados para fazer previsões, eles podem ser resolvidos apenas utilizando a ordenação dos dados.

Os problemas de Machine Learning são divididos em três subáreas principais:

#Classificação:

baseia-se em prever a categoria de uma observação dada. Aqui, procura-se estimar um “classificador” que gere como saída a classificação qualitativa de um dado não observado com base em dados de entrada (que abrangem observações com classificações já definidas).
Exemplo: um classificador que utilize dados não observados de um paciente e classifique-o como doente ou não-doente.

#Regressão: 
de forma similar a classificação, utiliza dados de entrada (preditores) já observados para prever uma resposta. A grande diferença é que, neste caso, procura-se estimar um valor numérico e não uma classificação de uma observação.
Exemplo: estimar um modelo que utilize a idade e os anos de escolaridade de um indivíduo não-observado anteriormente para tentar prever seu salário. Utiliza-se como base desse modelo: idades, anos de escolaridades e salários de diversos indivíduos já observados anteriormente.

#Agrupamento: 
também conhecido como “Clustering”, tem como objetivo agrupar observações em grupos conhecidos como “clusters”. Essas observações apresentam similaridades dentro de seu cluster e diferenças em relação aos demais clusters formados. Diferente da Classificação, não é realizada a rotulação dos clusters, fazendo com que não exista uma clusterização errada ou certa. A clusterização utilizada resulta em diferentes tipos de clusters, e a escolha dessas técnicas deve ser previamente analisada pelo pesquisador.
Exemplo: agrupar fotos de animais similares em clusters, sem ter o conhecimento prévio de qual animal está sendo apresentado.
Essas três subáreas podem ser divididas em dois tipos de aprendizado:

Supervised Learning: ou “aprendizado supervisionado”, abrange as subáreas da Classificação e Regressão. Utiliza dados já observados que possuem respostas ou classificações rotuladas, possibilitando comparar as previsões das respostas/rótulos com os rótulos reais.
Unsupervised Learning: ou “aprendizado não-supervisionado”, é onde a subárea do Clustering se encaixa. Suas técnicas não necessitam rótulos de suas observações e seu objetivo principal é encontrar grupos onde suas observações apresentem comportamento similar.
