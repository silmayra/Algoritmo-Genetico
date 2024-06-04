# Algoritmo-Genetico

Foi usado  o problema da mochila (ou knapsack problem), é um problema clássico de otimização combinatória. O objetivo é maximizar o valor total dos itens colocados em uma mochila, sem exceder sua capacidade de peso. No caso presente tinha-se uma lista de compras, um valor máximo (R$ 75,00.) e a prioridade de cada item da lista de compras.
Itens Produto Preço (R$) Necessidade
1 Arroz (5kg) 22 10
2 Açúcar (2kg) 3 5
3 Óleo (1l) 8 6
4 Feijão (1kg) 5 10
5 Macarrão (500g) 5 8
6 Sardinha (1lata) 5 7
7 Carne (1kg) 32 9
8 Frango (1kg) 13 9
9 Queijo (200g) 8 5
10 Presunto (200g) 4 5
11 Pão (8un.) 6 6
12 Banana (1kg) 4 7
13 Laranja (1kg) 2 7
14 Abacate (1kg) 7 2
15 Sabão (1un.) 2 9
16 Limpador multiuso (1un.) 4 6
17 Água Tônica (500ml) 7 1
18 Polpa de Fruta (500ml) 6 4
19 Refrigerante (2l) 8 3
20 Cerveja (600ml) 6 2

O algoritmo genético, utiliza alguns parâmetros de seleção. Eles são : População, gerações, taxa de crossover, taxa de mutação e no caso presente o orçamento.

Para definir os parâmetros citados, usou-se o seguinte critério:
1) População : Pode ser utilizado de início um valor moderado, variando de 50 á 200. Quanto maior a complexidade do problema, maior a necessidade de uma população grande, sendo de maior demanda de tempo e poder computacional populações maior que 200.
2) gerações: pode ser feita de duas formas : 1) estabelecendo um número de gerações e 2) estabelecendo um critério de parada. No caso presente usou-se o número de gerações (200)
3) taxa de crossover : Geralmente, uma taxa de crossover entre 0.7 e 0.9 é usada.
4) taxa de mutação : Normalmente, a taxa de mutação é baixa, entre 0.01 e 0.1.
e no caso presente o orçamento.
5) Orçamento : É  restrição específica desse problema.


