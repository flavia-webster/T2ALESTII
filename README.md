# T2ALESTII
Algoritmo que calcula os graus de separação entre dois atores/atrizes
Com base no código fornecido no Moodle, implementar o algoritmo que calcula os graus de separação entre dois atores/atrizes (ex: Kevin Bacon e Chuck Norris).

O arquivo de dados, contido no código (movies.txt) tem o seguinte formato:



Ou seja, cada linha contém os dados de um único filme:

Os campos são separados por /
O primeiro campo é o nome do filme
Os demais campos são os nomes dos atores/atrizes (elenco)
Como apresentado em aula, o grafo deve ser montado com vértices nos nomes dos filmes e elenco, onde as arestas são as ligações entre filmes e elenco (ver figura acima).
A partir da leitura e da criação do grafo não dirigido, o programa deve perguntar dois nomes de atores/atrizes e mostrar menor caminho de um até outro (isto é, BFS).

Dica: são cerca de 119 mil nomes diferentes (crie um grafo com 120000 vértices).

Utilizando o código-base da aula passada implementar o caminhamento em largura (breadth first search). 
Dica: comece com o código apresentado no slide 46 (que usa a classe Queue fornecida), mas você pode usar qualquer estrutura de dados que funcione como fila (ArrayList, LinkedList, ...) 
