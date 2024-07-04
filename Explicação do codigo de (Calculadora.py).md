Calculadora em python que realiza operaçao matematica entre 2 numeros

O codigo inicialmente irá pedir ao usuário para que insira um numero qualquer para realizar uma operaçao matematica 
que é o (valor1). através da linha: valor1 = input("digite um numero: \n")

ele é convertido para um valor flutuante (valor1_float) na linha seguinte do codigo em: valor1_float = float(valor1) 
pois a calculadora pode realizar operações com numeros quebrados usando o ponto (.) 
ex: 1.5

(op) é a operação a ser inserido pelo usuário através de um numero, como eu queria apenas 4 operações , numerei as operações em:
1 para adição
2 para subtração
3 para multiplicação
4 para divisão
ou seja o codigo ficou assim: 
op = input("Qual operação quer fazer? digite apenas o número."
"\n (1) Adição. \n (2) Subtração.\n (3) Multiplicaçao.\n (4) Divisão.\n  ")

obs: como esse texto todo estava enorme no condigo, utilizei o \n para descer uma linha na hora da execuçao

usando op_convert = int(op) para converter o valor inserido em (op) em um numero inteiro

logo em seguida o codigo pedirá para ser inserido um outro valor para a realização da operação matematica entre 2 numeros
o (valor2) e logo em seguida converte-lo em um valor flutante igualmente aconteceu ao valor1
valor2 = input("digite um segundo numero: \n")
valor2_float = float(valor2)

Usando condicionamento (if) e (elif) , criei as condiçoes para a realizaçao dos calculos

assim quando o usuario colocar o valor de 1 a 4 em (op) ele será convertido em (op_convert) que é um numero inteiro int(op)
para as condições funcionarem
ex: 

if op_convert == 1:
  print('Resultado da soma: ', valor1_float + valor2_float)
  
ou seja quando em (op) = 1 , o (op_convert) será igual (1) assim o codigo vai interpretar que (1) é pra pegar o (valor1) e somar com o (valor2) 
e mostrará o resultado final da adição.

elif op_convert == 2:
  print('Resultado da subtração: ', valor1_float - valor2_float)

ou se quando em (op) = 2 , o (op_convert) será igual (2) assim o codigo vai interpretar que (2) é pra pegar o (valor1) e subtrair o (valor2) 
e mostrará o resultado final da subtração.

e assim por diante no restante do codigo
