#  Spotify Data Analysis — 7 Days of Code

Coleta e análise exploratória de dados (EDA) desenvolvida como parte do desafio **7 Days of Code — Machine Learning**, da Alura.

O projeto utiliza um dataset com informações de músicas do Spotify para explorar padrões relacionados à **popularidade das faixas**, características musicais e artistas, além de preparar os dados para futuras etapas de Machine Learning.

> 🚧 **Status:** Dia 1 — Análise Exploratória de Dados (EDA)

---

## 🎯 Objetivo

O objetivo desta etapa é compreender o conjunto de dados antes da construção de modelos preditivos.

Durante a análise, foram explorados:

- Estrutura e características do dataset;
- Valores ausentes e possíveis inconsistências;
- Registros duplicados;
- Distribuição das variáveis;
- Músicas e artistas mais populares;
- Relações entre características musicais e popularidade;
- Correlações entre as variáveis numéricas;
- Padrões que podem ser relevantes para modelos de Machine Learning.

---

## 🔎 Principais análises

Entre as características analisadas estão:

- **Danceability** — indica o quanto uma faixa é adequada para dançar;
- **Energy** — representa a intensidade e atividade da música;
- **Valence** — indica a positividade ou o caráter mais alegre da faixa;
- **Acousticness** — medida de confiança de que a faixa é acústica;
- **Instrumentalness** — indica a probabilidade de a faixa não possuir vocais;
- **Liveness** — indica a probabilidade de a gravação ter sido realizada ao vivo;
- **Tempo** — velocidade da música em batidas por minuto (BPM);
- **Popularity** — índice de popularidade da faixa.

A análise busca entender se determinadas características apresentam alguma relação com a popularidade das músicas.

---

## 🗂️ Sobre os dados

O dataset utilizado foi obtido através do **Kaggle** e contém milhares de faixas do Spotify.

Cada registro representa uma música e possui diversas características relacionadas ao áudio e à popularidade da faixa.

Exemplo de algumas das variáveis:

| Variável | Descrição |
|---|---|
| `popularity` | Índice de popularidade da música |
| `danceability` | Adequação da música para dança |
| `energy` | Intensidade e atividade da faixa |
| `valence` | Positividade transmitida pela música |
| `acousticness` | Probabilidade de a música ser acústica |
| `instrumentalness` | Probabilidade de ausência de vocais |
| `liveness` | Probabilidade de uma gravação ao vivo |
| `tempo` | Tempo da música em BPM |

---

## 🛠️ Tecnologias utilizadas

- **Python 3.11+**
- **Jupyter Notebook / JupyterLab**
- **Pandas** — manipulação e análise dos dados
- **Matplotlib** — visualização de dados
- **Seaborn** — criação de visualizações estatísticas

---

## 📁 Estrutura do projeto

```text
sevendaysofcode/
│
├── diaum.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
```

> O nome do arquivo do dataset pode variar dependendo da versão utilizada.

---

## 🚀 Como executar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/gu1fernandes/sevendaysofcode.git
cd sevendaysofcode
```

### 2. Crie um ambiente virtual

Recomendado para evitar conflitos entre dependências:

```bash
python -m venv venv
```

### 3. Ative o ambiente virtual

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 4. Instale as dependências

```bash
pip install -r requirements.txt
```

Caso o arquivo `requirements.txt` ainda não exista:

```bash
pip install pandas matplotlib seaborn jupyterlab
```

### 5. Adicione o dataset

Baixe o dataset utilizado no desafio através do Kaggle e coloque o arquivo `.csv` no diretório indicado pelo notebook.

### 6. Execute o Jupyter

```bash
jupyter lab
```

ou:

```bash
jupyter notebook
```

Depois, abra:

```text
diaum.ipynb
```

e execute as células do notebook.

---

## 📊 Resultados

A análise exploratória permitiu investigar:

- Quais artistas e músicas apresentam maior popularidade;
- Como as características de áudio estão distribuídas;
- Quais variáveis apresentam maior ou menor correlação com a popularidade;
- Possíveis padrões que podem ser utilizados posteriormente na construção de modelos preditivos.

Os resultados e visualizações estão disponíveis diretamente no notebook [`desafio.ipynb`](desafio.ipynb).

---

## 🧠 Aprendizados

Este projeto representa a primeira etapa do desafio **7 Days of Code — Machine Learning** e teve como principais aprendizados:

- Importação e exploração de datasets;
- Limpeza e preparação de dados;
- Identificação de valores ausentes e duplicados;
- Análise estatística exploratória;
- Criação de visualizações;
- Interpretação de correlações;
- Preparação dos dados para etapas posteriores de Machine Learning.

---

## 📌 Próximas etapas

Este projeto faz parte de uma sequência de estudos em **Machine Learning**. As próximas etapas podem incluir:

- Tratamento e transformação das variáveis;
- Engenharia de atributos;
- Seleção de features;
- Construção de modelos preditivos;
- Avaliação de desempenho;
- Comparação entre diferentes algoritmos.

---

## 👨‍💻 Autor

**Guilherme Fernandes**
Estudante de Engenharia de Computação.
