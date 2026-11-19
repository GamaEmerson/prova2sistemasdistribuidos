ETAPA 3 - 
PROBLEMA A - CONCORRENCIA

MAXIMO_SIMULTANEO estava para 3, alterado para 2 de acordo com a empresa 

--------------------------------------------------------------------------

PROBLEMA b - REPLICAÇÃO E CONSISTENCIA

estava replica["estoque"] = replica["estoque"]  alterado para replica["estoque"] = principal["estoque"] 

--------------------------------------------------------------------------

PROBLEMA C - TOLERANCIA A FALHAS

if replica["online"]: 
