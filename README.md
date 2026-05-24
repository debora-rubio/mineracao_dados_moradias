# Projeto de Mineração de Dados: Análise Demográfica e Ocupação Domiciliar em SP.

Este projeto tem como objetivo realizar a mineração de dados para identificar padrões de ocupação em domicílios no Estado de São Paulo, utilizando dados do Censo Demográfico do IBGE SIDRA.

# Objetivo da Análise
A análise foca em compreender a relação entre o perfil demográfico (faixa etária e gênero dos moradores) e a média de moradores por domicílio, investigando como diferentes grupos populacionais ocupam o espaço habitacional no estado de São Paulo.

# Metodologia
- **Base de Dados**: Integração de dados das tabelas 4712 (Domicílios Particulares Ocupados) e 10243 (Média de moradores por idade e sexo) do IBGE SIDRA.

- **Técnicas Aplicadas**:

  - **Pré-processamento**: Tratamento, normalização e discretização de variáveis demográficas.
  - **Agrupamento**: Algoritmo K-Means com definição do número de grupos via Método do Cotovelo.
  - **Associação**: Algoritmo Apriori para extração de regras de comportamento demográfico e padrões de ocupação.

# Resultados
O estudo identifica padrões consistentes de ocupação, revelando correlações significativas entre gênero, faixa etária e a densidade média de moradores por domicílio no estado, validando a eficácia das técnicas de mineração de dados na interpretação de estatísticas populacionais.


