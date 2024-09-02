# Data Professional Survey Breakdown

Este repositório contém um projeto Power BI focado na análise de uma pesquisa com profissionais da área de dados. O objetivo é explorar dados sobre salários, satisfação no trabalho e linguagens de programação preferidas, fornecendo insights visuais para facilitar a interpretação dos resultados.

## Descrição do Projeto

### Data Cleaning e Transformação
O primeiro passo foi realizar o tratamento dos dados no Power Query, com as seguintes etapas:
- **Remoção de colunas desnecessárias**: Excluí colunas como `Browser` e outras não relevantes para a análise.
- **Filtragem de linhas**: Mantive apenas as opções mais importantes, removendo linhas específicas como "Other (software engineer, AI)", deixando apenas "Other".
- **Cálculo da média salarial**: A partir de uma coluna de salários no formato "60-120k", removi os caracteres 'k' e '-', criei duas colunas com esses valores, calculei a média salarial e criei uma nova coluna com esses resultados. As colunas intermediárias foram removidas.

### Visualizações Criadas
Após a preparação dos dados, criei as seguintes visualizações no Power BI:

- **Cartões:**
  - **Contagem de Participantes**: Um cartão mostrando o total de respondentes da pesquisa.
  - **Média de Idade**: Um cartão exibindo a média de idade dos participantes.

- **Gráficos:**
  - **Média Salarial por Profissão**: Um gráfico comparando a média salarial entre diferentes profissões (cientista de dados, analista, etc.).
  - **Linguagem de Programação Preferida**: Um gráfico que mostra a votação das linguagens de programação preferidas.
  - **Treemap de Respondentes**: Um treemap visualizando os respondentes.
  - **Happiness Gauges**: Dois medidores que avaliam a satisfação com o trabalho e com o salário.
  - **Gráfico Donut - Dificuldade para Ingressar em Data Science**: Um gráfico em formato donut mostrando o quão difícil foi para os participantes ingressarem na área de ciência de dados.

## Arquivo Disponível
O arquivo principal do projeto é o arquivo `.pbix`, que contém todas as transformações de dados e visualizações descritas acima.

## Como Usar
1. Clone este repositório para sua máquina local.
2. Abra o arquivo `.pbix` no Power BI Desktop.
3. Explore as visualizações e faça análises conforme necessário.

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork deste repositório e enviar um pull request com suas melhorias.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

