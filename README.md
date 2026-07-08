# Calculator-of-K.E-Physics-
With the values of mass and velocity it calculates K.E
#include <stdio.h>

int main()
{
    float m, v;

    printf("Enter your mass(kg), %f\n", m);
    scanf("%f", &m);

    printf("Enter your velocity(m/s), %f\n", v);
    scanf("%f", &v);

    printf("This is your kinetic energy(J), %f\n", (0.5*m*v*v));


    return 0;
}
