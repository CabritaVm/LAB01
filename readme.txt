#!/bin/sh

echo "  Um recurso poderoso do sistema Entrez é que ele pode armazenar conjuntos de UIDs recuperados temporariamente nos servidores para que possam ser combinados posteriormente ou fornecidos como entrada"
echo "para outras chamadas de E-utility. O servidor Entrez History fornece esse serviço e é acessado na Web usando as guias Visualizar/Índice ou Histórico nas páginas de pesquisa do Entrez."
echo "  Cada um dos utilitários eletrônicos também pode usar o servidor de histórico, que atribui a cada conjunto de UIDs um rótulo inteiro chamado chave de consulta (&query_key) e uma sequência de cookies codificada "
echo "chamada ambiente da Web (&WebEnv). O EPost permite que qualquer lista de UIDs seja carregada no History Server e retorna a chave de consulta e o ambiente da Web. "
echo "  O ESearch também pode postar seu conjunto de UIDs de saída para o History Server, mas somente se o parâmetro &usehistory estiver definido como “y”. O ELink também pode postar sua saída no " 
echo "servidor de histórico se &cmd estiver definido como ""neighbor_history"". A chave de consulta e o ambiente da Web resultantes do EPost ou do ESearch podem ser usados ​​no lugar de uma "
echo "lista UID em ESummary, EFetch e ELink."
