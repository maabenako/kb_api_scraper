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

