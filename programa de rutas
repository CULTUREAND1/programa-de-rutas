#include <stdio.h>

int main() {
    int opcion;
    printf("Menu:\n");
    printf("1. Digite la ruta de bus sobre la que desea conocer las paradas\n");
    printf("2. Conocer rutas que funcionan en feriados\n");
    printf("Seleccione una opción: ");
    scanf("%d", &opcion);

    // Si el usuario elige la opción 1
    if (opcion == 1) {
        int ruta;
        printf("Escriba el número de ruta de un BUS: ");
        scanf("%d", &ruta);

        // Imprimir las estaciones según el número de ruta
        switch (ruta) {
            case 78:
                printf("Estaciones para la ruta 78B:\n");
                printf("Parada de la Universidad\n");
                printf("Parada del Hospital\n");
                printf("Parada del Centro Comercial\n");
                break;
            case 45:
                printf("Estaciones para la ruta 45A:\n");
                printf("Parada del Paseo Marítimo\n");
                printf("Parada del Teatro\n");
                printf("Parada del Mercado\n");
                break;
            case 17:
                printf("Estaciones para la ruta 17G:\n");
                printf("Parada del Estadio\n");
                printf("Parada del Parque\n");
                printf("Parada del Barrio\n");
                break;
            default:
                printf("Número de ruta no válido.\n");
        }
    }
    // Si el usuario elige la opción 2
    else if (opcion == 2) {
        printf("Las siguientes rutas funcionan en feriados:\n");
        printf("78B\n");
        printf("45A\n");
        printf("17G\n");
    }
    // Si el usuario ingresa una opción inválida
    else {
        printf("Opción no válida.\n");
    }

    return 0;
}
