# U.S. Crude Oil Trade Analysis

## Project Overview
This project performs an exploratory data analysis (EDA) of historical U.S. crude oil import and export data. The analysis aims to uncover key trends, identify major trading partners, assess the impact of significant events (like policy changes), and reveal any seasonal patterns in crude oil trade volumes.

## Data Sources
The analysis utilizes two primary datasets:
1.  **Weekly U.S. Crude Oil Imports by Country:** Data sourced from [mention source, e.g., EIA - U.S. Energy Information Administration]. This dataset provides weekly import volumes from various countries.
2.  **Monthly U.S. Crude Oil Exports by Country:** Data also sourced from [mention source]. This dataset provides monthly export volumes to various countries.

*(If you used specific filenames, you can mention them, e.g., "The raw data files (`crude_oil_imports.xls`, `crude_oil_exports.xls`) are located in the `data/` directory.")*

## Key Analyses Performed

* **Data Cleaning and Preparation:** Handled inconsistent column names, data types, and missing values across both datasets.
* **Time Series Analysis:** Visualized overall trends in total U.S. crude oil imports and exports over time, highlighting significant shifts.
* **Top Trading Partners:** Identified and visualized the top 10 countries for both crude oil imports to and exports from the U.S. based on total trade volumes.
* **Individual Country Trends:** Explored the time-series evolution of crude oil trade with key partners.
* **Impact of Major Events:** Analyzed the visual correlation between trade volumes and significant events, particularly the lifting of the U.S. crude oil export ban in December 2015 and the impact of the U.S. Shale Revolution.
* **Seasonal Patterns:** Investigated and visualized average monthly import and export volumes to identify recurring seasonal trends.
* **Interactive Dashboard:** Developed a simple interactive dashboard using Plotly and Dash to allow dynamic exploration of trade trends and top partners.

## Technologies Used

* Python 3
* Pandas (for data manipulation and analysis)
* Matplotlib & Seaborn (for static visualizations)
* Plotly Express & Dash (for interactive visualizations and dashboarding)

## How to Run the Project (for others)

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/US-Crude-Oil-Trade-Analysis.git](https://github.com/YourGitHubUsername/US-Crude-Oil-Trade-Analysis.git)
    cd US-Crude-Oil-Trade-Analysis
    ```
2.  **Download Data:** Ensure you have the raw data files (`crude_oil_imports.xls` and `crude_oil_exports.xls`) in a `data/` subdirectory. *(If you download the files from a specific URL, provide those links here for convenience)*.
3.  **Open in Google Colab:** The core analysis is performed in a Google Colab notebook. You can open `US_Crude_Oil_Trade_EDA.ipynb` (or whatever you named your notebook) directly in Colab: `File > Open notebook > GitHub` and paste the repository URL.
4.  **Install Dependencies:** Run the `!pip install ...` commands in the Colab notebook to set up the environment.
5.  **Run the Notebook:** Execute all cells in the Colab notebook sequentially. The interactive Dash app will launch in your Colab output.

## Author
[Your Name/GitHub Username]
[Link to your LinkedIn profile (Optional)]
[Link to your personal website/portfolio (Optional)]

## License
This project is open-source and available under the [Choose a license, e.g., MIT License].
