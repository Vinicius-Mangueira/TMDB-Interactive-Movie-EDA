# TMDB Interactive Movie EDA 🎬📊

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)  
[![TMDB API](https://img.shields.io/badge/TMDB-API-yellow.svg)](https://www.themoviedb.org/documentation/api)

---

## 📖 Descrição
Análise Exploratória de Dados (EDA) interativa de filmes utilizando a API do The Movie Database (TMDB). Explore dados reais de bilheteria, avaliações e mais, com gráficos dinâmicos e filtros interativos diretamente em um Jupyter Notebook!

---

## 📋 Sumário
- [Funcionalidades](#-funcionalidades)
- [Tecnologias](#-tecnologias)
- [Pré-requisitos](#-pré-requisitos)
- [Instalação](#-instalação)
- [Configuração da API TMDB](#-configuração-da-api-tmdb)
- [Como Usar](#-como-usar)
- [Exemplo de Uso](#-exemplo-de-uso)
- [Contribuição](#-contribuição)
- [Licença](#-licença)
- [Contato](#-contato)

---

## ✨ Funcionalidades
- 📈 **Visualizações Interativas:** Gráficos de dispersão, barras e linhas com *hover* informativo.
- 🔄 **Filtros Dinâmicos:** Selecione ano, gênero, popularidade e mais usando `ipywidgets`.
- 🕵️‍♂️ **Insights de Dados:** Análise de tendências de receita, avaliações e popularidade.
- ⚙️ **Automação de Dados:** Consulta automática à API do TMDB e pré-processamento com `pandas`.

---

## 🛠 Tecnologias
- **Linguagem:** Python 3.8+
- **Notebook:** Jupyter Notebook
- **Pacotes:**
  - `pandas` para manipulação de dados
  - `requests` para chamadas HTTP
  - `Plotly Express` para visualizações interativas
  - `ipywidgets` para controles dinâmicos

---

## 📦 Pré-requisitos
- Conta gratuita no TMDB e chave de API
- Python 3.8 ou superior
- `pip` para instalar dependências

---

## 🚀 Instalação
```bash
# Clone o repositório
git clone https://github.com/Vinicius-Mangueira/TMDB-Interactive-Movie-EDA.git
cd TMDB-Interactive-Movie-EDA

# (Opcional) Crie e ative um ambiente virtual
python -m venv venv
# Linux/macOS
source venv/bin/activate
# Windows
venv\\Scripts\\activate

# Instale as dependências
pip install -r requirements.txt
````

---

## 🔑 Configuração da API TMDB

Adicione sua chave API em uma célula do notebook ou em um arquivo `.env`:

```python
import os
os.environ['TMDB_API_KEY'] = 'SUA_CHAVE_AQUI'
```

---

## 🎓 Como Usar

1. Abra o Jupyter Notebook:

   ```bash
   jupyter notebook Notebooks/TMDB_EDA.ipynb
   ```
2. Execute as células na ordem para baixar dados, limpar, explorar e visualizar.
3. Utilize os widgets na parte superior para filtrar por ano, gênero ou popularidade.

---

## 📸 Exemplo de Uso

> **Filtrando Filmes de Ação (2020)**

![Exemplo de Gráfico](assets/screenshots/acao_2020.png)

---

## 🤝 Contribuição

Contribuições são muito bem-vindas!

1. Faça um *fork* deste repositório
2. Crie sua *branch*: `git checkout -b minha-feature`
3. Faça *commit* das suas alterações: `git commit -m 'Minha feature'`
4. *Push* para a branch: `git push origin minha-feature`
5. Abra um *Pull Request* 🎉

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📬 Contato

Vinícius Mangueira – [GitHub](https://github.com/Vinicius-Mangueira) – [LinkedIn](https://www.linkedin.com/in/vinicius-mangueira-0b8285224/) – [viniciusmangueira04@gmail.com](mailto:viniciusmangueira04@gmail.com)

```
```
