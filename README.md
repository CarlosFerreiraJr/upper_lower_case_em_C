Funções de Conversão de String para maiúsculo e minúsculo em C

### Converte caracteres de uma string para minusculas
```
/**************************************************************************
** Funcao          : fStrToLower()
** Descricao       : Converte caracteres de uma string para minusculas
** Parametros      : char *szStr - ponteiro para a string
** Valores Retorno : NA
******************************************************************************/
void fStrToLower(char *szStr)
{
    int iAux = 0;
    while(szStr[iAux] != NULL)
    {
        szStr[iAux] = tolower(szStr[iAux]);
        iAux++;
    }    
} /* fStrToLower */
```

### Converte caracteres de uma string para MAIUSCULAS
```
/**************************************************************************
** Funcao          : fStrToUpper()
** Descricao       : Converte caracteres de uma string para MAIUSCULAS
** Parametros      : char *szStr - ponteiro para a string
** Valores Retorno : NA
******************************************************************************/
void fStrToUpper(char *szStr)
{
    int iAux = 0;
    while(szStr[iAux] != NULL)
    {
        szStr[iAux] = toupper(szStr[iAux]);
        iAux++;
    }    
} /* fStrToUpper */
```
