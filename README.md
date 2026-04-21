# ACC102 Mini Assignment - Track 2
# Analysis of U.S. Consumers' Preference Changes for Chinese E-commerce Products (Pre & Post COVID-19)

## 1. Problem & Target User
### Research Question
> Before and after the pandemic (2018-2019 is the pre-pandemic period, and 2021-2023 is the post-pandemic period), 

>1 what changes and differences did the sales proportion of the three major categories of **Chinese daily necessities, electronic products, and home goods** purchased by American consumers through online channels show?

>2 Which type of goods has seen **the most significant increase or decrease** in preference?

>3 How has the epidemic affected **American consumers' choices of Chinese e-commerce products**?
### Research Background
The COVID-19 pandemic accelerated the shift to online shopping globally, including in the U.S. At the same time, Chinese cross-border e-commerce products became more accessible. Understanding how U.S. consumers' preferences changed during this period can help sellers identify growth opportunities and optimize their product mix.

### Target User
Cross-border e-commerce operation teams (Chinese sellers targeting the U.S. market)
- International trade market analysts
- Small and medium-sized export enterprises

---

## 2. Data Source

The data used in this project is secondary data collected from public global e-commerce reports and market research statistics. 

### Main sources include:
1. Statista Global E-commerce Reports (2018–2023): Covers the share of Chinese consumer goods in U.S. online sales (daily necessities, electronics, home goods).
2. eMarketer U.S. Cross-border Shopping Surveys: Includes consumer purchase frequency of Chinese cross-border products.
3. Supplementary reference: U.S. Retail Federation data on domestic brand market share (used to verify preference shifts).

>The data covers the period from 2018 to 2023, which is divided into two groups: 
- Pre-COVID period: 2018–2019
- Post-COVID period: 2021–2023
 
### Relevance
This data is relevant to my research question because it provides year-by-year percentage shares of three product categories: daily necessities, electronic products, and home goods. These variables allow me to compare consumer preferences before and after the pandemic and identify clear trends in demand.Moreover, the supplementary domestic brand data helps further confirm that the growth of Chinese product share is not due to overall market expansion, but to real preference changes.


---


## 3. Python Implementation & Workflow
The analysis follows a clear, reproducible workflow using Python:
1.  **Data Organisation**: Input the collected data into a pandas DataFrame.
2.  **Preprocessing**: Categorise data into pre- and post-pandemic periods and calculate average shares.
3.  **Visualisation**:
    - A line chart showing trends in product share over time.
    - A bar chart comparing average share before and after the pandemic.
4.  **Interpretation**: Derive key insights from the visualisations.

---

## 4. Key Findings & Interpretation
From the analysis, three main conclusions are drawn:
1.  **Home goods saw the most significant growth**, with average share increasing from ~5% pre-pandemic to ~12% post-pandemic. This aligns with the "stay-at-home economy" during lockdowns.
2.  **Daily necessities remained stable**, with a slight increase from ~8% to ~10%. As essential goods, their demand was less volatile.
3.  **Electronics grew steadily but at a slower pace**, from ~12% to ~15%, possibly due to increased competition from local brands.

These findings suggest that home goods and daily necessities were more resilient and saw greater demand growth, while electronics faced stiffer competition.

---

## 5. How to Run the Project
1.  Ensure Python (3.8+) with `pandas` and `matplotlib` is installed.
2.  Download the `.ipynb` file and open it in Jupyter Notebook or VS Code.
3.  Run all cells sequentially. The code will output two charts and print key results.
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

## 7. Reflection & AI Disclosure
This project allowed me to apply Python for data analysis to a real-world business problem. I learned how to structure a complete data workflow, from defining the problem to interpreting the results. I also gained a better understanding of how external events like a pandemic can reshape consumer preferences.

**AI Disclosure**: I used AI tools to help with grammar and sentence structure in the README and video script. All research questions, analysis logic, and conclusions are my own.

---

## 8. Links
- Project Repository: `[Your GitHub Repo Link]`
- Demo Video: `[Your Video Link]`
