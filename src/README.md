https://github.com/cami-la/collections-java-api-2023/tree/master

Set: Esta interface define uma coleção que não permite a inclusão de elementos duplicados. A interface SortedSet, que herda de Set, permite a ordenação natural dos elementos, como por exemplo, em ordem alfabética.

List: Define uma coleção ordenada, onde elementos duplicados são permitidos. Esta interface é a mais apropriada quando é necessária a realização de acesso aleatório aos elementos, usando seus índices.

Queue: É um tipo de coleção que mantém uma lista de prioridades, onde a ordem dos elementos é determinada pela implementação de Comparable ou Comparator. Através da interface Queue, é possível criar filas e pilhas.

Map: Cada elemento contém, na verdade, dois objetos: uma chave e um valor. Valores podem ser duplicados, mas chaves não podem. A interface SortedMap estende Map e permite a classificação ascendente das chaves. Um exemplo de aplicação dessa interface é a classe Properties, que é utilizada para armazenar configurações e propriedades de um sistema.

https://www.devmedia.com.br/java-collections-como-utilizar-collections/18450