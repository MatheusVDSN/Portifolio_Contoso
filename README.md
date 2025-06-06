## Contoso Sales Dashboard
<img align="right" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_Contoso/blob/main/Imagens/contoso_print.JPG?raw=true">
Projeto de dashboard devolvido com Power BI para identificar os principais fatores que impactam as vendas da empresa Contoso, permitindo análises dinâmicas e de fácil compartilhamento com os responsáveis pela tomada de decisão.
Principais problemas relatados pelo requisitante: 
- Dificuldade de exportar os dados do sistema atual e manipular as informações em planilhas, macros e tabelas dinâmicas.
- Segmentar dados  por filiais, categorias, produtos e períodos de tempo de uma forma simples, dinâmica e fácil de compartilhar.
- Medir a performance comparando períodos de tempo (YoY, YTD, MoM, MTD).
<br>
<a href="" target="_blank">Clique aqui</a> e acesse o a solução desenvolvida para o cliente.
<br>
<a href="https://github.com/BruceFonseca/Contoso-Light/blob/main/README.md" target="_blank">Clique aqui</a> e acesse o repositório no Github.


<br><br>

## Modelo e fonte de dados 
<img align="left" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_Contoso/blob/main/Imagens/diagrama_dos_dados.JPG?raw=true">
Após conversa com a equipe glogal de tecnogia da informação do cliente, fomos informados de um existente data warehouse, contendo todas informações necessárias. Evitando assim a necessidade de importar dados de outras fontes como planilhas, arquivos de textos ou raspagem de dados em sistemas web.

<br><br><br><br>

<br><br>

## Criando tabela Calendário
<img align="right" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_Contoso/blob/main/Imagens/limpeza_criando_tabela_calendario.JPG?raw=true">
Após a importação dos dados foi necessário criar uma tabela dimensão referente as datas de análise, com o uso de power query foi possível criar uma tabela para o uso de parâmetros internos e um modelagem na demonstração dos dados.


<br><br><br><br>

<br><br>

## Medidas
<img align="left" width="500" height="320" src="https://github.com/MatheusVDSN/Portifolio_Contoso/blob/main/Imagens/tabela_medidas_ed.png?raw=true">
Identificado a necessidade do cliente, as regras de negócio e a aplicação das mesmas no modelo de dados, iniciamos o desenvolvimento.
Principais medidas desenvolvidas;
 - Custos, Receitas, Lucro, Entregas
 -  Medidas de inteligência temporal para comparação de performance e resultados entre períodos distintos ou cumulativos.
Para organizar as medidas, criamos uma tabela contendo todas as medidas, sempre seguindo a padronização dos nomes.


<br><br><br><br><br><br><br><br>

<br><br>

## Ferramentas e linguagens utilizadas
<div style="display: inline_block">
    <img align="center" alt="SQL" height="40" width="40" src="https://github.com/BruceFonseca/ferramentas/blob/main/logo.png?raw=true">
    <img align="center" alt="Power BI" height="40" width="40" src="https://github.com/BruceFonseca/ferramentas/blob/main/1200px-New_Power_BI_Logo.svg.png?raw=true">
</div>
