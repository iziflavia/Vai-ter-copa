//Vai-ter-copa utilizando função EOF

# include <stdio.h>
 
int main () {
     
    //Iniciando e declarando variáveis.
    int N;
 
    while(scanf("%d", &N) != EOF){ /*Condição com EOF utilizado para funções de teste, ele é utilizado para evitar erros, 
                                    gerando sempre falso até que o fim do arquivo seja alcançado, podendo substituir o FOR e 
                                    permitindo que o laço While tenha um fim.*/
                                     
         if(N==0){ //Condição no qual informa que se não houver reclamações o programa imprime na tela "vai ter copa!".
            printf("vai ter copa!\n");
        }
           else{//Caso a condição não se encaixe na primeira condição e haja uma ou mais reclamações o programa irá imprimir "vai te duas!".
            printf("vai ter duas!\n");
           }
    }
    return 0;
}

