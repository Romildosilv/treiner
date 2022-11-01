treiner
Algoritmos //

#include <stdio.h>
#include <math.h>
float ladoa,ladob,quadrado;

int main()
{
  printf("digite o lado a: ");
  scanf("%f",&ladoa);
  printf("\ndigite o lado b: ");
  scanf("%f",&ladob);
   quadrado=ladoa*ladob;
if(quadrado>=0 && quadrado<=200000)
 {
   printf("\nO valor do quadrado = %.2f",quadrado);
   quadrado=quadrado*2;
   printf("\no dobro do quadrado = %.2f",quadrado);
 }
 else {
 printf ("\n quadrado invalido***********");
 }
 
 return 0;
}

