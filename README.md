# ABAP

# SEGW

Sempre implementar em ...._EXT, para a geração dos Objetos não substituir o Código.

Não consegue gerar objetos em outro idioma a não ser "EN"
Versão 20.22 entrar em Inglês, evitar DUMP

Categoria              Erro de programação ABAP
Erro tpo.exec.         UNCAUGHT_EXCEPTION
Exceção                /IWBEP/CX_SBCM_FATAL
ABAP: programa         /IWBEP/CL_SBUI_PR_CMD_GENERA
Componente de aplicaçãoOPU-BSE-SB
Data e hora            12.03.2024 13:14:34 (CET)


Catálogo de Serviços
/IWFND/MAINT_SERVICE
/IWFND/ERROR_LOG
Sempre que transportar, precisa ativar.
/IWBEP/CL_MGW_DATA_UTIL



# Postman

{{URL}}/<sodata service>/ZMCAGW_VOOS_SRV/
{{URL}}/<sodata service>/ZMCAGW_VOOS_SRV/$metadata
{{URL}}/<sodata service>/ZMCAGW_VOOS_SRV/CompanhiaAereaSet
{{URL}}/<sodata service>/ZMCAGW_VOOS_SRV/HorarioVooSet
{{URL}}/<sodata service>/ZMCAGW_VOOS_SRV/VooSet

Header
x-csrf-token	fetch
Cookie	

Params
$format	Ex: $format=json
$filter	Ex: $filter=( Carrid eq '' )
$orderby	Ex: $orderby=Carrid ASC
$top	Ex: $top=10
$skip	Ex: $skip=2
$expand	Ex: $expand=<association 1>, ..., <Association N>

