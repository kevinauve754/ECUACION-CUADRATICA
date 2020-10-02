# ECUACION-CUADRATICA
#include <stdio.h>

int main()
{
    float a, b, c, d, x1, x2;

    printf("COLOQUE EL PRIMER TERMINO CUADRATICO: \n");
    scanf("%f", &a);
    printf("COLOQUE EL TERMINO LINEAL: \n");
    scanf("%f", &b);
    printf("COLOQUE LA PARTE INDEPENDIENTE: \n");
    scanf("%f", &c);

    if(a==0)
    {
        printf("NO ESTA BIEN");
    }
    else
    {
        d=b*b-4*a*c;
    if (d==0)
    {
        x1=(-b)/(2.0*a);
        printf("x= %f \n",x1);
    }
    else
    {
        printf("TERMINOS INCORRECTOS");
    }
    }
}
