Algoritmo "Segundos"

var
   H, M, S, soma:real
   
inicio
   //Entrada de dados
   escreva("Digite as horas: ")
   leia(H)
   
   escreva("Digite os minutos: ")
   leia(M)
   
   escreva("Digite os segundos: ")
   leia(S)
   
   //Operações
   soma <- (H * 3600) + (M * 60) + S
   
   escreva("O TEMPO EM SEGUNDOS E = ", soma)
fimalgoritmo
