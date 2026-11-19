# Global Course Sales and Advertising Analysis with Matplotlib

A Google Colab project exploring course enrollments, advertising activity, and estimated revenue across several international markets. It demonstrates a broad range of Matplotlib chart types and formatting options using one consistent dataset.

> **Data note:** This project uses simulated educational data for a fictional online learning company. It is not actual BYJU'S data or records from any real company. Revenue and advertising values are illustrative estimates. The country currency conversions are also simulated for practice.

## Project files

- `Global_Course_Sales_Ads_Matplotlib_UPDATED.ipynb` — expanded Colab notebook with charts and code.
- `GlobalLearn_Simulated_Course_Ads_Sales.csv` — 720-row dataset used by the notebook.
- `README_assets/` — chart images displayed below.

## Dataset overview

The sample covers 12 months in 2024 and includes five markets: India, the United States, the United Kingdom, Canada, and Australia. Each row represents a month, country, course category, and advertising channel combination.

Fields include:

- Month, country, and course category
- Advertising channel
- Impressions, clicks, and enrollments
- Advertising spend, course price, and revenue in local currency
- Illustrative advertising spend and revenue estimates in USD

The USD estimate fields are intended to make cross-country chart comparisons easier. Treat all figures as practice data, not business results.

## Charts in the project

### Monthly course enrollments by country

![Monthly course enrollments by country](README_assets/monthly-enrollments-by-country.png)

### Estimated course revenue by country

![Estimated course revenue by country](README_assets/estimated-revenue-by-country.png)

### Advertising spend by channel

![Advertising spend by channel](README_assets/advertising-spend-by-channel.png)

### Share of enrollments by course category

![Share of enrollments by course category](README_assets/enrollments-by-course-category.png)

### Estimated revenue versus advertising spend

![Estimated revenue versus advertising spend](README_assets/revenue-vs-advertising-spend.png)

## Matplotlib chart types demonstrated

The notebook demonstrates line, vertical bar, horizontal bar, stacked bar, area, pie, donut, scatter, histogram, box, violin, heatmap, step, error-bar, hexbin, and stem plots.

It also uses Matplotlib functions and options such as `figure`, `plot`, `step`, `bar`, `barh`, `stackplot`, `pie`, `scatter`, `hist`, `boxplot`, `violinplot`, `imshow`, `errorbar`, `hexbin`, `stem`, `colorbar`, `title`, `xlabel`, `ylabel`, `xticks`, `yticks`, `grid`, `legend`, `bar_label`, `tight_layout`, `savefig`, markers, colors, line styles, labels, and annotations/formatting settings.

## Run in Google Colab

1. Download the notebook and CSV from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Choose **File → Upload notebook** and select the `.ipynb` file.
4. Run the notebook cells from top to bottom. The notebook can generate and download the simulated dataset itself.
5. To use the CSV already in the repository, upload it with the Colab Files panel and load it with `pandas.read_csv()`.

## Run locally

Install the required packages:

```bash
pip install pandas matplotlib
```

Then open the notebook in Jupyter, or use Google Colab. The dataset is included as a CSV file; no external data API is required.

## Repository suggestion

- **Repository name:** `global-course-sales-matplotlib`
- **Short description:** `Matplotlib visualizations of simulated international online course enrollments, advertising, and estimated revenue.`

## License and attribution

The notebook, sample CSV, and included charts are educational project materials. The dataset is simulated and does not represent any real company's performance.
