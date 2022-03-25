# Anotações C++
### Aprendendo C++ para aula de Estrutura de dados

## Exibir no console
- g++ nome_arquivo.cpp -o nome_arquivo.out
- ./nome_arquivo.out
- saida

## Tipos de dados:
- int
- float
- double
- char
- string
- wchar_t
- bool
- void

## Modificadores de Tipo
- Long
- Short
- Unsigned
- Signed

## Entrada e Saída de dados
- cin >>
- cout <<

## Concatenar
cout << "Digite seu" **<< nome <<** endl;

## Lidando com o tipo bool
bool isCodingFun = true;
bool isFishTasty = false;
cout << isCodingFun;  // Saida 1 (true)
cout << isFishTasty;  // Saida 0 (false)

## Operadores
* **Aritimético**
    - (+) (soma)
    - (-) (subtração)
    - (*) (multiplicação)
    - (/) (divisão)
    - (%) (modulo)
    - (++)(incremento)
    - (--)(decremento)

* **Atribuição**
    - (=) (atribuição)
    - (+=)(adição + atribuição)
    - (-=)(subtração + atribuição)
    - (*=)(multiplicação + atribuição)
    - (/=)(divisão + atribuição)
    - (%=)(modulo + atribuição)
    - (&=)(AND + atribuição)
    - (|=)(OR + atribuição)
    - (^=)(XOR + atribuição)

* **Comparação**
    - (==) (Igual)
    - (!=)(Diferente)
    - (>)(Maior)
    - (<)(Menor)
    - (<=)(Menor Igual)
    - (>=)(Maior Igual)
 
 * **Logico**
    - (&&) (AND Lógico)
    - (||)(OR Lógico)
    - (!)(NOT)

## Strings
* **Acesso**
    - [0] 
* **Trocar Valor**
    - string oi = "Hello"
    - [0] = "J"
    - cout << oi << endl;
    - "Jello"

## Math
* **Funcoes Matemáticas**
    - max()
    - min()
    - sqrt()
    - round()
    - log()
    - abs(x)	
    - acos(x)	 
    - asin(x)	
    - atan(x)	
    - cbrt(x)	 
    - ceil(x)	
    - cos(x)	
    - cosh(x)	
    - exp(x)	
    - expm1(x)	
    - fabs(x)	
    - fdim(x, y)	
    - floor(x)	
    - hypot(x, y)	
    - fma(x, y, z)
    - fmax(x, y)	
    - fmin(x, y)	
    - fmod(x, y)	
    - pow(x, y)	
    - sin(x)	
    - sinh(x)	
    - tan(x)	
    - tanh(x)

## Arrays
* **Declaração** 
    - string carros[4] = {"onix", "palio", "x5", "a3" }
* **Tamanho** 
    - sizeof(carros)
    - 128bytes
    - sizeof(carros) / sizeof(int)
    - 4    

* **Multidimensão**
    - [Linha][Coluna]
    - string letras[2][4] = {
  { "A", "B", "C", "D" },
  { "E", "F", "G", "H" }
};

## Orientação A Objetos (OO)
* **Criar Clasee** 
    - class MyClass{}
* **Métodos**
    - void method(){}
* **Construtores**
    - MyClass(){}
* **Especificador de Acesso**
    - public :
    - private :
    - protected :
* **Encapsulamento**
    - setSalario(int salario){return salario;}
    - getSalario(){return salario;}
* **Herança**
    - ***class Carro{}***
    - ***class Veiculo {}***
    - class Carro: public Veiculo