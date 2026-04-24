# ACC102 Mini Assignment - Track 2
## US Imports from China – 20-Year Trend Analysis (2004–2024)
## 1. Problem & Target User
### Research Question
How have the value and structure of U.S. imports from China changed across three product categories (Necessities, Home Goods, Electronics) over the 20-year period 2004–2024?
>1 What is the overall trend of total US imports from China over the 20‑year period?

>2 How do annual import values compare across the three product categories?

>3 How has the share structure of the three categories changed (which categories have become more/less important)?

>4 How do growth rates and fluctuations compare across the three categories?

>5 How do the 20‑year cumulative import totals compare across the three categories?
### Target Users: 
Trade analysts and policy researchers

Market researchers analyzing U.S. consumer demand for Chinese goods

Importers and retail businesses interested in category trends

---
## 2. Data Source& Key Varibles
### Dataset information:
- Source: US Customs DataWeb (Import Statistics)
- Time range: 2004 – 2024 (20 years)
 ### Relevance
This data is relevant to my research question because it provides year-by-year import value  of three product categories: daily necessities, electronic products, and home goods. These variables allow me to compare consumer preferences .
### Key Variables
 Years,Category,Import Value,Growth Rate,Cumulative Value

---
## 3. Python Methods
- **Data Loading**: Read and merge multi-source datasets with pandas
- **Data Cleaning**: Handle missing values, remove duplicates, filter by year and category, standardize formats
- **Analysis**: Descriptive statistics, group calculation by year / category, long-term trend comparison, structural share analysis
- **Visualization**: Plot trend charts, proportion charts, and category comparison charts with matplotlib / seaborn
### Key Visualizations
1. Total import trend (line chart)
2. Three-category annual trend comparison (line chart)
3. Category share: 2004 vs 2024 (pie charts)
4. Annual growth rate comparison (line chart)
5. 20-year cumulative import value (horizontal bar chart)
6. CAGR (2004–2024) by Category(horizontal bar chart)

---
## 4. Key Findings 
From the analysis, three main conclusions are drawn:
1.The total value of U.S. imports from China presents a steady long-term upward trend.

2.Electronics is the dominant category with the most rapid growth.

3.The import structure has gradually shifted to electronics-oriented consumption.

4.All product categories show similar growth fluctuations, and home goods are more volatile.

5.Electronics contributes the largest cumulative import value over two decades.

6.Electronics records the highest CAGR, reflecting strong long-term growth potential.







用英文总结一下美国从中国进口的商品结构
把美国从中国进口商品的总价值趋势用图表展示出来
美国从中国进口商品的增长趋势对中国经济有什么影响？


   

---
## 5. How to Run the Project
1.  Ensure Python (3.8+) with `pandas` and `matplotlib` is installed.
2.  Download the `.ipynb` file and open it in Jupyter Notebook or VS Code.
3.  Run all cells sequentially. The code will output five charts and print key results.
4.  View the generated visualisations and insights.

---
## 6. Links
- Project Repository: `[Your GitHub Repo Link]`
- Demo Video: `[Your Video Link]`

---
## 7. Limitations & Future Improvements
### Limitations
- The data is aggregated from public reports and lacks granularity by consumer demographics.
- The analysis does not account for external factors like tariffs or shipping costs.
- The year 2020 is excluded, which omits the initial impact of the pandemic.
### Improvements
- Add 2020 data to capture the immediate effects of the pandemic.
- Include price sensitivity analysis to understand the role of cost in consumer choices.
- Compare Chinese vs. non-Chinese product performance to isolate the "China factor".

---
## 8. Reflection & AI Disclosure 如果扩写要附件
This project allowed me to apply Python for data analysis to a real-world business problem. I learned how to structure a complete data workflow, from defining the problem to interpreting the results. I also gained a better understanding of how external events like a pandemic can reshape consumer preferences.

**AI Disclosure**: I used AI tools to help with grammar and sentence structure in the README and video script. All research questions, analysis logic, and conclusions are my own.

---
