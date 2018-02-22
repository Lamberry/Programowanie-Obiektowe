#include <stdio.h>

typedef struct trojkat{

    int x;
    int y;
    int z;

}trojkat;


int function(trojkat zmienna){

    int obwod;
    obwod = zmienna.x+zmienna.y+zmienna.z;
    return obwod;

}

int main(){

    trojkat Trojkat;
    Trojkat.x = 2;
    Trojkat.y = 5;
    Trojkat.z = 1;

    int obwod = function(Trojkat);
    printf("%d", obwod);
    return 0;

}

