# Modfied Virus on Network
<br>
O modelo utilizado tem como objetivo inicial descrever a propagação de um vírus em uma rede e como a mesma pode reagir diante desta circunstância. Analisando um vírus observando de um ponto de vista biológico, uma característica fundamental trata-se da sua capacidade em mutar diante a situações adversas, assim, será acrescentado a possibilidade de mutação do mesmo, sendo esta uma mutação irá diminuir a possibilidade de resistência, aumentar o nível de sucetividade a adquirir vírus e aumentar a a probabilidade de propagação do vírus.

<h3>Hipótese Casual</h3>

Através do acréscimo da possibilidade de mutação, temos que possivelmente a rede será levada a uma grande contaminação dependendo do cenário inicial, e para uma baixa probabilidade de adquirir resistência muito possivelmente a rede terá muitas dificuldades durante um determinado período para voltar a um caso de estabilidade.

<h3>Definições e Resultados</h3>

<p>
Para a elaboração do procedimento uma nova variável foi inserida com o nome de "mutated" tendo um grau de variação de 0.0 a 0.4, colocou-se uma baixa intensidade para dificultar a mutação.
</p>
<p>
E caso de algum elemento mutar, então ocorrerá um aumento em 10% da taxa de transmissão, 10% de aumento de sucetividade e 10% de diminuição da probabilidade de adquirir resistência, os valores definidos foram descritos de maneira arbitrária, contudo os mesmos poderiam ser modificados para tornar o experimento mais preciso.
<p>
Como resultados temos que a princípio ocorre um pico no aumento do vírus, contudo, após a passagem do tempo, independente de ser ou não mutante a rede irá se estabilizar e lentamente haverá uma queda, o modelo analisado poderia ser mais apurado ao criar melhor a disputa entre adquirir resistência e ocorrer mutações, assim haveriam resultados menos estáveis a medida em que o tempo decorresse.
</p>
<p>
Acrescentou-se um elemento de slider em sua interface para que fosse possível controlar a probabilidade de mutação.
</p>

<h3>Procedimentos</h3>
<p>
Para execução do projeto, pode-se através do uso da versão 3 de python realizar o seguinte comando:
<code>
python3 run.py
</code>
<br>
Assim, será possível executá-lo.
</p>
<p>
Para análise e exploração dos arquivos, dentro do repositório e na pasta "virus_on_network" existem os arquivos com suas respectivas modificações, sendo <code>model.py</code> responsável por descrever o modelo da simulação, assim como seus agentes e <code>server.py</code> responsável por definir aspectos gerais de execução.
</p>
