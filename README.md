# Questões do teste_target
Olá a todos obrigado pela oportunidade. As questões 1 e 2 foram programadas em Java, na IDE Eclipse, o arquivo de cada questão está comprimido, as outras questões enviei junto com o link deste repositorio no formulario do teste porém também constam aqui.
Leonardo César


1) Dado a sequência de Fibonacci, onde se inicia por 0 e 1 e o próximo valor sempre será a soma dos 2 valores anteriores (exemplo: 0, 1, 1, 2, 3, 5, 8, 13, 21, 34...), escreva um programa na linguagem que desejar onde, informado um número, ele calcule a sequência de Fibonacci e retorne uma mensagem avisando se o número informado pertence ou não a sequência.

IMPORTANTE: Esse número pode ser informado através de qualquer entrada de sua preferência ou pode ser previamente definido no código;

2) Escreva um programa que verifique, em uma string, a existência da letra ‘a’, seja maiúscula ou minúscula, além de informar a quantidade de vezes em que ela ocorre.

IMPORTANTE: Essa string pode ser informada através de qualquer entrada de sua preferência ou pode ser previamente definida no código;

3) Observe o trecho de código abaixo: int INDICE = 12, SOMA = 0, K = 1; enquanto K < INDICE faça { K = K + 1; SOMA = SOMA + K; } imprimir(SOMA)
Ao final do processamento, qual será o valor da variável SOMA?

Resposta: O programa executará 12 vezes, incrementando a variável k em 1 a cada vez e a variável soma,
 que começa em 0  é incrementada 12 vezes pelo seu valor anterior somado ao k atual. No final o valor printado será 77.



5) Descubra a lógica e complete o próximo elemento:
a) 1, 3, 5, 7, ___
b) 2, 4, 8, 16, 32, 64, ____
c) 0, 1, 4, 9, 16, 25, 36, ____
d) 4, 16, 36, 64, ____
e) 1, 1, 2, 3, 5, 8, ____
f) 2,10, 12, 16, 17, 18, 19, ____

Resposta: 
a) 1, 3, 5, 7, _9_ (incremento por 2)
b) 2, 4, 8, 16, 32, 64, _128__ (dobro)
c) 0, 1, 4, 9, 16, 25, 36, _49__ (sequência do quadrado dos números naturais)
d) 4, 16, 36, 64, _100__ (quadrado dos números naturais pares a partir do 2)
e) 1, 1, 2, 3, 5, 8, _13__ (Sequência de Fibonacci, anterior + atual = próximo )
f) 2,10, 12, 16, 17, 18, 19, _20__ (A partir do 16 vai sendo somado 1)


6) Você está em uma sala com três interruptores, cada um conectado a uma lâmpada em salas diferentes. Você não pode ver as lâmpadas da sala em que está, mas pode ligar e desligar os interruptores quantas vezes quiser. Seu objetivo é descobrir qual interruptor controla qual lâmpada. Como você faria para descobrir, usando apenas duas idas até uma das salas das lâmpadas, qual interruptor controla cada lâmpada? 

Resposta: Se aproposta for que eu tenho 1 sala com 3 interruptores e 3 salas separadas, 1 com uma lampada referente a um interruptor diferente.
Só há uma possibilidade de resolver o enígma que é o caso de ligarmos duas lampadas quaisquer e de que visitamos na primeira vez uma sala em que a lampada está apagada.
Com isso identificamos com sorte uma das relações interruptor-lâmpada, apos isso temos que apagar um dos dois interruptores acesos e visitar uma das duas outras salas, caso a luz da sala visitada estiver acesa, o interruptor aceso corresponde a ela e
o interrupptor desligado corresponde a última sala que ainda não foi verificada. Caso contrário e a luz da sala visitada estiver apagada então interruptor que foi desligado corresponde a essa sala e a ultima sala correponde ao interruptor que ainda estava
acionado. Resumindo, podemos achar a resposta se no início tivermos sorte de entrarmos na sala com a luz apagada.
