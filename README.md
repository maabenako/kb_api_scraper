# 💻 Kabum Product Scraper

Este projeto é um **scraper de produtos da Kabum** desenvolvido em **Node.js**, projetado para coletar dados de múltiplas categorias do e-commerce brasileiro **Kabum** por meio da sua API pública.

---

## 🚀 Funcionalidades

- Consulta produtos diretamente da API: `/catalog/v2/products-by-category`
- Paginação automática com limite de até 100 páginas por categoria
- Coleta de produtos em mais de **25 categorias diferentes**
- Delay aleatório entre requisições para simular navegação humana
- Pausas entre categorias (10 a 15 minutos) para evitar bloqueios
- Exportação dos dados em formato **CSV** pronto para análise

---

## 📦 Dados Coletados

Cada produto extraído inclui:

- `id`: ID do produto
- `attributes`: JSON de atributos técnicos
- `category`: nome da categoria
- `url`: link direto para o produto na Kabum

---

## 🛠️ Tecnologias Utilizadas

- `Node.js`
- `axios`
- `json2csv`
- `fs`

---

## 🧪 Como Usar

### 1. Clonar o repositório
```bash
git clone https://github.com/maabenako/kabum-scraper.git
cd kabum-scraper
```

### 2. Instalar dependências
```bash
npm install axios json2csv
```

### 3. Executar o script
```bash
node kabum_scraper.js
```
---

### 📁 Saída
O resultado será salvo em um arquivo chamado:
kabum_products.csv

---

### 👩‍💻 Autora
Desenvolvido com 💙 por Marcela Nako
🔗 [in/marcelaabe-alvim/] | 💼 [https://github.com/maabenako?tab=repositories]

---

# English:

# 💻 Kabum Product Scraper

This project is a **product scraper for Kabum**, developed in **Node.js**, designed to collect data from multiple categories of the Brazilian e-commerce **Kabum** using their **public API**.

---

## 🚀 Features

- Fetches product data directly from the API: `/catalog/v2/products-by-category`  
- Automatic pagination with a limit of up to 100 pages per category  
- Covers over **25 different categories**  
- Random delay between requests to simulate human-like browsing  
- Pauses between categories (10 to 15 minutes) to avoid blocking  
- Exports data in a **CSV** file ready for analysis

---

## 📦 Extracted Data

Each product record includes:

- `id`: product ID  
- `attributes`: JSON of technical attributes  
- `category`: name of the product category  
- `url`: direct product link on Kabum  

---

## 🛠️ Technologies Used

- Node.js  
- axios  
- json2csv  
- fs

---

## 🧪 How to Use

### 1. Clone the repository  
```bash
git clone https://github.com/maabenako/kabum-scraper.git  
cd kabum-scraper  
```
### 2. Install dependencies  
```bash
npm install axios json2csv  
```
### 3. Run the script  
```bash
node kabum_scraper.js
```

---

## 📁 Output

The result will be saved to a file named:  
```bash 
kabum_products.csv  
```
---

## 👩‍💻 Author

Developed with 💙 by **Marcela Nako**  
🔗 [LinkedIn](https://www.linkedin.com/in/marcelaabe-alvim/)  
💼 [GitHub](https://github.com/maabenako?tab=repositories)

---

