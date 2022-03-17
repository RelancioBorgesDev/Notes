# **Big O Notation**
## Forma de classificar o qual a escalabilidade do algoritimo.

### Essa classificação é feita de duas formas:
- Tempo / Time Complexity
- Espaço / Space Complexity

 ## Time Complexity / Complexidade de Tempo
- É o tempo que leva para um algoritimo rodar. É utilizado para medir o tempo em que cada trecho de código é executado.

- Existem diferentes tipos de notações de **"Time Complexity."**:

* 1. Constant time / Tempo Constante – O (1):
    Constante independente do input de tamanho n
* 2. Linear time/ Tempo Linear – O (n):
    O tempo de execução aumenta de forma linear ao comprimento/tamanho do input (n). 
* 3. Logarithmic time - Tempo Logarítmico – O (log n):
    Diz-se que um algoritmo tem uma complexidade de tempo logarítmica quando reduz o tamanho dos dados de entrada em cada etapa
* 4. Quadratic time – O (n^2):
    Diz-se que um algoritmo tem uma complexidade de tempo não linear onde o tempo de execução aumenta não linearmente (n^2) com o comprimento da entrada. Geralmente, os loops aninhados estão nessa ordem de complexidade de tempo, onde para um loop leva O(n) e se a função envolve um loop dentro de um loop, então ela vai para O(n)*O(n) = O(n^2) pedido.

 ## Space Complexity / Complexidade de Espaço
 - A complexidade do espaço é a quantidade total de espaço de memória usado por um algoritmo/programa incluindo o espaço de valores de entrada para execução. Assim, para encontrar a complexidade do espaço, basta calcular o espaço ocupado pelas variáveis ​​utilizadas em um algoritmo/programa.


 ***Bibliografia:***
 https://medium.com/linkapi-solutions/o-que-%C3%A9-big-o-notation-32f171e4a045

 https://www.faceprep.in/data-structures/space-complexity/#:~:text=Space%20complexity%20is%20the%20total,used%20in%20an%20algorithm%2Fprogram.

 https://www.mygreatlearning.com/blog/why-is-time-complexity-essential/#:~:text=Time%20complexity%20is%20the%20amount,you%20understand%20time%20complexity%20clearly.