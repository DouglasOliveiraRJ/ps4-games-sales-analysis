<div align="center">
<h1>ps4-games-sales-analysis</h1>
<h3>Foi realizada uma Análise Exploratória de Dados (EDA) sobre o mercado de jogos de PlayStation 4, explorando tendências de vendas ao longo dos anos, diferenças regionais, gêneros mais populares e empresas com maior arrecadação global.</h3>  
</div>
<br><br>
<div align="center">

<p>Este README detalha o processo de análise exploratória de um dataset do Kaggle, desde a inspeção e preparação dos dados, análise estatística e exploratória em Python, insights e conclusão.</p>

</div>
<br><br>

<h2>📖 Visão Geral</h2>
<p>O objetivo deste projeto é compreender o comportamento do mercado de jogos de PS4 a partir de um dataset contendo informações de vendas por região, gênero e publisher, identificando padrões e tendências que influenciaram o desempenho global.</p>

## 💾 Fonte dos Dados

<p>O dataset utilizado foi o <strong>"Video Games Sales Dataset"</strong>, disponível na plataforma Kaggle.
  <ul>
  <li>Link para o Dataset: <a href="https://www.kaggle.com/datasets/sidtwr/videogames-sales-dataset?datasetId=189386&sortBy=voteCount" target="_blank">Video Games Sales Dataset on Kaggle</a</li>
  </ul>

   <h2>🔧 Processo do Projeto</h2>
  
  <h3>1. Preparação e Limpeza dos Dados</h3>
  
  <p>A primeira etapa consistiu em preparar o arquivo <code>.csv</code> original para análise, garantindo consistência e eliminando ruídos.</p>
  
  <h4>Etapas Executadas:</h4>
  
  <ul>
  <li>Carregamento do Dataset: O arquivo PS4_GamesSales.csv foi carregado em Python utilizando pandas.</li>
  <li>Limpeza de Dados: Verificação de valores nulos e duplicados, garantindo consistência nos dados.</li>
  <li>Conversão de Tipos: Coluna Year foi convertida para int, para melhor precisão.</li>
  <li>Análise inicial com <code>.info()</code>, <code>.describe()</code> e <code>.head()</code></li>  
  <li>Resultado: Base de dados limpa e pronta para análise estatística e visual.</li>
</ul>

<h3>2. Análise Exploratória com Python</h3>
<p>Com os dados tratados, foi feita uma análise exploratória (EDA) utilizando Seaborn e Matplotlib para identificar padrões nas vendas globais.</p>

<h4>Principais etapas e visualizações:</h4>

 <h5>📊 Vendas Globais por Ano</h5>
 <img src="tabela_amostra.png" alt="Tabela de Amostra" width="600"/>
 <ul>
  <li>Distribuição Geral das Médias: Estatísticas descritivas da coluna average score com describe().</li>
  <li>Comparação entre Grupos: Boxplots para as colunas "lunch" e "test preparation course" (mostrando dispersão, mediana e outliers) e Barplots para "parental level of education" e "race/ethnicity" (comparando médias por grupo).</li>
  <li>Estatísticas por Grupo: cálculo de médias com groupby().mean().</li>
  <li>Ranking dos 5 melhores e 5 piores alunos, a fim de comparação.</li>
</ul>














