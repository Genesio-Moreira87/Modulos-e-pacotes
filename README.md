# Modulos e Pacotes
Antes de começar

Faça login na sua conta da Google. Acesse o **Google Colab** e faça o download do arquivo notebook “Profissão Analista de dados M8 Material de apoio”. 

# Nesta tarefa, iremos praticar 2 exercícios. 

Prepare o ambiente

Nesta atividade você vai utilizar a base de dados de ações da bolsa de valores dos EUA, a Dow Jones. Os dados estão disponíveis para download no link:

https://archive.ics.uci.edu/ml/datasets/Dow+Jones+Index

Vamos utilizar o pacote wget para fazer o download dos dados.

**1ª Parte**:

Instale o pacote wget na versão 3.2.

**2ª Parte**:

Faça o download dos dados no arquivo compactado dados.zip.

**3ª Parte**:

Descompacte os dados na pasta dados com o pacote nativo zipfile.

**4ª Parte**:

Verifique a pasta dados criada, ela deve conter dois arquivos:

dow_jones_index.data: um arquivo com os dados;

dow_jones_index.names: um arquivo com a descrição completa dos dados.

É possível observar que o arquivo de dados é um arquivo separado por vírgulas, o famoso csv. Vamos renomear o arquivo de dados para que ele tenha a extensão csv com o pacote nativo os.

﻿**5ª Parte**:

Renomeie o arquivo com o pacote nativo os.

Abra o arquivo e o Google Colab irá apresentar uma visualização bem legal dos dados.

# 1º Exercício: Pandas

Para processar os dados, vamos utilizar o pacote pandas na versão 1.1.5. A documentação completa por ser encontrada no link:

https://pandas.pydata.org/docs/

- Importe o pacote com o apelido (alias) pd.

- Leia o arquivo.

O pandas trabalha com o conceito de dataframe, uma estrutura de dados com muitos métodos e atributos que aceleram o processamento de dados. Alguns exemplos:

- Visualize as n primeiras linhas:

- Visualize o nome das colunas:

- Verifique o número de linhas e colunas:

- Selecione os valores de abertura, fechamento, máximo e mínimo das ações do McDonalds, listado na Dow Jones como MCD:

- a. Selecione as linhas do dataframe original df em que a coluna stock é igual a MCD

- b. Selecione apenas as colunas de data e valores de ações.

O problema é que as colunas com os valores possuem o carater $ e são do tipo texto ( object no pandas).

-c. Limpe as colunas com o método apply, que permite a aplicação de uma função anônima (lambda) qualquer. A função lambda remove o 
 caracter $ e faz a conversão do tipo de str para float.

Agora é a sua vez!

Conduza o mesmo processo para extrair e tratar os dados da empresa Coca-Cola (stock column igual a KO).

- a. Selecione as linhas do dataframe original df em que a coluna stock é igual a KO.

# extração e tratamento dos dados da empresa Coca-Cola.

Vamos selecionar os valores de abertura, fechamento, máximo e mínimo das ações da empresa Coca-Cola, listado na Dow Jones como KO:

- b. Selecione apenas as colunas de data e valores de ações.

O problema é que as colunas com os valores possuem o carater $ e são do tipo texto (object no pandas).

# Visualize os dados do dataframe

# Verifique o tipo dos dados

- c. Limpe as colunas com o método apply, que permite a aplicação de uma função anônima ( lambda) qualquer. A função lambda remove o caracter $ e faz a conversão do tipo de str para float.

- d. Verifique novamente os dados e seus tipos.

# Visualize novamente os dados do dataframe

# Verifique novamente o tipo dos dados

- e. Explore os dados visualmente.

# 2º Exercício: Seaborn

Para visualizar os dados, utilize o pacote seaborn na versão 0.11.1. A documentação completa por ser encontrada no link:

https://seaborn.pydata.org/

- Importe o pacote com o apelido (alias) sns.

- Visualize os valores de abertura das ações ao longo do tempo.

- Visualize os valores de fechamento das ações ao longo do tempo.

- Para facilitar a comparação, visualize os quatro valores no mesmo gráfico.

- Para finalizar, salve o gráfico numa figura.

Agora é a sua vez!

- a. Faça o gráfico acima para a empresa Coca-Cola e salve a imagem com o nome ko.png.

# visualização dos dados da Coca-Cola.

- b. Visualize os valores de abertura das ações ao longo do tempo.

- c. Visualize os valores de fechamento das ações ao longo do tempo.

- d. Para facilitar a comparação, visualize os quatro valores no mesmo gráfico.

- e. Para finalizar, salve o gráfico numa figura.

- f. Analise as duas imagens e escreva pelo menos um insight que você consegue extrair dos dados. Fique a vontade para escrever quantos 
  insights você quiser.

Saiba mais: 

Insights são observações sobre o que você percebe/entende/interpreta em suas análises. No caso deste exercício, você vai analisar os dados dos gráficos da empresa McDonalds e da empresa Cola-Cola e notar o que os dados gerados podem ser interessante, que tipo de interpretação o comportamento dos dados estão te trazendo.

## Autor: Genésio Moreira Coutinho 
- Graduado: Bacharelado em Sistemas de Informação | Pós Graduando:  MBA em Gestão da Qualidade em Tecnologia da Informação |Analista de Dados| 1x Azure - AZ900
- Date Analyst | Cloud Infrastructure | Azure | Analista Cloud | Analista Dados | Infraestrutura Cloud | Python
- Linkedin: https://www.linkedin.com/in/genesio-coutinho-554733124/
- Kaggle:https://www.kaggle.com/genesiomoreira

- Notebook para execução dos códigos Google Collab: https://colab.research.google.com/drive/11lbDDT42_EVQAnf64AFWodgGgLGWRFTK?usp=sharing
