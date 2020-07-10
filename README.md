# Market Basket Analysis
> Aplicação de um algoritmo apriori em uma base de dados de um varejo online.

Uma Regra de Associação nada mais é que um método de explorar relações entre Itens em conjuntos de dados. Vamos definir os seguintes termos para Regra de Associação:
  - I (Itens): conjunto dos seus n atributos {i_1, i_2, …, i_n};
  - D (Database): conjunto das m transações {t_1, t_2, …, t_m};
  - Toda transação t_i, é única em D e consiste em um subconjunto dos Itens I;
  - Vamos Definir uma Regra de Associação como a relação (X => Y) , onde X e Y são subconjuntos de I. Eles não podem ter nenhum elemento em comum.
  - X é chamado de antecedente e Y da consequência da Regra.
  
Com isso definido, considere a transação de ID igual a 2, podemos ter a seguinte Regra de Associação: {Beer} => {Diaper}. Essa é a Regra de Associação que define que nessa transação, quem comprou Cerveja também comprou Fralda.

Nesse ponto, se você começar a montar as Regras de Associação na sua cabeça, perceberá que mesmo para um conjunto de dados pequeno, existem muitas Regras. O desafio agora é encontrar um modo de selecionar as regras relevantes. 
