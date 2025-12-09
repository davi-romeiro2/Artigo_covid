# Artigo_covid

Visão Geral do Projeto

Este projeto tem como objetivo analisar a relação entre a incidência de casos e a mortalidade por COVID-19 nos estados brasileiros, considerando como fator central a infraestrutura de saúde disponível em cada região. A análise parte do pressuposto de que o impacto da pandemia não pode ser explicado apenas pelo número absoluto de casos, mas também pela capacidade hospitalar de resposta, especialmente em situações de alta demanda por atendimento crítico.

Os resultados mostram que estados mais populosos apresentam maior número absoluto de casos e óbitos, porém tendem a ter taxas de letalidade mais controladas. Em contrapartida, estados com menor população apresentaram crescimento mais acelerado da mortalidade, mesmo com menor volume de casos. Isso indica que fatores estruturais, como quantidade absoluta de leitos, leitos de UTI, distribuição regional e capacidade técnica do sistema de saúde, influenciam diretamente os desfechos observados.

A análise evidencia fortes desigualdades regionais no sistema de saúde brasileiro, reforçando a importância de avaliar não apenas indicadores per capita, mas também a capacidade real de absorção de pacientes graves em contextos de crise sanitária.

Metodologia Técnica e Construção dos Gráficos
Linguagem e Bibliotecas Utilizadas

Toda a análise foi desenvolvida em Python, utilizando principalmente as seguintes bibliotecas:

Pandas: para leitura, organização, limpeza e manipulação dos dados.

Matplotlib: para criação e customização dos gráficos utilizados na análise exploratória e comparativa.

Bases de Dados Utilizadas
Base Principal – Brasil.io

A principal fonte de dados utilizada foi o Brasil.io, que disponibiliza dados públicos consolidados sobre a COVID-19 no Brasil. Essa base fornece informações como:

Número acumulado de casos por estado

Número acumulado de óbitos

Dados organizados por período e unidade federativa

Esses dados foram importados diretamente para o código em formato tabular, tratados com Pandas e utilizados como base dinâmica para geração dos gráficos.

Base Secundária – Fonte Online sem Arquivo

Além da base principal, foi utilizada uma segunda fonte de dados referente à infraestrutura hospitalar. Essa base não possui arquivo para download, existindo apenas como visualização direta em um site, acessível exclusivamente de forma manual.

Dessa forma, os valores relevantes foram:

Observados diretamente no site

Interpretados visualmente

Inseridos manualmente no código como dados estáticos

Esses dados estáticos foram utilizados especificamente para fins de comparação, permitindo relacionar os indicadores epidemiológicos com a infraestrutura hospitalar disponível nos estados analisados.

Construção dos Gráficos

Após o tratamento dos dados, foram gerados diferentes tipos de gráficos, incluindo:

Gráficos de barras para comparação entre estados

Gráficos de dispersão para análise de relação entre variáveis (ex.: população, casos e mortalidade)

Os gráficos foram construídos a partir de DataFrames do Pandas e renderizados com Matplotlib, permitindo uma visualização clara das diferenças regionais e dos padrões observados nos dados.

Considerações Finais Técnicas

A combinação entre dados dinâmicos (Brasil.io) e dados estáticos (extraídos manualmente de fonte online) permitiu uma análise comparativa consistente, mesmo diante da limitação de acesso a arquivos estruturados. O uso de Python, Pandas e Matplotlib garantiu reprodutibilidade, clareza e flexibilidade na análise dos dados, tornando o projeto adequado tanto para fins acadêmicos quanto para estudos exploratórios em ciência de dados aplicada à saúde pública.
