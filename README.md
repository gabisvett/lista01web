# lista01web
Lista 01 programação web

Esses exercícios devem ajudá-lo a praticar e entender melhor os tipos de dados
primitivos em JavaScript.

Exercício 1: Crie uma variável chamada idade e atribua a ela sua idade. Em seguida, exiba a
idade no console.

let idade = 18
console.log ("Minha idade é ",idade)


Exercício 2: Crie uma variável chamada nome e atribua a ela seu nome. Em seguida, exiba
seu nome no console.

const Nome = "Gabrielle Vitória"
console.log ("Meu nome é ",Nome)


Exercício 3: Crie uma variável chamada isEstudante e atribua a ela um valor booleano
representa

const isEstudante = true
console.log (isEstudante)


Exercício 4: Crie duas variáveis numéricas, numero1 e numero2, e realize as seguintes
operações:

● Soma dos números.

● Subtração dos números.

● Multiplicação dos números.

● Divisão dos números.

Exiba os resultados no console.

let numero01 = 3
let numero02 = 7 
console.log (numero01+numero02)
console.log (numero01-numero02)
console.log (numero01*numero02)
console.log (numero01/numero02)


Exercício 5: Crie uma variável chamada frase e atribua a ela uma frase em forma de string.
Em seguida, exiba a frase no console.

const frase = "eu sou uma garota dos programa"
console.log(frase)


Exercício 6: Crie uma variável chamada tamanhoFrase e atribua a ela o comprimento da
frase do exercício anterior. Exiba o valor no console.

const frase = "gabrielle vitória é demais"
let tamanhoFrase = frase.length
console.log(tamanhoFrase)


Exercício 7: Crie uma variável chamada temNumero e atribua a ela um valor booleano que
indique se a frase do exercício 5 contém algum número. Exiba o valor no console.

const frase = "gabrielle vitória é demais"
temNumero = /\d/.test(frase)


Exercício 8: Crie uma variável chamada listaDeCompras e atribua a ela uma lista (array) de
strings representando itens de uma lista de compras. Exiba a lista no console.

let listaDeCompra = ["Cerveja" , "Picanha" , "Salsicha" , "Pinga"]
console.log(listaDeCompra)



Exercício 9: Crie uma variável chamada primeiroItem e atribua a ela o primeiro item da lista
de compras do exercício anterior. Exiba o valor no console.

let listaDeCompra = ["Cerveja" , "Picanha" , "Salsicha" , "Pinga"]
let primeiroItem = listaDeCompra[0]
console.log(primeiroItem)


Exercício 10: Crie uma variável chamada ultimoItem e atribua a ela o último item da lista de
compras do exercício 8. Exiba o valor no console.

let listaDeCompra = ["Cerveja" , "Picanha" , "Salsicha" , "Pinga"]
let ultimoItem = listaDeCompra[3]
console.log(ultimoItem)

Exercício 11: Crie uma variável chamada idadeString e atribua a ela sua idade como uma
string. Em seguida, converta essa string em um número inteiro e exiba no console.

let idadeString = "18"
console.log(parseInt(idadeString))

Exercício 12: Crie uma variável chamada precoProduto e atribua a ela um número decimal
representando o preço de um produto. Arredonde o preço para o inteiro mais próximo e
exiba o valor no console.

const precoProduto = "68.99"
const precoNovo = Math.round(precoProduto)
console.log(precoNovo)
