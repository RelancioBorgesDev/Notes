# Built In Methods - Array
## **Insert and Remove Methods**
* pop() - Remove o ultimo elemento e retorna o valor que foi removido.

* push() - Adiciona um valor no final do Array.

* shift() - Remove um elemento do começo do Array, e muda o indice de todos os elementos para - 1.

* unshift() - Adiciona um elemento para o inicio do Array e adiciona + 1 no indice de todos os elementos.

* splice() - Adiciona um valor no Array em uma determinada posição, podendo determinar quantos elementos vão ser removidos e quais elementos devem ser adicionados. ***! Tambem é possivel remover elementos usando o splice, splice(0,1), remove o elemento 0, e não adiciona ninguem***. 

* slice() - Remove um elemento retornando um novo Array, não remove do Array Principal

## **Merge - Methods**
* concat() - Junta dois arrays retornando um só, a junção dos outros dois

## **Ordenar e Reverter - Methods**
- sort() - Por padrão ordena um Array de Strings na ordem alfabética. Para organizar numeros é necessário passar uma função que recebe dois parametros, e compara eles.
  * Se o resultado for negativo, a é ordenado antes de b.
  * Se o resultado for positivo, b é ordenado antes de a.
  * Se o resultado for 0, nenhuma alteração será feita com a ordem de classificação dos dois valores.


- reverse() - Inverte as posições dos elementos do Array.

## **Iteração - Methods**

- forEach() - Executa uma Callback para cada elemento do Array, Parâmetros (item,indice ,array)

- map() - Executa uma Callback para cada elemento do Array e retorna um novo Array com a mesma quantidade de valores do Array Original.

- filter() - Retorna um array ou um valor que passe pelo "filtro"/condição posta na Callback.

- every() - Vê se todos os elementos do array passam no teste.

- some() - Verifica se algum valor passa no teste.

- indexOf() - Retorna o indice do valor passado por parâmetro (item, start)

- lastIndexOf() - Mesma coisa do indexOf(), so que retorna o ultimo valor.

- find() - Retorna o valor que passar no teste.

- findIndex() - Mesma coisa do find, so retorna o Indice.