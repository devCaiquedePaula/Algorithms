# Algoritmos e Notação Big O

## Sumário

- [Introdução](#introdução)
- [O que é Notação Big O?](#o-que-é-notação-big-o)
- [Análise de Algoritmos](#análise-de-algoritmos)
  - [Complexidade de Tempo](#complexidade-de-tempo)
  - [Complexidade de Espaço](#complexidade-de-espaço)
- [Exemplos de Análise de Algoritmos](#exemplos-de-análise-de-algoritmos)
  - [Pesquisa Linear](#pesquisa-linear)
  - [Pesquisa Binária](#pesquisa-binária)
  - [Ordenação por Inserção](#ordenação-por-inserção)
  - [Ordenação Rápida](#ordenação-rápida)
- [Conclusão](#conclusão)
- [Referências](#referências)

## Introdução

Este repositório é dedicado ao estudo de algoritmos e da notação Big O, uma ferramenta essencial para entender e comparar a eficiência de diferentes algoritmos. Exploraremos a teoria por trás da notação Big O e forneceremos exemplos teóricos de análise de desempenho de algoritmos, com foco em sua implementação em Java.

## O que é Notação Big O?

A notação Big O é uma maneira de descrever a complexidade de um algoritmo em termos de tempo ou espaço de execução, dependendo do tamanho da entrada (n). É usada para caracterizar funções que expressam o tempo de execução ou o espaço usado por um algoritmo em função do tamanho da entrada.

### Principais Tipos de Complexidade

1. **O(1) - Constante:** O tempo de execução é constante, independentemente do tamanho da entrada.
2. **O(n) - Linear:** O tempo de execução cresce linearmente com o tamanho da entrada.
3. **O(n²) - Quadrática:** O tempo de execução cresce quadraticamente com o tamanho da entrada.
4. **O(log n) - Logarítmica:** O tempo de execução cresce logaritmicamente com o tamanho da entrada.
5. **O(n log n) - Linear-Logarítmica:** Comum em algoritmos de ordenação eficientes como Merge Sort e Quick Sort.

## Análise de Algoritmos

Analisar a complexidade de um algoritmo é fundamental para entender seu comportamento em diferentes cenários. A análise envolve a identificação das operações críticas que dominam o tempo de execução à medida que o tamanho da entrada aumenta.

### Complexidade de Tempo

A complexidade de tempo refere-se à quantidade de tempo que um algoritmo leva para ser executado, geralmente em função do tamanho da entrada (n). A análise de tempo ajuda a prever como o tempo de execução aumenta à medida que a entrada cresce, permitindo comparar a eficiência de diferentes algoritmos.

### Complexidade de Espaço

A complexidade de espaço refere-se à quantidade de memória que um algoritmo usa durante sua execução. Assim como a complexidade de tempo, é uma função do tamanho da entrada (n). A análise de espaço é importante para garantir que um algoritmo não só seja rápido, mas também eficiente em termos de uso de memória.

## Exemplos de Análise de Algoritmos

### Pesquisa Linear

A pesquisa linear é um algoritmo simples que percorre uma lista ou array elemento por elemento até encontrar o valor desejado ou atingir o final da lista. Sua complexidade de tempo é O(n), pois, no pior caso, todos os elementos precisam ser verificados.

### Pesquisa Binária

A pesquisa binária é um algoritmo eficiente para encontrar um elemento em uma lista ordenada. Ele divide a lista repetidamente pela metade até encontrar o elemento desejado. Sua complexidade de tempo é O(log n), tornando-o muito mais rápido do que a pesquisa linear para listas grandes.

### Ordenação por Inserção

A ordenação por inserção é um algoritmo simples de ordenação que constrói a lista ordenada elemento por elemento. No pior caso, sua complexidade de tempo é O(n²), tornando-o ineficiente para listas grandes, mas útil para listas pequenas ou quase ordenadas.

### Ordenação Rápida

A ordenação rápida, ou Quick Sort, é um dos algoritmos de ordenação mais eficientes na prática. Ele seleciona um "pivô" e reorganiza os elementos para que os menores que o pivô fiquem antes dele e os maiores fiquem depois. O processo é então repetido recursivamente para as sublistas. Sua complexidade média de tempo é O(n log n), embora possa ser O(n²) no pior caso.

## Conclusão

A compreensão da notação Big O e a análise de algoritmos são fundamentais para desenvolver software eficiente e escalável. Este repositório fornece uma introdução à teoria e exemplos teóricos para ajudar a ilustrar esses conceitos. A aplicação desses princípios em Java ou qualquer outra linguagem de programação permitirá a criação de soluções mais eficazes e robustas.

## Referências

- [Big-O Algorithm Complexity Cheat Sheet](https://www.bigocheatsheet.com/)
- [Introduction to Algorithms, 3rd Edition](https://mitpress.mit.edu/9780262033848/introduction-to-algorithms/)
- [GeeksforGeeks - Analysis of Algorithms](https://www.geeksforgeeks.org/analysis-of-algorithms-set-1-asymptotic-analysis/)

Sinta-se à vontade para explorar os conceitos e contribuir para este repositório adicionando mais análises ou melhorando as existentes. Boa codificação!
