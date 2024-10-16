# Workshop - Utilizando Pandas na Prática - Painéis de Dados

![logo](/static/idp_logo.png)

**Professor:** Lucas dos Santos Althoff
**Data:** 20/04/2024

---

Repositório para Workshop de Data Science para Negócios II. Este repositório contém dados e exemplos de códigos utilizados no workshop.


## Dados

Os dados a serem utilizados no workshop são: 

- `dados/estoque.csv` (Dados falsos de estoque)
- `dados/dados_tic.csv` (Dados reais da Região do Entorno do DF - RIDE)

## Dependências

Para criar um ambiente com todas as dependências usando o Conda:

`conda env create -f environment.yml`

Caso você não utilize Conda utilize execute o seguinte código no terminal para configurar seu ambiente: 

`pip install -r requirements.txt`

## Executando

Para executar os painéis do Workshop basta executar o seguinte comando em seu terminal:

`streamlit run painel_estoque.py`

ou

`python -m streamlit run painel_texto.py`


# Passo a passo

1) Instalar VS Code
2) Instalar Python
3) Baixar arquivo `workshop_paineis_streamlit-1.zip` no ambiente virtual 
   1) https://ambientevirtual.idp.edu.br/courses/3815/assignments/15021
4) Descomprimir o arquivo `workshop_paineis_streamlit-1.zip`
5) Abrir VS Code
6) Abrir a pasta File>Open Folder>workshop_paineis_streamlit-1
7) Instalar bibliotecas
   1) Abrir terminal em: Terminal>New Terminal
   2) Executar no terminal esse código: `pip install -r requirements.txt`
8) Executar um exemplo 
   `python -m streamlit run painel_texto.py`