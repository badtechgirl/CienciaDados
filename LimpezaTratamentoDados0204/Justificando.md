Análise exploratória:

Verificar os primeiros registros do DataFrame fornece uma visão geral dos dados e ajuda a identificar possíveis problemas de formatação ou conteúdo.
Identificar valores nulos é essencial para o tratamento adequado dos dados e para evitar erros em análises subsequentes.
Estatísticas descritivas ajudam a entender a distribuição dos dados e a identificar valores atípicos ou fora do padrão.
A visualização da distribuição dos dados usando boxplots ajuda a identificar outliers de forma visual.
Tratamento dos dados:

Preencher valores nulos com a mediana é uma abordagem robusta para evitar a influência de outliers, diferente da média que pode ser afetada por valores extremos.
O método do IQR (Interquartile Range) é uma técnica eficaz para identificar e remover outliers, garantindo que a análise subsequente seja mais precisa.
Remover outliers nas colunas 'score', 'nivel' e 'idade' ajuda a garantir que os dados analisados estejam dentro de um intervalo aceitável e livre de valores extremos.
Recalcular as estatísticas descritivas após o tratamento dos dados confirma que os outliers foram removidos e que os dados estão dentro do padrão esperado.
