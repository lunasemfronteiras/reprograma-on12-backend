## Algoritmos

_Os exercícios a seguir devem ser resolvidos em linguagem natural, utilizando estrutura de narrativa, fluxograma ou pseudocódigo. Consulte a professora!_

1. Faça um algoritmo que mostre o passo a passo de uma troca de lâmpada queimada.

```
Ligo o interruptor
    se a luz acender finalizo 
    senao
       pego a escada e uma lampada
       subo a escada
       retiro a lampada queimada
       coloco a lampada nova
       desço a escada
       guardo a escada
       jogo a lampada queimada fora
repete Ligo o interruptor

```

2. Faça um algoritmo que mostre o passo a passo de uma lavar pratos.

```
    Vou até a pia
    verifico pratos da pia
	se pratos na pia estiverem limpos finalizo a ação
	senao
		pego bucha de lavar louça
        ligo a torneira
		molho a bucha
        desligo a torneira
		coloco sabão ou detergente na bucha
		esfrego a bucha nos pratos  um a um
		coloco bucha de lado
        ligo a torneira
		enxaguo prato
        desligo a torneira
         verificando se estão limpos
			se limpos
				coloco no escorredor
	senao repete verifico pratos da pia

```		


3. Faça um algoritmo que mostre o passo a passo de uma troca de um pneu furado.

```
Estacione o carro em um lugar seguro 
verifico o pneu
se tiver não tiver furado finalizo
senao
    Prepare o carro
    Pegue o estepe e o macaco
    Levante o macaco até que ele apoie o carro
    Tire a calota e afrouxe os parafusos
    Levante um pouco mais o pneu
    Remova os parafusos e o pneu
    Ponha o estepe no eixo
    Aperte os parafusos
    Desça o carro e retire o macaco
senao repete todo o processo

```



4. Faça um algoritmo que mostre o passo a passo de um débito num caixa eletrônico.

```
ir até o caixa eletrônico escolhido 
	insiro cartão 
    digito a senha
	espero processamento
	vou a opção de débito 
	informar o valor desejado 
    informar chave de acesso 
	aguardo contagem de notas
    retiro o cartão
	retiro notas da saída 
	encerro a operação

```

5. Faça um algoritmo que mostre o passo a passo de um professor corrigindo uma pilha (de quantidade indefinida) de provas, com 5 questões cada.

Pegue as provas. 
    Corrigir questão por questao.
    Se o aluno acertou todas as questões, fica com 10. 
    Se errou uma questão, fica com 8.
    Se errou duas questões, fica com 6.
    Se errou três questões, fica com 4. 
    Se errou quatro questões, fica com 2.
    Se errou todas as questões, fica com 0. 
    Coloque as notas no boletim do aluno

6. Faça um algoritmo que represente a brincadeira "Morto! Vivo!".

``` 

Quando ele disser morto todas as crianças deverão se agachar. 
Quando ele disser "vivo", todas dão um pulinho e ficam em pé. 
Quem errar e ficar agachado quando for para ficar em pé, ou vice-versa, sai do jogo. 
A brincadeira continua até restar apenas um participante, que será o vencedor e vira o próximo líder.

```

7. Faça um algoritmo que some três números.

```
escrever "informe o primeiro numero"
ler n1
escrever "informe o segundo numero"
ler n2
escrever "informe o terceiro numero"
ler n3
soma = n1 + n2 + n3 
escrever soma

```
8. Faça um algoritmo que descubra se um número é par ou ímpar.

```
Var
numero : inteiro

Inicio

       escreva("Escreva um número: ")
       leia(numero)

       se numero mod 2 = 0 entao
           escreva("O número ", numero, " é par!")
       senao
           escreva("O número ", numero, " é ímpar!")
       fimse


```


9. Faça um algoritmo para calcular a média aritmética entre duas notas de um aluno e mostrar sua situação, que pode ser aprovado ou reprovado.

```

Pegue prova v1 e prova v2
somar v1 + v2
o resultado da soma dividir por 2

```


10. Faça um algoritmo para calcular o novo salário de um funcionário. Sabe-se que os funcionários que recebem atualmente salário de até R$500 terão aumento de 20%; os demais terão aumento de 10%.

``` 

Se salário menor ou igual a quinhentos. 
Salário vezes vinte dividido por cem. 
Salário mais a porcentagem calculada. 
Senao salário vezes dez dividido por cem. 
Salário mais a porcentagem calculada.

```