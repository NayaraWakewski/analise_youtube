
![youtube-small-icon-8 (1)](https://github.com/NayaraWakewski/analise_youtube/assets/79403619/86711b0a-a80a-4f72-9f9f-c6b11ab88a7e)


# Desafio DataGlowUp - Analise dos Dados do YOUTUBE.

Foi proposto um desafio para fazer uma análise com os dados do Youtube, de alguns países, do período de 2006 a 2018.

---
# 🚀 Análise Exploratória e Tratamento (PYTHON).

Foi utilizado o Python e o Notebook Jupyter para fazer as primeiras análises da base de dados.
A base de dados, continha vários arquivos csv e json, separada por países.
Decidi converter as bases para dataframe, para proceder com a unificação dos dados, criando 2 datframes: 

-**df_youtube** - contendo a base geral dos dados.
-**df_catgorias** - contendo o id e nome das categorias dos vídeos.

No notebook contém todo o passo a passo dessas análises, tratamentos e merge das bases.

---

## 🚀 Análises Estatísticas (PYTHON).

Como a base de dados, continha muitas informações numéricas, decidi fazer algumas análises estatíticas, antes de proceder com a visualização no PowerBi.

### Resumo da Análise Estatística das Métricas de Vídeos - 
Foi utilizado Mapa de Calor, que representa visualmente a matriz de correlação entre as métricas selecionadas.

### Análise de Regressão das Métricas de Engajamento no YouTube - 
Neste segmento da análise, dediquei-me a explorar a relação entre várias métricas de engajamento de vídeos no YouTube, como `likes` (curtidas), `dislikes` (descurtidas), e `comment_count` (contagem de comentários), e como elas influenciam a métrica de `views` (visualizações). O foco foi estabelecer um modelo de regressão linear múltipla para quantificar essas relações e oferecer insights sobre a dinâmica do engajamento dos espectadores.

### Análise de Cluster dos Vídeos do YouTube - 
Focando nas métricas de engajamento — likes, dislikes e comment_count e apresentado gráficos de distribuição de clusters e do método cotovelo.

---

## 🚀 Funcionalidades do Dashboard

### Seleção de Filtros
O dashboard permite a seleção de filtros para personalizar a análise dos dados, incluindo:

- **Ano:** Selecione o ano desejado para análise.
- **País:** Escolha um país específico.
- **Categoria:** Selecione uma categoria específica.
- **Canal:** Escolha um canal especifíco.

### Análise de Engajamento

- **Cartões com Quantitativo:** Gráfico de cartão com quantitativo de likes, comentários, categorias e visualizações.
- **Gráfico de Linha:** Gráfico de Linha demostrando a evolução de visualizações por ano.
- **Taxa de Engajamento** Gráfico de barras horizontais, demostrando a taxa % de engajamento por categoria de vídeos.
- **Top5 Países com % de engajamento e canal** Gráfico de barras verticais, demostrando o top5 países com maior taxa de engajamento/canal.


### Mapa de Engajamento

- **Mapa Interativo dos Países:** Mapa interativo que exibe a localização dos países e com as bolhas por engajamento.


### Análise de Correlação

- **Mapa de Calor:** Esse visual foi feito no Python e importado a imagem para o Powerbi, demostra a correlação das variáveis.


### Análise de Dispersão

- **Gráfico de Dispersão com Linha de Tendência** Demostra a relação entre o engajamento total e as visualizações.


### Análise de Satisfação

- **Gráfico de Barras Horizontais:** Gráfico de barras que mostra o % de satisfação por categoria, onde verde tem o maior percentual positivo de satisfação e vermelhor tem o menor percentual positivo (negativo) de satisfação.

---
## 🛠️ Link do visual do PowerBi.


  
---
## 🎁 Expressões de gratidão

* Compartilhe com outras pessoas esse projeto 📢;
* Quer saber mais sobre o projeto? Entre em contato para tomarmos um :coffee:;
---
⌨️ com ❤️ por [Nayara Vakevskii](https://github.com/NayaraWakewski) (https://www.linkedin.com/in/nayaraba/) 😊




