# Algoritmo de Merge Sort

Este projeto implementa o algoritmo de ordenação Merge Sort em linguagem C. Merge Sort é um algoritmo de ordenação eficiente baseado na técnica de "dividir e conquistar".

## Descrição

Merge Sort é um algoritmo de ordenação que divide a array original em duas metades, ordena cada metade recursivamente e, em seguida, combina as duas metades ordenadas para produzir a array final ordenada.

### Funcionamento

1. **Divisão**: A array é dividida no meio até que cada subarray contenha apenas um elemento.
2. **Conquista**: Cada subarray é ordenado recursivamente.
3. **Combinação**: As metades ordenadas são combinadas para produzir a array final ordenada.

### Complexidade

- **Tempo (Pior, Médio, Melhor Caso)**: O(n log n)
- **Espaço**: O(n)

## Estrutura do Projeto

- `mergeSort`: Função que divide a array e chama recursivamente para ordenar as metades.
- `merge`: Função que combina duas metades ordenadas em uma única array ordenada.
- `main`: Função principal que inicializa a array, chama `mergeSort` e exibe a array ordenada.
