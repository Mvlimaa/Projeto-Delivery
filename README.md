# Projeto ML - Análise de Entregas

Este repositório contém a estrutura padrão para o desenvolvimento de um projeto de Machine Learning.

## 🚀 Sobre o Projeto

Este projeto foca na análise e modelagem de dados de entrega (provavelmente do arquivo `delivery_time.csv`). O objetivo inicial é conduzir uma Análise Exploratória de Dados (EDA) para entender os fatores que influenciam o tempo de entrega e identificar possíveis problemas de qualidade nos dados.## 🔧 

Instalação e Configuração

Para configurar o ambiente e executar o projeto, siga as etapas abaixo.

**Pré-requisitos:**

  * Python (Versão recomendada: 3.11.6)

**Passos:**

1.  **Clone o repositório:**

    ```bash
    git clone (URL-DO-SEU-REPOSITORIO)
    cd (NOME-DO-PROJETO)
    ```

2.  **Crie um ambiente virtual:**

    ```bash
    python -m venv venv
    ```

3.  **Ative o ambiente virtual:**

      * No macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
      * No Windows:
        ```bash
        .\\venv\\Scripts\\activate
        ```

4.  **Instale as dependências:**
    O projeto utiliza as bibliotecas listadas no arquivo `requirements.txt`.

    ```bash
    pip install -r requirements.txt
    ```

5.  **Inicie o Jupyter (se necessário):**
    Para trabalhar nos notebooks, inicie o Jupyter:

    ```bash
    jupyter notebook
    ```

## 🛠️ Dependências

As principais bibliotecas usadas neste projeto são:

  * `pandas==2.2.3`
  * `numpy==1.26.4`
  * `matplotlib==3.9.2`
  * `seaborn==0.13.2`
  * `scipy==1.13.1`
  * `jupyter==1.0.0`

## 📂 Estrutura de Pastas

A organização do projeto segue a seguinte estrutura:

  * `data/raw`: Armazena os dados brutos e imutáveis (ex: `delivery_time.csv`).
  * `data/interim`: Dados temporários, em processamento.
  * `data/processed`: Dados finais, limpos e processados, prontos para a modelagem.
  * `notebooks`: Notebooks Jupyter usados para análise (ex: `01_EDA.ipynb`), experimentação e prototipagem.
  * `src`: Código-fonte principal do projeto (scripts Python, módulos de data prep, modelagem, etc.).
  * `reports/figures`: Figuras, gráficos, relatórios e dashboards gerados.
  * `requirements.txt`: Lista de dependências do Python.