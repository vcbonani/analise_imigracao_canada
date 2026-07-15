# 📊 Análise de Dados de Imigração para o Canadá (1980–2013)

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-3F4F75?logo=plotly&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)

Este projeto apresenta uma **Análise Exploratória de Dados (EDA)** sobre a imigração para o Canadá entre **1980 e 2013**, utilizando Python e diferentes bibliotecas de visualização de dados.

Ao longo da análise são exploradas séries temporais, comparações entre países e visualizações interativas para compreender o comportamento da imigração ao longo de mais de três décadas. O projeto demonstra como diferentes técnicas de visualização podem transformar dados em informações claras e relevantes para apoiar a tomada de decisões.

> **Projeto desenvolvido durante o curso _Data Visualization: Criando gráficos com bibliotecas Python_, da Alura.**

---

## 🎯 Objetivos

- Explorar dados históricos de imigração para o Canadá entre 1980 e 2013.
- Analisar a evolução da imigração ao longo do tempo.
- Comparar o comportamento da imigração entre diferentes países.
- Aplicar técnicas de visualização de dados utilizando Matplotlib, Seaborn e Plotly.
- Desenvolver visualizações claras, personalizadas e interativas.

---

## 📌 Destaques do projeto

- ✔️ Análise da imigração para o Canadá entre **1980 e 2013**
- ✔️ Evolução da imigração do **Brasil**
- ✔️ Comparação entre **Brasil** e **Argentina**
- ✔️ Visualização dos países da **América do Sul**
- ✔️ Construção de gráficos com **Matplotlib**
- ✔️ Customização de visualizações
- ✔️ Gráficos estatísticos com **Seaborn**
- ✔️ Visualizações interativas com **Plotly**

---

## 📂 Base de dados

O projeto utiliza uma base de dados contendo o histórico de imigração para o Canadá entre **1980 e 2013**, permitindo analisar tendências temporais e comparar o fluxo migratório entre diversos países.

---

## 🔍 Fluxo da análise

O notebook foi desenvolvido seguindo uma sequência lógica de exploração dos dados:

1. Importação e preparação da base de dados.
2. Criação das primeiras visualizações com Matplotlib.
3. Análise da evolução da imigração do Brasil para o Canadá.
4. Comparação do fluxo migratório entre Brasil e Argentina.
5. Construção de subplots para facilitar comparações.
6. Exploração da imigração dos países da América do Sul.
7. Personalização das visualizações com estilos, cores e anotações.
8. Desenvolvimento de gráficos com Seaborn.
9. Construção de gráficos interativos utilizando Plotly.

---

## 📈 Visualizações desenvolvidas

Durante o projeto foram produzidas diferentes tipos de gráficos para comunicar informações de maneira clara e objetiva, incluindo:

- gráficos de linhas;
- gráficos comparativos;
- subplots;
- gráficos personalizados com estilos e paletas de cores;
- gráficos com anotações;
- visualizações estatísticas;
- gráficos interativos;
- exportação de visualizações em HTML.

---

## 📊 Resultados

Ao longo da análise foi possível:

- Identificar a evolução do fluxo de imigração para o Canadá entre **1980 e 2013**.
- Visualizar o comportamento da imigração brasileira ao longo de mais de três décadas.
- Comparar as tendências de imigração entre **Brasil** e **Argentina**, evidenciando diferenças no comportamento das séries temporais.
- Analisar o fluxo migratório dos países da **América do Sul** por meio de visualizações comparativas.
- Explorar diferentes formas de representar os mesmos dados utilizando **Matplotlib**, **Seaborn** e **Plotly**, avaliando as vantagens de cada biblioteca.
- Desenvolver visualizações estáticas e interativas capazes de facilitar a interpretação dos dados e apoiar a comunicação dos resultados.

Os resultados demonstram como a visualização de dados pode revelar padrões, tendências e comparações que seriam mais difíceis de identificar apenas por meio de tabelas.

---

## 🛠️ Tecnologias e bibliotecas utilizadas

| Tecnologia | Aplicação no projeto |
|------------|----------------------|
| **Python** | Desenvolvimento da análise exploratória de dados. |
| **Jupyter Notebook** | Ambiente de desenvolvimento e documentação da análise. |
| **Pandas** | Importação, tratamento, manipulação e preparação dos dados. |
| **Matplotlib** | Construção de gráficos de linhas, figuras, subplots e personalização das visualizações. |
| **Seaborn** | Criação de gráficos estatísticos utilizando temas e paletas de cores. |
| **Plotly Express** | Desenvolvimento de gráficos interativos. |
| **Plotly Graph Objects** | Customização avançada das visualizações interativas. |

---

## 📚 Bibliotecas exploradas

### 📌 Pandas

- Importação da base de dados.
- Limpeza e preparação dos dados.
- Seleção e filtragem de países.
- Manipulação das séries temporais.

### 📌 Matplotlib

Durante o projeto foram explorados diversos recursos da biblioteca, incluindo:

- gráficos de linhas;
- criação de figuras (`figure()`);
- construção de subplots (`subplots()`);
- interface orientada a objetos (`fig` e `ax`);
- personalização de títulos, eixos e legendas;
- estilos (`plt.style.use()`);
- customização de cores e espessura das linhas;
- anotações (`annotate()`);
- exportação de gráficos (`savefig()`).

### 📌 Seaborn

- Aplicação de temas (`set_theme()`);
- Utilização de paletas de cores;
- Criação de visualizações estatísticas;
- Customização da aparência dos gráficos.

### 📌 Plotly

- Desenvolvimento de gráficos interativos;
- Personalização de layouts;
- Utilização do Plotly Express;
- Customizações com Graph Objects;
- Exportação das visualizações em HTML.

---

## 📁 Estrutura do repositório

```text
.
├── dados/
|   └── imigrantes_canada.csv
├── desafios - aula/
|   └── desafio_aula.ipynb
├── imagens/
|   ├── imigracao_america_sul.png
|   ├── imigracao_argentina_brasil.png
|   ├── imigracao_brasil.png
|   ├── imigracao_brasil_colombia_argentina_peru.png
|   └── imigracao_top_10_global.png
├── Analisando_dados_de_imigração_no_Canadá.ipynb
├── IDEIAS_GERADAS.md
└── README.md
```

---

## 🚀 Como executar o projeto

Clone este repositório:

```bash
git clone https://github.com/vcbonani/analise-imigracao-canada.git
```

Acesse a pasta do projeto:

```bash
cd analise-imigracao-canada
```

Instale as dependências:

```bash
pip install pandas matplotlib seaborn plotly notebook
```

Execute o Jupyter Notebook:

```bash
jupyter notebook
```

Abra o arquivo:

```text
Analisando_dados_de_imigração_no_Canadá.ipynb
```

---

## 🎓 Créditos

Este projeto foi desenvolvido durante o curso **Data Visualization: Criando gráficos com bibliotecas Python**, da **Alura**, aplicando na prática técnicas de visualização de dados para análise exploratória utilizando Python.

---

## 👨‍💻 Autor

**vcbonani**

GitHub: https://github.com/vcbonani

---

⭐ Se este projeto foi útil ou interessante para você, considere deixar uma estrela no repositório.
