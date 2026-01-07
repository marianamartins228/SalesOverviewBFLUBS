# Sales Overview Dashboard - 2022 Analysis
Este projeto foi desenvolvido como parte do curso do professor Bruce Fonseca. O objetivo principal foi transformar dados brutos de vendas em uma solução analítica interativa no Power BI, permitindo que gestores visualizem a performance de vendas, margens de lucro e distribuição geográfica de forma rápida e eficiente.

## Visão Geral do Projeto
O dashboard apresenta uma análise detalhada do ano de 2022, focando em KPIs essenciais como Faturamento (Revenue), Custos (Cost), Margem de Lucro (Margin) e Volume de Vendas.

<img width="1429" height="804" alt="image" src="https://github.com/user-attachments/assets/7c52a2bb-5355-4ef9-8dff-b1e13077f564" />

## Tecnologias e Recursos Utilizados
- Power BI: Construção de todo a estrutura visual e cálculos.
- DAX: Criação de medidas personalizadas para análise de performance.
- Power Query: Tratamento e limpeza dos dados.
- UX/UI Design: Implementação de menu retrátil e tooltips personalizados.

## Estrutura de Dados e Medidas DAX
A base de dados é composta por uma tabela de fatos principal (2022 Sales) contendo informações de vendas, clientes, localização e produtos.
As principais medidas desenvolvidas foram:
- Sales: Somatória total das vendas.
- Cost: Custo total das operações.
- Margin: Diferença entre vendas e custos ($Sales - Cost$).
- Margin %: Percentual de margem sobre o faturamento.
- Cost %: Percentual de custo sobre o faturamento.
- Volume Ton: Volume total comercializado em toneladas.

<img width="218" height="175" alt="image" src="https://github.com/user-attachments/assets/11a5669d-350b-47f3-a621-e90be3a06309" />

## Recursos Avançados de Navegação (UX)
Para tornar o dashboard mais intuitivo, foram implementados recursos avançados:
1. Menu de Filtros Retrátil: Um menu lateral que pode ser ocultado ou exibido, otimizando o espaço de tela para os gráficos sem perder o poder de segmentação por Business Line, Division, Plant e Data.

<img width="322" height="465" alt="image" src="https://github.com/user-attachments/assets/63b551c9-1f03-41f5-af3e-b0b0fd58092b" />

2. Tooltip Visual (Dica de Ferramenta): Ao passar o mouse sobre as divisões nos gráficos, o usuário visualiza um detalhamento instantâneo da performance mensal daquela categoria específica, sem precisar sair da página.

<img width="553" height="538" alt="image" src="https://github.com/user-attachments/assets/8c837949-d13b-4bf2-898e-b9ab58f2b4ff" />

3. Drill-through para Detalhamento: Possibilidade de clicar com o botão direito em um dado e "mergulhar" em uma página de Sales Detail, que traz o grão mais fino da informação (nível de pedido e cliente).

<img width="1428" height="800" alt="image" src="https://github.com/user-attachments/assets/a51d5598-c1ee-4fc0-9645-3c5ca4eea7a1" />

4. Os dados permitiram a visualização geográfica das vendas ao utilizar o Azure Maps, em que é possível ver a proporção em detalhes por região.

<img width="720" height="634" alt="image" src="https://github.com/user-attachments/assets/c815931c-deda-4119-9632-c037688c9888" />

## Insights Obtidos
Com esta visualização, é possível identificar:
- Performance por Região: A divisão "Centroeste/Sudeste" representa a maior fatia do faturamento (160,79 Mi).
- Mix de Produtos: A linha de "Lubrificantes" domina o volume de vendas comparado a "Aditivos".
- Saúde Financeira: Manutenção de uma margem média de 56%, com monitoramento em tempo real dos custos.

## Conclusão e Entrega de Valor
Este projeto vai além da simples visualização de dados: ele entrega uma ferramenta de Self-Service BI que empodera o gestor. Através da implementação de recursos como o drill-through e tooltips visuais, a solução reduz o tempo de análise e permite que a equipe saia de uma visão macro para o detalhe operacional em apenas dois cliques.
A construção deste dashboard consolidou conhecimentos em modelagem de dados, otimização de cálculos em DAX e, principalmente, em como aplicar princípios de UX para criar uma experiência de análise fluida e intuitiva.
