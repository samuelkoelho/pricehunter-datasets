# 📦 PriceHunter Datasets

**Repositório oficial do projeto PriceHunter**, responsável por coletar, organizar e disponibilizar bases de dados de produtos extraídos das principais plataformas de e-commerce do Brasil.

🔗 Shopee | Mercado Livre | Amazon Brasil

---

## 📊 Sobre o Projeto

Este projeto utiliza **web scraping com Python + Selenium** para coletar dados atualizados de produtos nas categorias:

- 📱 **Celulares e smartphones**
- 🚗 **Produtos automotivos** (óleos, acessórios, peças, etc)

As informações são salvas em **CSV** e **JSON**, prontos para análise ou uso em projetos de ciência de dados, BI e precificação.

---

## 📂 Estrutura do Repositório

```
📦 pricehunter-datasets
 ┣ 📁 dados
 ┃ ┣ 📄 celulares.csv
 ┃ ┣ 📄 celulares.json
 ┃ ┣ 📄 automotivos.csv
 ┃ ┗ 📄 automotivos.json
 ┣ 📁 src
 ┃ ┣ 📄 scraper_shopee.py
 ┃ ┣ 📄 scraper_ml.py
 ┃ ┗ 📄 scraper_amazon.py
 ┣ 📁 landing
 ┃ ┗ 📄 index.html
 ┣ 📄 requirements.txt
 ┗ 📄 README.md
```

## 📈 Visualizar amostras dos dados

- 📱 [Download exemplo de celulares (CSV)](dados/celulares.csv)
- 🚗 [Download exemplo de automotivos (CSV)](dados/automotivos.csv)

Você pode visualizar diretamente os arquivos ou importar em ferramentas como Excel, Power BI, Tableau ou pandas.

---

## 🛒 Comprar a base completa

- 💰 [Gumroad](https://gumroad.com/.)
- 🛍️ [Payhip](https://payhip.com/.)

Inclui versão completa + atualizações automáticas por 30 dias.

---

## 📡 Rodar no Google Colab

Você pode testar o scraping no Colab:

[🔗 Abrir no Google Colab](https://colab.research.google.com/drive/seu-link)

---

## 📬 Contato

Dúvidas, sugestões ou parcerias:

📧 samuel.coelho@live.com
---

## 🛠️ Feito com:
- Python 3.12+
- Selenium + webdriver-manager
- pandas

---

## 📄 Licença
Este projeto está licenciado sob a licença MIT.
