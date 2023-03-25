# desafio_bolas_de_canhao
#include <stdio.h>

int main() {
    char escolha;
    do {
    int nbase;
    printf("Por quantas bolas e formado cada lado da base do tetraedro? \n");
    scanf("%d", &nbase);

    int ntotal = 0;
    int bolcam = nbase;
    int cam = 1;
    while (bolcam >= 1){

      ntotal += (bolcam*cam);
      bolcam --;
      cam ++;
    }
    printf("O tetraedro tera %d bolas!\n", ntotal);
    printf("Deseja calcular novamente? (S) ou (N)\n");
   scanf("%s", &escolha);
}    
	while(escolha == 'S' || escolha =='s' || 	escolha == 'Sim' || escolha == 'sim');
}
