# Projeto de Análise de Dados Imobiliários no Rio de Janeiro

****

## 🔍 Sobre o projeto
Este é um projeto de análise de dados imobiliários na cidade do Rio de Janeiro, utilizando a biblioteca Pandas em Python. O objetivo é explorar e extrair insights valiosos a partir de um conjunto de dados sobre aluguéis de imóveis. Os dados foram obtidos do seguinte <a href="https://raw.githubusercontent.com/alura-cursos/pandas-conhecendo-a-biblioteca/main/base-de-dados/aluguel.csv" target="_blank">Link</a>. e contêm informações sobre diversos imóveis, incluindo tipo, localização, número de quartos, vagas de estacionamento, área, valor do aluguel, condomínio e IPTU.

## Características Gerais da Base de Dados

### Dimensões
A base de dados possui 32.960 linhas e 9 colunas.

![Screenshot_1](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/e3d4c0af-5e91-4689-9fda-15853795e6c9)

### Nomes das Colunas
As colunas presentes no conjunto de dados são: Tipo, Bairro, Quartos, Vagas, Suítes, Área, Valor, Condomínio e IPTU.

![Screenshot_2](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/f584425a-81a1-4c03-a9f7-3cf29185feec)

### Resumo das Informações
O conjunto de dados contém informações sobre tipos de dados, valores não nulos e uso de memória.

![Screenshot_3](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/2ceecf6d-13f0-4821-a909-e48774403235)

## Análise Exploratória de Dados

### Média de Aluguel por Tipo de Imóvel

![Screenshot_4](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/e2fa6dee-d848-47d3-8233-ba4a65775a5b)

![download](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/5dd90a8f-6839-41d0-918d-206bf86cd77c)

O gráfico resultante mostra visualmente a média de aluguel para cada tipo de imóvel. Isso permite comparar as médias de aluguel entre os diferentes tipos, oferecendo insights sobre quais tipos de imóveis tendem a ter aluguéis mais altos ou mais baixos. Essa análise é útil para compreender as variações nos preços de aluguel em relação aos tipos de propriedade.

### Percentual de Cada Tipo de Imóvel

![download (2)](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/062e0ac1-d1e1-4f4b-be64-36116bebceab)

O gráfico de barras resultante mostra visualmente a distribuição percentual de diferentes tipos de imóveis presentes no conjunto de dados. Cada barra representa a proporção de um tipo específico em relação ao total de imóveis, proporcionando insights sobre a diversidade dos tipos de imóveis na base de dados.

## Tratamento e Filtragem de Dados

### Removendo Imóveis Comerciais

![Screenshot_5](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/e37f10dd-ab59-4929-8649-a3ff4ae0d7a6)

![Screenshot_6](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/f5c6a99d-136c-49b6-980d-7e13bfb78747)

## Filtros
### 1. Apartamentos com 1 Quarto e Aluguel Menor que 1200

![Screenshot_7](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/3e2c80c9-1ba6-4d17-949a-0bfcb223dc4b)

### 2. Apartamentos com pelo menos 2 Quartos, Aluguel Menor que 3000 e Área Maior que 70

![Screenshot_8](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/9f7b0a83-58c1-4aab-b8f2-03943a7aeb90)

## Salvando os Dados

![Screenshot_9](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/92b307c7-bd0e-4983-aec1-cf1c17ac925a)

### Para visualizar o conjunto de dados salvo:

![Screenshot_10](https://github.com/diegolimagomes/Analise_de_Dados_Imobiliarios_Residenciais/assets/131981987/14c88219-9b22-41d2-966e-75d0d4313dfb)
