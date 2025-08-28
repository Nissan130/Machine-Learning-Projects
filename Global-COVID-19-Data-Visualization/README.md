# COVID-19 Interactive Dashboard

## **Project Overview**

This project is a **fully interactive COVID-19 dashboard** built using **Python, Plotly, Seaborn, and Dash**. It allows users to:

* Explore **daily new cases, deaths, and total cases** across multiple countries.
* Compare COVID-19 metrics dynamically using **dropdown filters**.
* Visualize **vaccination impact vs total cases**.
* Download filtered COVID-19 data as a CSV file.
* Gain insights from trends and correlations for a professional data analysis experience.

---

## **Features**

* **Dynamic Country Selection:** Users can select one or more countries to visualize.
* **Metric Comparison:** Compare `new_cases`, `new_deaths`, `total_cases`, or `total_deaths` dynamically.
* **Interactive Plots:** Line plots, bar charts, and scatter plots with hover information.
* **Download CSV:** Export filtered data directly from the dashboard.
* **Modern Dark Theme:** Professional, clean design suitable for portfolio showcase.

---

## **Technologies Used**

* **Python 3**
* **Pandas** – data manipulation
* **Seaborn & Matplotlib** – static plots
* **Plotly & Dash** – interactive visualizations and web dashboard

---

## **Installation**

1. Clone the repository:

```bash
git clone https://github.com/yourusername/covid-dashboard.git
cd covid-dashboard
```

2. Install required packages:

```bash
pip install pandas plotly dash matplotlib
```

3. Run the app:

```bash
python app.py
```

4. Open your browser at `http://127.0.0.1:8050` to view the dashboard.

---

## **Dataset**

The dashboard uses the **COVID-19 dataset by Our World in Data (OWID)**:
[Download Dataset](https://github.com/owid/covid-19-data/tree/master/public/data)

Columns used:

* `date`, `location`, `new_cases`, `new_deaths`, `total_cases`, `total_deaths`, `people_vaccinated`, `people_fully_vaccinated`, `population`, `gdp_per_capita`

---

## **Insights**

* The US and India have experienced the **highest peaks of daily cases**.
* **Correlation** exists between total cases and total deaths.
* Countries with **higher vaccination rates** show lower new cases in most instances.
* The dashboard allows **dynamic exploration** of trends for selected countries and metrics.


---

## **Future Enhancements**

* Add **more countries dynamically** from the dataset.
* Include **additional metrics** like hospitalizations and testing rates.
* Deploy the dashboard online using **Heroku or Streamlit Share** for public access.
* Add **trend prediction charts** using machine learning models.

