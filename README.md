Análise de Produtividade da Equipe de Programadores

Este projeto tem como objetivo realizar uma análise da produtividade da equipe de programadores ao longo de uma semana de trabalho, utilizando as bibliotecas pandas, numpy e matplotlib. O projeto visa a aplicação dos conceitos aprendidos no módulo 4 do curso.
Modo de Usar

Para executar este projeto no Google Colab, siga os passos abaixo:

    Acesse o Google Colab em https://colab.research.google.com/.

    Crie um novo notebook Python clicando em "Arquivo" e "Novo Notebook Python".

    Copie o código fornecido no projeto e cole-o em uma célula no Colab.

    Execute cada célula de código clicando no botão de execução à esquerda de cada célula ou pressionando "Shift + Enter".

    O projeto realizará as seguintes etapas:

        Transformará as informações do DataSet em quatro listas: dias, horastrabalhadas, bugscorrigidos e tarefasconcluidas.

        Criará um dicionário chamado dici a partir das listas.

        Converterá o dicionário em arrays NumPy: arraydias, arrayhorastrabalhadas, arraybugscorrigidos e arraytarefasconcluidas.

        Transformará os arrays em Series Pandas: seriesdias, serieshorastrabalhadas, seriesbugscorrigidos e seriestarefasconcluidas.

        Criará um DataFrame Pandas chamado df a partir das Series.

        Plotará gráficos de barras agrupadas e gráficos de linhas para visualizar o desempenho semanal da equipe de programadores.

        Calculará estatísticas sobre o DataFrame, incluindo médias e desvios padrão.

    Ao final da execução, você verá os gráficos e um relatório final com as conclusões da análise.

Caso deseje utilizar seus próprios dados, você pode modificar o código para adequá-lo aos novos dados a serem analisados.

Lembre-se de que a análise de dados é um processo contínuo e iterativo. Sempre busque refinar suas análises e tirar conclusões embasadas nos dados disponíveis.

Observação: O projeto utiliza um conjunto específico de dados para fins ilustrativos. Certifique-se de ter acesso aos dados ou substitua-os por seu próprio conjunto de dados antes de executar o código.

Boa análise!

# Projindividualresiliamodulo4

CONTEXTO
Uma empresa de
desenvolvimento de softwares
possui uma tabela com os
seguintes dados ao lado e deseja
um RELATÓRIO que você irá
ajudar a construir!

Este relatório tem o objetivo de demonstrar a importância da análise dos dados de um
projeto de desenvolvimento de software ao longo de uma semana. Os dados fornecidos
permitirão ao proprietário da equipe de desenvolvimento obter insights sobre o progresso
do projeto, identificar possíveis áreas de melhoria e tomar decisões informadas para
garantir o sucesso do projeto.

#O QUE É PARA FAZER?

##Gerar um relatório de progresso diário para mostrar o quão produtivo está sendo o
trabalho dos funcionários e incluir no relatório outros itens como:
- Total de Horas Trabalhadas
- Média Diária de Horas Trabalhadas
- Total de Bugs Corrigidos
- Média Diária de Bugs Corrigidos
- Total de Tarefas Concluídas
- Média Diária de Tarefas Concluídas
- Produtividade Diária (Tarefas Concluídas por Hora)

# Requisitos
- Utilizar Jupyter Notebook ou Colab;
- Realizar análise exploratória;
- Responder cada uma das perguntas com a visualização mais adequada;
- O notebook utilizado na análise deve estar organizado, com descrições do
passo a passo da análise em markdown, apresentação dos resultados e
insights gerados.

