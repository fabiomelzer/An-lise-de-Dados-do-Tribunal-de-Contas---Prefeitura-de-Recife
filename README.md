# Analise-de-Dados-do-Tribunal-de-Contas---Prefeitura-de-Recife
Realizei uma análise de dados das bases da prefeitura de Recife, com objetivo foi identificar inconsistências, responder a várias perguntas-chave e extrair insights valiosos dos dados. Neste repositório, vou compartilhar detalhes sobre a metodologia, o código usado e os resultados obtidos.
Algumas informações importantes: 
1. Os arquivos vieram desconfigurados com relação à formatação das letras, tais como "ç", letras com acentuação e caracteres especiais - identifiquei os padrões que cada letra seguia e fiz uma substituição manualmente (foi o melhor método que identifiquei para trabalhar com esta base);
2. Fiz a transformação de colunas necessárias para as análises com relação a ponto e vírgula, para não influenciar e modificar os resultados relativos a valores (em R$);
