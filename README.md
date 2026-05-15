

 **Project Overview**

The goal of this analysis is to identify the key drivers of customer satisfaction for an airline. By understanding these patterns, the airline can prioritize service improvements to convert "neutral or dissatisfied" passengers into "satisfied" ones.

**Dataset Features**

The dataset includes several categorical and numerical variables:

* **Demographics:** Gender, Age, Customer Type (Loyal/Disloyal).
* **Travel Details:** Type of Travel (Business/Personal), Class (Eco/Business), Flight Distance.
* **Service Ratings (Scale 1-5):** In-flight WiFi, Online Boarding, Seat Comfort, In-flight Entertainment, On-board Service, Cleanliness, etc.
* **Logistics:** Departure and Arrival Delay in minutes.
* **Target Variable:** `satisfaction` (Satisfied vs. Neutral or Dissatisfied).

 **Key Libraries Used**

* **Pandas & NumPy:** For data manipulation and numerical analysis.
* **Matplotlib & Seaborn:** For data visualization and identifying trends.
* **Missingno:** Used for visualizing missing data patterns (as seen in the notebook setup).
* **Scikit-Learn:** (Anticipated) For preprocessing and building predictive models.

 **Exploratory Data Analysis (EDA) Highlights**

* **Data Integrity:** Initial checks show missing values in `Arrival Delay in Minutes` (approx. 310 missing rows in the training set).
* **Demographics:** The average passenger age is approximately **39 years**.
* **Flight Distance:** Flights range from short hops of 31 miles to long-haul journeys of nearly 5,000 miles.
* **Satisfaction Drivers:** Preliminary looks suggest service areas like `Inflight wifi service` and `Online boarding` show significant variance in scores.

** How to Use**

1. **Clone the Repository:**
```bash
git clone https://github.com/your-username/Airline-Passenger-Satisfaction.git

```


2. **Install Dependencies:**
```bash
pip install pandas numpy matplotlib seaborn missingno scikit-learn

```


3. **Run the Notebook:**
Open `Airline Passenger Satisfaction.ipynb` in Jupyter Lab or Notebook to view the analysis steps.



Since you just finished the data inspection phase, would you like help writing the code to handle those missing values in the `Arrival Delay` column?
