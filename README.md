# 📊 Análise da Incidência e Mortalidade por COVID-19 no Brasil
🧠 Visão Geral do Projeto

Este projeto tem como objetivo analisar a relação entre a incidência de casos e a mortalidade por COVID-19 nos estados brasileiros, considerando como eixo central a infraestrutura de saúde disponível em cada região.

A análise parte do princípio de que o impacto da pandemia não é explicado apenas pelo número absoluto de casos, mas também pela capacidade do sistema de saúde em atender pacientes graves, especialmente em contextos de alta demanda. Os resultados evidenciam desigualdades regionais, mostrando que estados mais estruturados conseguem manter taxas de letalidade menores, mesmo com grandes volumes de casos.

🎯 Objetivo da Análise

• Avaliar a relação entre número de casos e mortalidade por COVID-19 nos estados brasileiros
• Comparar estados com diferentes perfis populacionais
• Analisar o impacto da infraestrutura hospitalar nos desfechos da pandemia
• Evidenciar desigualdades regionais no sistema de saúde

📌 Principais Conclusões

• Estados mais populosos apresentam maior número absoluto de casos e óbitos, porém taxas de letalidade relativamente menores
• Estados menos populosos apresentaram crescimento mais acelerado da mortalidade, mesmo com menor número de casos
• A infraestrutura hospitalar exerce papel fundamental na contenção da letalidade
• A análise per capita, isoladamente, não é suficiente para explicar os resultados observados
• Fatores como capacidade absoluta de leitos, distribuição geográfica e complexidade hospitalar influenciam diretamente os desfechos

🛠️ Metodologia Técnica
💻 Linguagem e Bibliotecas Utilizadas

• Python – linguagem principal do projeto
• Pandas – manipulação, limpeza e organização dos dados
• Matplotlib – geração e customização dos gráficos

🗂️ Bases de Dados Utilizadas
✅ Base Principal – Dados Epidemiológicos

A base principal utilizada fornece dados públicos consolidados sobre COVID-19 no Brasil, incluindo:

• Casos acumulados por estado
• Óbitos acumulados por estado
• Organização por unidade federativa

Esses dados foram importados para o código em formato tabular e tratados utilizando Pandas, permitindo análises dinâmicas e reprodutíveis.

⚠️ Base Secundária – Dados de Infraestrutura Hospitalar

A base secundária utilizada apresenta uma limitação técnica importante:

• Não possui arquivo para download
• Existe apenas como visualização direta em um site
• Os dados são acessíveis apenas de forma manual

Dessa forma, os valores relevantes foram:

• Observados diretamente na plataforma online
• Interpretados visualmente
• Inseridos manualmente no código como dados estáticos

Esses dados estáticos foram utilizados exclusivamente para fins de comparação, permitindo relacionar indicadores epidemiológicos com a infraestrutura hospitalar disponível.

📈 Construção dos Gráficos

Os gráficos foram gerados a partir de DataFrames do Pandas e renderizados com Matplotlib, incluindo:

• Gráficos de barras para comparação entre estados
• Gráficos de dispersão para análise de relação entre variáveis
• Visualizações comparativas entre casos, mortalidade, população e infraestrutura

Todo o processo de plotagem foi feito diretamente em Python, garantindo controle total sobre os dados e a visualização.

✅ Considerações Técnicas Finais

• A combinação de dados dinâmicos e dados estáticos permitiu uma análise comparativa consistente
• O uso de Python garantiu flexibilidade e reprodutibilidade
• A abordagem adotada contorna limitações de acesso a dados estruturados
• O projeto é adequado para análise exploratória e estudos aplicados em saúde pública

📌 Observação:
Este README descreve exclusivamente a estrutura técnica, metodologia e lógica analítica do projeto, sem referência direta a artigos, publicações ou textos acadêmicos externos.
