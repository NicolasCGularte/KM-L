# KM-L




Parte 1
Escrever um algoritmo e um programa para efetuar o cálculo da quantidade de litros de combustível necessarios em uma viagem, de longa distancia,
considerando o consumo por litro do automovel, e que informe o valor em combustivel gasto na viagem, considerando tambem o valor por litro atual.

Parte 2
Para obter o cálculo, o usuário deverá fornecer a distancia à percorrer(d_km), o consumo do automovel por litro(c_km) e o valor atual do combustivel(preco_c).

Parte 3
Desta forma, será possível obter a a quantidade de litros consumidos com o calculo c_km*d_km
Parte 4
Tendo o valor do combustivel atual, será possivel obter o valor total gasto em combustivel com o seguinte calculo, do consumo total de combustivel multiplicado pelo valor atual do combustivel.

Parte 5
O programa deverá apresentar a quantidade de litros de combustível utilizados na viagem, e o valor total gasto em combustivel.

algoritmo "semnome"

var

d_km, c_km, preco_c, cg, vg : real

inicio

EscrevaL("-----------------------------------------")

EscrevaL

EscrevaL("Informe a distancia da viagem em Km :")
Leia(d_km)
EscrevaL("Informe o consumo do carro por litro :")
Leia(c_km)
EscrevaL("Informe o valor do litro do combustivel: ")
Leia(preco_c)

EscrevaL

EscrevaL("-----------------------------------------")

cg := d_km*c_km
vg := cg*preco_c

EscrevaL("-----------------------------------------")

EscrevaL

EscrevaL("A quantida de combutivel necessaria para a viagem é :", cg)
EscrevaL("O valor gasto em combustivel na viagem foi de :", vg:4:2)

EscrevaL

EscrevaL("-----------------------------------------")
fimalgoritmo



