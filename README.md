
# Desafio Dio - Criando um relatório de vendas elegante com Power BI
Neste projeto, criei um relatório de vendas com base em dados de amostra disponiveis pelo próprio Microsoft Power BI, e vou explicar o pouco do que eu fiz, nesta que foi minha primeira atividade com Power BI, na qual gostei muito. O processo de criação do arquivo foi feito no Power BI Desktop, e depois o arquivo foi publicado no Power BI Service Web.

# Criando o arquivo e importando dados
Para começar, ao abrir o programa Power BI Desktop pela primeira vez, foi criado um novo arquivo selecionando "Criar um novo relatório". Ao criar, selecionei a opção "Usar dados de amostra", e depois na janela que se abre selecionei "Carregar dados de exemplo", para ja carregar os dados do exemplo para meu painel, que no caso eu ja tinha disponivel que era os dados "Financials".

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/criar%20novo%20relatorio.png)

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/dados%20financials.png)

Após isso, foi só começar o processo de criação do relatório inserindo visualizações marcando os dados na aba **Dados** que seriam utilizados em cada recurso de visualização utilizado. O processo por muitas vezes lembra a criação de um arquivo Power Point.

# Pagina 1

## Cabeçalho e lateral
Para o cabeçalho e lateral esquerda, usei formas e caixa de texto, além de um botão de seta para a direita, que seria utilizado para mudar para a segunda pagina do relatório. Tambem utilizie formas no corpo da pagina, para dimensionar melhor as visualizações que seriam inseridas. Posteriormente, removi as formas do corpo após as visualizações estarem inseridas.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/formas%20e%20caixa%20de%20texto.png)

## Parte superior
Na parte superior do corpo da pagina, utilizei duas caixas de texto, um campo de filtro das informações por data, e um botão de "apagar" os filtros e ações feitas pelo usuario para visualizar, retornando a pagina para seu estado inicial.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/area%20superior%20pagina%201.png)

## Cartões
Ainda na parte superior da pagina, inseri visualização de cartões, para exibir os dados de **total de vendas**, **Unidades vendidas**, **Total de descontos**, **Soma de profit**, e **Soma de cogs**.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/cards.png)

## Grafico de Área
No centro da pagina, inseri uma visualização de **gráfico de área**, para demonstrar soma de vendas por mês.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/grafico%20de%20area%20pagina1.png)

## Gráficos de barra, mapa, Donut e Treemap
Na parte inferior da pagina, finalizei com dois **graficos de barra** utilizando dados de vendas por segmento e vendas por produto, respectivamente, e um **grafico de mapa** para vendas por país. Porem, adicionei um recurso de **indicadores**, no qual o botão Donut chart do grafico de vendas por segmento, alterava para uma visualizaçãode **grafico de "rosca"**, e o botão de Treemap do grafico de vendas por país, alterava para uma visualização de **grafico Treemap**.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/graficos%20barra%20e%20mapa.png)

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/grafico%20de%20rosca%20e%20treemap.png)

# Página 2
aqui houve um desafio proposto, no qual fariamos sem seguir um passo a passo e usando recursos de visualização importados, que não vinham ao instalar o Power BI Desktop. Para importar utilizei o menu "3 pontinhos" na área de visualizações e em seguida cliquei em **obter mais visuais**, no qual utilizei os recursos visuais **Radar Chart** e **ChicletSlicer**.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/pagina2.png)

## Cabeçalho e lateral
Na pagina 2 do relatório, não houve muita diferença da primeira, utilizei formas e caixas de textoe um botão de seta que volta para a pagina 1. A diferença ficou por conta do botão de **perguntas e respostas**, que mostram alguns tópicos ao clicar, semelhante a um chat, no qual clicando em um dos tópicos, ele lhe apresenta uma visualização correspondente.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/pagina2.png)

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/perguntas%20e%20respostas.png)

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/resposta.png)

## ChicletSlicer e gráfico de hierarquia
Na parte esquerda da pagina, utilizei um dos recursos obtidos, o ChicletSlicer, para fazer o filtro de data, e usei os dados de ano. Mais abaixo utilizei um **grafico de hierarquia**, que expandia os dados utilizados conforme se clicava (soma de profit, ano e vendas por país).

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/chiclet%20slicer%20e%20grafico%20de%20hierarquia.png)

## Grafico de radar, Treemap e Grafico cascata
Na parte a direita da pagina, utilizei o outro recurso obtido, o **grafico de radar** do recuros Radar Chart, no qual se ve claramente o que se deseja, que no caso foi a soma de profit por produto. Tambem foi utilizado um **grafico Treemap** para mostrar a soma de profit por segmento, e um **grafico cascata**, mostrando a soma de profit por trimestre.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/treemap%2C%20radar%20e%20grafico%20cascata.png)

# Publicando o relatório
Finalizado as paginas do desafio, realizei a publicação no serviço web do Power BI. Para tal tarefa, fui na aba pagina inicial, e depois na opção publicar, e selecionei meu workspace para a publicação.

![](https://github.com/henriquesoaresjr/Desafio_DIO-Criando-Relatorio-De-Vendas-Com-PowerBI/blob/main/prints%20auxiliares/publicar%20no%20workspace.png)

Com isso, estava disponivel no meu serviço web o relatório do desafio, onde pude testar de melhor maneira se todos os recursos inseridos no Power BI desktop estavam funcionando da maneira desejada.

# Conclusão
Essa foi uma atividade muito legal de se realizar. Foi meus primeiros contatos com o Power BI, e gostei demais! Foi uma atividade bem simples, mas importante para mim ja ter uma boa noção de como funcionam algumas coisas no Power BI.
