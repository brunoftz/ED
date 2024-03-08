
# Revisão de C - estrutura de dados

Uma breve descrição sobre o que esse projeto faz e para quem ele é

//Bibliotecas ou arquivos de cabeçalho
#include <stdio.h>
#include <stdlib.h>

#include <math.h>
//biblioteca de matematica



	int main() //Primeira função a ser executada
	{

    return 0; //Devolve ao S.O que tudo foi executado corretamente
	}


#  Variáveis e tipos (Variável = espaço reserva na memória)

* Declaração: tipo_de_variavel nome_variavel

Ex:	

	int idade = 1;
    char letra;
    

Tipos:

int -> inteiro

float & double -> ponto flutuante

char -> caractere

void -> Não tem retorno a função

#  Comandos de entrada e saída:

	printf: mostra informação na tela.

Ex:
    
	printf("Hello, world!");
    printf("%d",idade );


#  Caracteres de formatação:
            
int -> %d ou %i
            
float -> %f
            
double -> %lf
            
char -> $c (%s quando for uma string, ou seja, um vetor de caracteres)
        

* scanf: entrada de dados (leitura de valores)

	scanf("%d", &idade);
	printf("asda");
    scanf(" %c", &letra);


# operadores 

->lógicos:

'&&' > E

'||' > ou
	
aritméticos

'+'

'-'

'*'

'/'

	
* comparação
'<'

'>'

'<='

'>='



# Estrutura de controle


* if
```
	#include <stdio.h>
	#include <stdlib.h>

	int main(){
	int chovendo = 0
	if(chovendo == 0){
	printf("Nao esta chovendo");
	}
	return 0
	}
```
* if else
```
	#include <stdio.h>
	#include <stdlib.h>

	int main(){
	int num = 13;

	if num%2 == 0){
	printf("Eh par");
	}else{
	printf("Eh impar");'
	}

	return 0;

```
* switch

    ```
    int dia;
	printf("Digite o valor:");
	scanf("%d", &dia);
	switch(dia){
		case 0:
			printf("Domingo");
			break;
		case 1:
			printf("Segunda");
			break;
		case 2:
			break;

		case 3:
		.
		.
		.

		case 6: 
			break;

		default:
			printf("Dia invalido");
	}

# laços de repetição
 * For
	
```	 
	for(i=2.i<10;i++)
```
i=2 - inicializa o contador

i<10 - comparação/condição

i++ - incremento ou decremento

* While

	```
	num = 1
	while(num>0){


		num--;
	}<br><br>
   ```

* Do While

        int main(){
		int op=0;
		do{
			printf("Digite 1 para cadastrar");
  
			printf("Digite 2 para remover");
			
			printf("Digite 3 para editar");
			
			printf("Digite 0 para sair");
			
			scanf("%d",&op);
		}while(op!=0)}


for:
		quando se sabe a quantidade exata de repetições

while: 
		-estrutura de teste no início
		-executa 0 ou + vezes

do while:
		-estrutura de teste no final	
		-executa 1 ou + vezes

	
 # Vetor: é um arranjo unidimensional

 * Declaração
	```
 	int chuchu[6],i;
	```
declara-se o tipo, nome e o tamanho da variável.

* inserção dos dados
  	 ```
   	for(i=0; i<6; i++){
	scanf("%d", &chuchu[i];
	
   	}
	```

* busca de elementos

  	```
   for(i=0; i<6; i++){
	if(chuchu[i]==21{
   	printf("%d",i};	
   }
   	```
* exemplo

  ```
  #include <stdio.h>
  #include <stdlib.h>

  int main(){
    float v[4];

  //inserir dados no vetor
  for(i=0;i<4;i++){
  scanf("%f", &v[i];
  }

  //calcular a média
  for(i=o;i<4;i++){
  soma = soma + v[i];
  }

  media = soma/4
  printf("%f",media);
  }

   
