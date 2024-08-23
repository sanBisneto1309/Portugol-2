# Portugol-2
Repositório de condicionais em Portugol

1-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 22/08/2024
Var

velocidade, multa, velocidadePermitida, valorPorKm: real

Inicio
velocidadePermitida:= 80
valorPorKm:= 5

Escreval("Digite a velocidade do carro em Km/h")
leia(velocidade)
Se(velocidade>velocidadePermitida) entao
multa:= (velocidade - velocidadePermitida) * valorPorKm
Escreval("Você estará sendo MULTADO! O valor da multa é de R$", multa)
SeNao
Escreval("Você está dentro do limite de velocidade, tenha um bom dia!")
Fimse
Fimalgoritmo
---------------------------------------------------------
2-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 20/08/2024
Var
idade: real

Inicio
Escreval("Quantos anos você tem?")
leia(idade)
Se(idade)>=16 entao
Escreval("Você pode votar")
SeNao
Se(idade)<16 entao
Escreval("Você não pode votar")
Fimse
Fimse
Fimalgoritmo
--------------------------------------------------------
3-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 20/08/2024
Var
nota1, nota2: real

Inicio
Escreval("Digite a primeira nota")
leia(nota1)
Escreval("Digite a segunda nota")
leia(nota2)
Se(nota1+nota2%2)>=7 entao
Escreval("Você teve um bom aproveitamento, parabéns!")
SeNao
Se(nota1+nota2%2)<7 entao
Escreval("Você não teve um bom aproveitamento, estude mais da próxima vez.")
Fimse
Fimse
Fimalgoritmo
---------------------------------------------------------------------------------
4-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 22/08/2024
Var

ano: inteiro

Inicio
Escreval("Digite um ano: ")
leia(ano)
Se(ano % 4 = 0) e ((ano % 100 <>0) ou (ano % 400 = 0)) entao
Escreval("O ano", ano, " é bisexto")
SeNao
Escreval("O ano ", ano, " não é bisexto")
Fimse
Fimalgoritmo
----------------------------------------------------------------------------------
5-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 20/08/2024
Var
nome: caractere
sexo, desconto, valor: real

Inicio
Escreval("Digite seu nome")
leia(nome)
Escreval("Olá, ", nome,", Digite seu sexo")
Escreval("1 - HOMEM")
Escreval("2 - MULHER")
leia(sexo)
EscrevaL("Qual o valor total das compras?: R$")
leia(valor)
Se(sexo)=1 entao
Escreval("O total deu R$", valor*5/100)
SeNao
Se(sexo)=2 entao
Escreval("O total deu R$", valor*13/100)
Fimse
Fimse
Fimalgoritmo
-------------------------------------------------------------------
6-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 21/08/2024
Var

numero1, numero2: inteiro

Inicio
Escreval("Digite o primeiro número")
leia(numero1)
Escreval("Digite o segundo número")
leia(numero2)
Se(numero1)>numero2 entao
Escreval("O primeiro é o maior número")
Escreval("O segundo é o menor número")
SeNao
Se(numero2)>numero1 entao
Escreval("O segundo é o maior número")
Escreval("O primeiro é o menor número")
SeNao
Se(numero2)=numero1 entao
Escreval("Os dois números são iguais")
Fimse
Fimse
Fimse
Fimalgoritmo
-------------------------------------------------------------------
7-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 21/08/2024
Var

largura, comprimento: real

Inicio
Escreval("Digite a largura do terreno em m")
leia(largura)
Escreval("Digite o comprimento do terreno em m")
leia(comprimento)
Escreval("A área do terreno é de ", largura*comprimento, "m²")
Se(largura*comprimento)<100 entao
Escreval("O terreno está abaixo de 100m², então é considerado um TERRENO POPULAR")
SeNao
Se(largura*comprimento)>=100 entao
Escreval("O terreno está acima de 100m² e abaixo de 500m², então é considerado um TERRENO MASTER")
SeNao
Se(largura*comprimento)<=500 entao
Escreval("O terreno está acima de 100m² e abaixo de 500m², então é considerado um TERRENO MASTER")
SeNao
Se(largura*comprimento)>500 entao
Escreval("O terreno está acima de 500m², então é considerado um TERRENO VIP")
Fimse
Fimse
Fimse
Fimse
Fimalgoritmo
-------------------------------------------------------------------
8-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 22/08/2024
Var
    nome : caractere
    salario, novoSalario : real
    anosTrabalho : inteiro
Inicio
    escreva("Digite o nome do funcionário: ")
    leia(nome)
    escreva("Digite o salário atual de ", nome, ": R$ ")
    leia(salario)
    escreva("Digite quantos anos ", nome, " trabalha na empresa: ")
    leia(anosTrabalho)

    se (anosTrabalho < 3) entao
        novoSalario := salario * 1.03
    senao
        se (anosTrabalho >= 3) e (anosTrabalho < 10) entao
            novoSalario := salario * 1.125
        senao
            novoSalario := salario * 1.20
        fimse
    fimse

    escreva("O novo salário de ", nome, " é: R$ ", novoSalario:0:2)
fimalgoritmo
-------------------------------------------------------------------
9-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 22/08/2024
Var
    valorCasa, salario, anos, prestacaoMensal, limite: real
Inicio
    escreva("Digite o valor da casa: ")
    leia(valorCasa)

    escreva("Digite o salário do comprador: ")
    leia(salario)

    escreva("Digite em quantos anos será pago: ")
    leia(anos)

    prestacaoMensal := valorCasa / (anos * 12)

    limite := salario * 0.30

    se prestacaoMensal > limite entao
        escreva("Empréstimo negado. A prestação mensal de R$", prestacaoMensal:0:2, " excede 30% do salário.")
    senao
        escreva("Empréstimo aprovado! A prestação mensal será de R$", prestacaoMensal:0:2)
    fimse
fimalgoritmo
-------------------------------------------------------------------
10-
Algoritmo "algoritmo-1"
// Disciplina   : [Linguagem e Lógica de Programação]
// Descrição   : Tarefa de Portuglol Condicionais
// Autor(a)    : Antônio Santiago
// Data atual  : 23/08/2024
Var
    tipoCarro: caractere
    diasAluguel: inteiro
    kmPercorridos, precoTotal, precoDiaria, precoKm: real
Inicio
    escreva("Digite o tipo de carro (P para popular, L para luxo): ")
    leia(tipoCarro)
    escreva("Digite o número de dias de aluguel: ")
    leia(diasAluguel)
    escreva("Digite a quantidade de Km percorridos: ")
    leia(kmPercorridos)

    se (tipoCarro = "P") ou (tipoCarro = "p") entao
        precoDiaria := 90
        se (kmPercorridos)<= 100 entao
            precoKm := kmPercorridos * 0,20
        senao
            precoKm := kmPercorridos * 0,10
        fimse
    senao
    se (tipoCarro = "L") ou (tipoCarro = "l") entao
        precoDiaria := 150
        se (kmPercorridos) <= 200 entao
            precoKm := kmPercorridos * 0,30
        senao
            precoKm := kmPercorridos * 0,25
        fimse
    fimse
    fimse
    precoTotal := (diasAluguel * precoDiaria) + precoKm

    escreva("O preço total a ser pago é R$", precoTotal:0:2)
fimalgoritmo
-------------------------------------------------------------------
