# Enem  X Educação Básica
Projeto de Data Scientist focado em analises atráves dos microdados disponibilizados pelo INEP. O objetivo é mapear e entender como a infraestrutura da escola durante a educação básica interfere nos resultados colhidos no ENEM. O principal foco de estudo é compreender se escolas de educação primária que possuem agua filtrada, internet, etc. apresentam melhores resultados no enem, a correlação das bases será feita pelo código identificador de escola.

# Links de Acesso as Bases
Bases utilizadas para o estudo:<p>
[Microdados Enem por Escola](http://download.inep.gov.br/microdados/enem_por_escola/2005_a_2015/microdados_enem_por_escola.zip)<p>
[Microdados Enem](http://download.inep.gov.br/microdados/microdados_enem2018.zip)<p>
[Dados de Estados e Região](http://download.inep.gov.br/microdados/micro_censo_escolar_2014.zip)<p>
  
# Recomendações para o uso:
  1 - Instale as bibliotecas colocadas no arquivo requirements.txt (pip install -r requirements.txt)<p>
  2 - Baixe as bases de dados especificadas acima.<p>
  3 - Salve as bases recem baixadas num diretorio BASES/DADOS/ na mesma pasta que o arquivo .ipynb<p>
  4 - Execute jupyter notebook no seu CMD e navegue pela arvore até encontrar o Estudos.ipynb<p>
  5 - Use nosso notebook sem moderação! :)<p>

# Resultados Colhidos

## Frequência de Registros por Região

<div align="center">
    <img src="./IMAGENS/FREQUENCIAPORREGIAO.png" width="640" />
    <div height="2"></div>
</div>

## Comparativo de Média de Notas do Enem vs Existência da Biblioteca na Escola

<div align="center">
    <img src="./IMAGENS/graficoNotasEnemvsBiblioteca.png" width="640" />
    <div height="2"></div>
</div>

## Comparativo de Média de Notas do Enem vs Existência da Laboratóriode Informática na Escola

<div align="center">
    <img src="./IMAGENS/graficoNotasEnemvsLabInformatica.png" width="640" />
    <div height="2"></div>
</div>

