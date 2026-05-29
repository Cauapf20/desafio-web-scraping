# Desafio Web Scraping - Versão Python

Este projeto é um robô de raspagem de dados desenvolvido em Python para extrair informações estruturadas de uma página de produto.
D

# Dados Extraídos

O script foi mapeado utilizando seletores CSS específicos da página para garantir a coleta completa de:
- Título e Marca do produto
- Categorias (Breadcrumbs)
- Descrição completa do produto (Aba correspondente)
- Variações de Modelos (SKUs), incluindo preços atuais, preços antigos e disponibilidade de estoque
- Lista completa de especificações técnicas
- Lista de avaliações dos usuários com nome, data, comentário e nota (calculando também a média geral das notas automaticamente)

# Tecnologias Utilizadas
* Python 3**
*Requests: Para fazer as requisições HTTP e acessar a página.
*BeautifulSoup4: Para fazer o parse do HTML e navegar pelos seletores CSS.
*JSON: Para estruturar e exportar os dados limpos.

## 🚀 Como Executar o Projeto

1. Instale as bibliotecas necessárias:
   
   pip install requests beautifulsoup4

2 ..python scraper.py