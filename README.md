# Análise de Crescimento Populacional de Municípios e Estados Brasileiros

Este projeto realiza uma análise da população de municípios e estados brasileiros de 1970 a 2021, abordando diversos aspectos como:
- Estatísticas descritivas básicas (média, mediana, moda, desvio padrão, variância, quartis, etc.);
- Análise de tendências temporais;
- Distribuição da população;
- Identificação de outliers;
- Crescimento populacional por décadas e regiões;
- Comparações entre estados e correlações entre ano e população.

## Requisitos

Para rodar este projeto localmente, é necessário ter instalado:

- Python 3.7 ou superior
- Bibliotecas Python:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`

Essas bibliotecas podem ser instaladas executando o seguinte comando:

```bash
pip install pandas numpy matplotlib seaborn
```
## Dados Utilizados

Os dados de população são fornecidos em um arquivo CSV, contendo as colunas:

- year: Ano do censo.
- abbrev_state: Sigla do estado.
- name_municipality: Nome do município.
- population: População registrada.

## Estrutura do Projeto

- main.py: Arquivo principal do projeto que contém todas as análises e gráficos.
- brasil_municipalities_population.csv: Arquivo com os dados de população de municípios e estados brasileiros.
- README.md: Este arquivo, com orientações de como rodar o projeto.

## Passos para Rodar o Projeto

``` bash
git clone <URL_DO_REPOSITORIO>
cd nome_do_projeto
```

## Instale dependências
Execute o seguinte comando para instalar as bibliotecas necessárias:

``` bash
pip install pandas numpy matplotlib seaborn
```

## Executando o Projeto
Você pode rodar o projeto de duas formas:
### a)Jupyter Notebook
Se estiver usando o Jupyter Notebook, siga os passos abaixo:

1. Inicie o Jupyter Notebook no terminal:
``` bash
jupyter notebook
```
2. Abra o arquivo populacao_municipios_brasil.ipynb e execute as células sequencialmente para gerar os gráficos e análises.

### b)Arquivo Python
Se estiver rodando através de um arquivo Python, siga os passos:
1. Certifique-se de que o arquivo main.py está no diretório do projeto.
2. Execute o script no terminal:
``` bash
python main.py
```

## Análises Disponíveis
As análises disponíveis no projeto são as seguintes:

1. Estatísticas Básicas:
Média, mediana, moda, desvio padrão, variância e quartis para a população dos municípios ao longo dos anos.

2. Tendências Temporais:
Gráficos de linhas que mostram a evolução da população por estado e a comparação do crescimento populacional entre diferentes décadas.

3. Distribuição da População:
Histogramas e boxplots que visualizam a dispersão da população dos municípios e estados em determinados anos.

4. Outliers:
Identificação de municípios com populações extremamente altas ou baixas, com base em z-scores e análise de IQR.

5. Comparações Regionais:
Comparação da média populacional entre as regiões do Brasil e análise da proporção populacional de cada estado.

6. Correlação entre Ano e População:
Gráfico que mostra a relação entre o ano e o crescimento populacional, verificando a correlação para diferentes estados.

7. Crescimento por Décadas:
Comparação do crescimento populacional ao longo das décadas, para identificar períodos de crescimento e declínio por estado.

## Exemplo de Resultados
- Gráfico de Linhas: Representa a evolução da população ao longo dos anos.
- Boxplot: Visualiza a dispersão da população e detecta outliers.
- Gráfico de Barras: Representa o crescimento populacional médio de cada estado.
- Gráfico de Pizza: Exibe a proporção populacional de cada estado em um determinado ano.
- Correlação: Avalia a relação entre o ano e a população em cada estado.

## Licença
Este projeto é de uso livre e pode ser modificado conforme necessário. Sinta-se à vontade para contribuir com melhorias e atualizações.

Com essas instruções, você será capaz de rodar o projeto localmente e visualizar as análises e gráficos gerados. Caso tenha dúvidas, consulte os arquivos de código e os comentários para entender melhor como cada parte do projeto funciona.
