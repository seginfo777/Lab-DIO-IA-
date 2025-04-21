# Características

- A empresa foca apenas em fabricação de consoles, deixando a distribuição e venda para terceiros
- Os produtos são vendidos globalmente

# Objetivos

- [x] Consolidar todas as bases de terceiros para realizar uma análise
- [x] Transformar dados de vendasem informações relevantes para a fabricante
- [x] Quais são os produtos mais populares em cada país
- [x] Como otimizar o processo de transporte e logística até o momento da venda


##  Tabela de Prompts para Análise de Vendas (utilizado a versão paga do ChatGPT)

| Nº | Objetivo                                              | Prompt para IA                                                                                                  |
|----|--------------------------------------------------------|------------------------------------------------------------------------------------------------------------------|
| 1  | Obter os produtos mais vendidos por país              | Liste os produtos mais vendidos em cada país, com base na quantidade total vendida.                            |
| 2  | Descobrir qual produto é mais popular por país        | Para cada país, mostre o produto com maior número de unidades vendidas.                                        |
| 3  | Saber o total de vendas por país                      | Agrupe os dados de vendas por país e mostre a soma de unidades vendidas.                                       |
| 4  | Verificar o faturamento por país                      | Liste o total de faturamento (`total_price`) para cada país de entrega.                                        |
| 5  | Calcular a diversidade de produtos vendidos por país  | Quantos produtos diferentes foram vendidos em cada país? Mostre a contagem por país.                           |
| 6  | Identificar oportunidades logísticas                  | Com base nas vendas por país, indique onde concentrar estoques para otimizar o transporte e reduzir prazos.    |
| 7  | Criar um plano de distribuição por popularidade       | Para cada país, sugira um plano logístico baseado nos produtos mais vendidos e no volume total de vendas.      |
| 8  | Detectar regiões com baixa diversidade de produtos    | Identifique países com pouca diversidade de produtos vendidos. Mostre o número de produtos diferentes por país.|
| 9  | Cruzar vendas e cupons de desconto                    | Existe relação entre o uso de cupons de desconto e a quantidade de produtos vendidos?                          |
| 10 | Visualizar as vendas ao longo do tempo                | Mostre um gráfico de vendas por mês para identificar sazonalidades e picos de venda.                           |
