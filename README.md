// Declaração de variáveis e bibliotecas 
#include <stdio.h> 
#include <string.h>
#include <stdbool.h>


int main (){
char email [50];
char validarEmail;

//================ login =================

    //Função que válida o e-mail com verificações básicas. 
    bool validarEmail(const char *email) {
        //Procurar o arroba
        const char *arroba = strchr (email,'@');
        //Se não tiver arroba ou arroba for primeiro, retornar falso.
        if ( !arroba || arroba == email ) return false;
        
        const char *ponto = strchr (email, '.');
        
        if char !ponto || ponto <= arroba +1) return false;
    
    



}
return 0;
}