
# 🛒 Alura StoreBR - Análise de Dados das Lojas

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&style=flat-square)
![Pandas](https://img.shields.io/badge/Pandas-data%20analysis-green?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-visualization-orange?style=flat-square)

---

## 📋 Sobre o Projeto

O **Alura StoreBR** é um projeto de análise de dados que visa ajudar o Sr. João a escolher a melhor loja para focar suas vendas, a partir da análise das informações de quatro lojas diferentes. 

As análises realizadas contemplam:

- Faturamento total de cada loja;
- Categorias de produtos mais e menos vendidas;
- Média das avaliações dos clientes por loja;
- Produtos mais e menos vendidos;
- Custo médio do frete em cada loja.

Com base nesses indicadores, o projeto gera insights para apoiar a tomada de decisão.

---

## 📂 Estrutura do Repositório

```
.
├── dados/
│   ├── loja_1.csv
│   ├── loja_2.csv
│   ├── loja_3.csv
│   └── loja_4.csv
├── AluraStoreBR_analise.ipynb
├── README.md
└── requirements.txt
```

- **dados/**: Contém os arquivos CSV com as bases de dados das lojas (os arquivos também são carregados diretamente das URLs no notebook).
- **AluraStoreBR_analise.ipynb**: Notebook contendo todo o código para carregamento, análise e visualização dos dados.
- **requirements.txt**: Lista das bibliotecas Python necessárias para rodar o projeto.

---

## 🚀 Como Executar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/AluraStoreBR.git
   cd AluraStoreBR
   ```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):  
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows
   ```

3. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```

4. Abra o notebook Jupyter:  
   ```bash
   jupyter notebook
   ```  
   E execute as células na ordem para ver as análises e visualizações.

---

## 📊 Principais Resultados

- **Faturamento:** Identificamos qual loja apresenta maior receita total.
- **Categorias:** Analisamos quais categorias de produtos são mais e menos vendidas em cada loja.
- **Avaliações:** Calculamos a média das avaliações para entender a satisfação dos clientes.
- **Produtos:** Descobrimos os produtos mais e menos vendidos em cada loja.
- **Frete:** Avaliamos o custo médio do frete para cada loja.

Os gráficos gerados fornecem uma visão clara e visual dos dados para facilitar a interpretação.

---

## 📝 Relatório Final

Ao final das análises, foi possível recomendar a loja com melhor desempenho global para o Sr. João focar suas vendas, considerando faturamento, satisfação dos clientes, popularidade dos produtos e custos operacionais.

---

## 📦 Dependências

- pandas
- matplotlib
- jupyter (para rodar o notebook)

Você pode instalar todas executando:  
```bash
pip install -r requirements.txt
```

---

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

---

## 📄 Licença

Este projeto está licenciado sob a licença MIT.

---

## 👤 Autor

Denner — Engenheiro de Controle e Automação

---

Made with ❤️ for learning and data analysis.

