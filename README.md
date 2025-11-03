# ⚽ Análise Base de Dados das Ligas Europeias de Futebol – Temporada 2024/2025

Este projeto realiza uma **análise exploratória e estatística de jogadores das ligas europeias de futebol da temporada 2024/2025**, utilizando Python e bibliotecas de ciência de dados. O objetivo é identificar padrões de desempenho ofensivo e defensivo, avaliar ligas e construir o **"Dream Team"** com base em métricas de performance.

---

## 📁 Estrutura do Repositório

```
├── futebol data analysis.ipynb     # Notebook principal com análises e visualizações
├── players_data_light-2024_2025.csv # Base de dados dos jogadores da temporada
├── README.md                        # Descrição do projeto
```

---

## 🧩 Bibliotecas
* **Pandas** – tratamento e análise de dados
* **Matplotlib / Seaborn** – visualizações estatísticas

---

## 🚀 Execução do Projeto

1. Clone o repositório:

   ```bash
   git clone https://github.com/seuusuario/futebol-data-analysis.git
   cd futebol-data-analysis
   ```

2. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

3. Execute o notebook:

   ```bash
   jupyter notebook "futebol data analysis.ipynb"
   ```

---

## 📊 Principais Análises

| Análise                      | Descrição                                                           | Principais Métricas                                         |
| ---------------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------- |
| **Top Jogadores Ofensivos**  | Identificação dos atletas com melhor desempenho em ações ofensivas. | Gols + assistências ("G+A").     |
| **Top Jogadores Defensivos** | Avalia a performance defensiva individual.                          | Botes e interceptações ("Tkl+Int")  |
| **Ligas de Maior Qualidade** | Compara ligas por média ofensiva e defensiva.                          | Melhores defensores e atacantes.
| **Melhores Goleiros**        | Analisa goleiros com base em defesa ("Saves").                  | Defesas por jogo. |
| **Dream Team**               | Montagem do time ideal por concatenação dos melhores jogadores, sem restrição de liga.   | Ranking geral ponderado por desempenho e impacto.           |

---

![Top 10 Jogadores Ofensivos](/images/top10ofensivos.png)


---

## 💡 Futuras Extensões

* Integração com dados históricos (últimas 5 temporadas)
* Análise de evolução de performance dos jogadores
* Criação de dashboard interativo (Streamlit ou Power BI)

