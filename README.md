# ACC102 Mini Assignment - Track 2
# Analysis of U.S. Consumers' Preference Changes for Chinese  Products (Pre & Post COVID-19)

## 1. Problem & Target User
### Research Question
> Before and after the pandemic (2018-2019 is the pre-pandemic period, and 2021-2023 is the post-pandemic period), 

>1 what changes and differences did the sales proportion of the three major categories of **Chinese daily necessities, electronic products, and home goods** 加上品类编号 更加细化purchased by American consumers ?

>2 Which type of goods has seen **the most significant increase or decrease** in preference?

>3 How has the epidemic affected **American consumers' choices of Chinese  products**?
### Research Background
The COVID-19 pandemic accelerated the shift to online shopping globally, including in the U.S. At the same time, Chinese cross-border  products became more accessible. Understanding how U.S. consumers' preferences changed during this period can help sellers identify growth opportunities and optimize their product mix.

### Target User
Cross-border  operation teams (Chinese sellers targeting the U.S. market)
- International trade market analysts
- Small and medium-sized export enterprises

---

## 2. Data Source& Key Varibles

The data used in this project is secondary data collected from public global e-commerce reports and market research statistics. 

### Main sources include:
1 The official data platform of the USITC, providing public inquiry services for U.S. official import and export statistics.https://dataweb.usitc.gov/trade/search/Import/HTS
2. 客单价和购买频次 
>The data covers the period from 2018 to 2023, which is divided into two groups: 
- Pre-COVID period: 2018–2019
- Post-COVID period: 2021–2023
 
### Relevance
This data is relevant to my research question because it provides year-by-year percentage shares of three product categories: daily necessities, electronic products, and home goods. These variables allow me to compare consumer preferences before and after the pandemic and identify clear trends in demand.
### Key Variables
| Variable Name | Definition | Data Type |
|---------------|------------|-----------|
| Year | Time dimension of the dataset (2018, 2019, 2021, 2022, 2023) | Numerical |
| Time_Period | Categorical grouping for comparison: Pre-COVID (2018-2019) / Post-COVID (2021-2023) | Categorical |
| Category | Product category | Object |
| Category_Share| Market share of each category (%) | Numerical |
| Category_Sales| Annual sales of each category | Numerical |
| Year_Sales | Sales of each category by year | Numerical |
| Freq_Pre |	Purchase frequency before COVID |	Numerical |
| Freq_Post | Purchase frequency after COVID |	Numerical |
| AOV_Pre |	Average order value before COVID	| Numerical |
| AOV_Post |	Average order value after COVID	| Numerical |
---


## 3. Python Implementation & Workflow
This study adopts Python to establish a clear and reproducible analytical workflow, with the following steps:
1. **Data Organisation**:Input the collected annual sales data of three product categories  (daily necessities, electronics, and home goods) into a pandas DataFrame to build a structured analytical dataset.
2. **Data Preprocessing**:Categorise the data into pre-pandemic and post-pandemic periods, and calculate the average share of each category across the two phases. Additionally, compute the year-on-year growth rate and absolute sales increment to quantify the changes in consumer preferences.
3. **Data Visualisation**:Generate a series of visualisations to intuitively present the analytical results:
  - A line chart showing the annual trend of category market share
  - A bar chart comparing the average category share before and after the pandemic
  - A bar chart comparing the absolute sales increment of each category across the two periods
  - A bar chart comparing the changes in purchase frequency before and after the pandemic
  - A bar chart comparing the changes in average order value before and after the pandemic
4. **Interpretation**: Derive key insights from the visualisations.
---

## 4. Key Findings & Interpretation
From the analysis, three main conclusions are drawn:
1. **Sales structure shifted from high concentration to relative balance**：Electronics dominated the sales mix before the pandemic. Post-pandemic, its share dropped slightly, while the shares of home goods and daily necessities rose moderately, driving the overall sales structure toward relative balance.
2. **Category preference growth showed differentiated characteristics**：In terms of absolute growth scale, electronics registered the largest increase in consumer preference. In terms of growth trend reversal, home goods achieved the most remarkable turnaround, shifting from pre-pandemic decline to post-pandemic growth.
3. **The pandemic reshaped U.S. consumers’ purchasing behavior toward Chinese goods**：The pandemic boosted U.S. consumers’ demand intensity for Chinese-made home goods and daily necessities, with purchase frequency rising significantly. Price preferences showed differentiation: daily necessities trended toward high-frequency, low-price purchases, while consumers were more willing to pay a premium for Chinese-made electronics and home goods, and overall demand tilted toward home-oriented essential products.
   
This study analyzes the changes in U.S. consumers’ preferences for Chinese-made daily necessities, electronics, and home goods before and after the pandemic. The results show that the sales structure shifted from being highly concentrated on electronics to relatively balanced; category preference growth was differentiated, with electronics leading in absolute growth and home goods achieving a notable turnaround from decline to growth. Meanwhile, the pandemic increased U.S. consumers’ demand intensity for Chinese-made home-oriented essential products and gave rise to differentiated price preferences.


---

## 5. How to Run the Project
1.  Ensure Python (3.8+) with `pandas` and `matplotlib` is installed.
2.  Download the `.ipynb` file and open it in Jupyter Notebook or VS Code.
3.  Run all cells sequentially. The code will output five charts and print key results.
4.  View the generated visualisations and insights.

---

## 6. Limitations & Future Improvements
### Limitations
- The data is aggregated from public reports and lacks granularity by consumer demographics.
- The analysis does not account for external factors like tariffs or shipping costs.
- The year 2020 is excluded, which omits the initial impact of the pandemic.

### Improvements
- Add 2020 data to capture the immediate effects of the pandemic.
- Include price sensitivity analysis to understand the role of cost in consumer choices.
- Compare Chinese vs. non-Chinese product performance to isolate the "China factor".

---

## 7. Reflection & AI Disclosure 如果扩写要附件
This project allowed me to apply Python for data analysis to a real-world business problem. I learned how to structure a complete data workflow, from defining the problem to interpreting the results. I also gained a better understanding of how external events like a pandemic can reshape consumer preferences.

**AI Disclosure**: I used AI tools to help with grammar and sentence structure in the README and video script. All research questions, analysis logic, and conclusions are my own.

---

## 8. Links
- Project Repository: `[Your GitHub Repo Link]`
- Demo Video: `[Your Video Link]`
