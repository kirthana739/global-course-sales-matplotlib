# Global Course Sales and Advertising Analysis

A Matplotlib project that explores course enrollments, estimated revenue, and advertising activity across international markets. The notebook uses a simulated dataset for a fictional online learning company and demonstrates how to create and format a wide range of charts in Python.

> **Dataset note:** All business records in this project are simulated for educational use. They are not actual BYJU'S data or records from another real company. Revenue and advertising figures are illustrative estimates.

## Project overview

This project analyzes course activity across India, the United States, the United Kingdom, Canada, and Australia. It considers four course categories—Coding, English, Mathematics, and Science—and three advertising channels: Search Ads, Social Media, and Video Ads.

The notebook explores questions such as:

- How do enrollments change over the year in each country?
- How do estimated course revenues compare across markets?
- Which advertising channels receive the most estimated spend?
- How are enrollments distributed across course categories?
- How do estimated advertising spend and revenue relate in the sample data?

## Visualizations

### Monthly course enrollments by country

![Monthly course enrollments by country](Monthly%20course%20enrollments%20by%20country.png)

### Estimated course revenue by country

![Estimated course revenue by country](Estimate%20course%20revenue%20by%20country.png)

### Advertising spend by channel

![Advertising spend by channel](Advertising%20spend%20by%20channel.png)

### Share of enrollments by course category

![Share of enrollments by course category](Share%20of%20enrollments%20by%20course%20category.png)

### Estimated revenue versus advertising spend

![Estimated revenue versus advertising spend](Estimate%20revenue%20versus%20advertising%20spend.png)

## Dataset

The sample contains 720 records covering 12 months in 2024. Each row represents a month, country, course category, and advertising channel combination.

Fields include:

- Month, country, course category, and advertising channel
- Currency and local advertising spend
- Impressions, clicks, and course enrollments
- Local course price and estimated local revenue
- Illustrative USD estimates for advertising spend and revenue

USD estimates are included to make sample comparisons across markets easier. They are not audited financial figures, and the currency conversions are illustrative.

The notebook generates the sample dataset when its data-generation cell runs. If you keep a separate CSV in this repository, add it at the root and update the notebook to load it with `pandas.read_csv()` if desired.

## Matplotlib topics

The notebook demonstrates line, vertical bar, horizontal bar, stacked bar, area, pie, donut, scatter, histogram, box, violin, heatmap, step, error-bar, hexbin, and stem charts.

It also practices Matplotlib functions and formatting options including `figure`, `plot`, `bar`, `barh`, `stackplot`, `pie`, `scatter`, `hist`, `boxplot`, `violinplot`, `imshow`, `errorbar`, `hexbin`, `stem`, `colorbar`, `title`, `xlabel`, `ylabel`, `xticks`, `yticks`, `grid`, `legend`, `bar_label`, `tight_layout`, `savefig`, colors, markers, line styles, labels, and figure sizing.

## Run the notebook in Google Colab

1. Open the notebook file `Global_Course_Sales_Ads_Matplotlib.ipynb` in this repository.
2. In Colab, choose **File → Save a copy in Drive** if you want your own editable copy.
3. Run the notebook cells from top to bottom.
4. The data-generation cell creates the simulated dataset and displays a preview.
5. Run the plotting cells to generate the visualizations.

## Run locally

Install Python packages used by the notebook:

```bash
pip install pandas matplotlib
```

Then open the `.ipynb` file using Jupyter Notebook or JupyterLab and run the cells in order. The dataset is generated in the notebook, so an external API or real company data is not required.

## Repository structure

```text
.
├── Global_Course_Sales_Ads_Matplotlib.ipynb
├── README.md
├── Advertising spend by channel.png
├── Estimate course revenue by country.png
├── Estimate revenue versus advertising spend.png
├── Monthly course enrollments by country.png
└── Share of enrollments by course category.png
```

## Tools used

- Python
- pandas
- Matplotlib
- Google Colab / Jupyter Notebook

## License and use

This repository is an educational demonstration. The included simulated dataset is not representative of the performance of any real company. Add a license file if you want to specify how others may reuse the notebook and project materials.
