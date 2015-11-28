# Introdução a funções

Você notou que no dojo anterior usamos duas coisinhas para conseguirmos o que queríamos?
* upper()
* len('exemplo')

Esses dois códigos são chamadas para funções. 

Funções são partes do código que servem para fazer algo expecífico. As funções geralmente tem:
* Entrada
* Saída

No exemplo do dojo: ```len()```
* teve como entrada uma string (o seu nome)
* teve como saída o número que dizia quantos caracteres tem na string dada como entrada (quantas letras tem no seu nome)

Você pode ter se perguntando porque usamos ```upper()``` e ```len() ```de forma diferente. Chamamos ```'seunome'.uper()``` e ```len('seunome')```. 
É porque  em alguns casos, funções pertencem a objetos, como ```upper()```, que só pode ser utilizada em strings. Nesse caso, nós chamamos a função de ```método```. Outras vezes, funções não pertencem a nada específico e podem ser usadas em diferentes tipos de objetos, assim como ```len()```. É por isso que nós estamos fornecendo 'seunome' como um parâmetro para a função ```len```.

Mas não se preocupe, isso ficará mais claro para você no futuro e você voltará para reler essa parte e compreenderá melhor ;-) 
