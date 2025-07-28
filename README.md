# Smart Pricing & Retention: My Airbnb and Telecom Solutions

## What This Project Is About

In this project, I tackled two real-world business problems using data and machine learning:

1.  **Airbnb Smart Pricing:** I built a model to predict how much Airbnb listings should cost.
2.  **Telecom Customer Retention (Churn Prediction):** I developed a model to figure out which telecom customers were likely to leave, so companies can try to keep them.

## Why I Built This (Problem Solved)

* **For Airbnb:** Property owners often struggle with setting the right price. My goal was to give them a data-driven tool to estimate optimal listing prices, helping them earn more and attract more renters.
* **For Telecom:** Losing customers (churn) is a big issue for telecom companies. I aimed to create a system that predicts which customers are at risk, allowing the company to proactively offer incentives or support to retain them.

## What I Did (Key Features)

* **Data Prep:** For both datasets, I handled cleaning, transforming, and preparing the data so it was ready for my models.
* **Feature Engineering:** I created new features from the raw data to give my models more insights (e.g., how long an Airbnb listing has been active, customer call history for telecom).
* **Airbnb Pricing Model:** I used regression techniques to build a model that predicts listing prices based on various factors like location, amenities, and number of bedrooms.
* **Telecom Churn Model:** I applied classification algorithms to identify patterns in customer behavior that lead to churn, allowing me to predict who might leave.
* **Model Evaluation:** For both models, I rigorously tested their performance. For pricing, I looked at how close my predictions were to actual prices. For churn, I evaluated how well I could identify at-risk customers using metrics like accuracy, precision, and recall.

## Tools I Used

* **Python** (My main programming language)
* **Core Libraries:** `pandas`, `numpy`, `scikit-learn` (for machine learning models like Logistic Regression, Decision Trees, etc.), `matplotlib`, `seaborn` (for visualizations)
* **Jupyter Notebooks** (Where I did all my analysis and model building)

## How You Can Run This

If you want to check out my work on your own machine, here's how:

1.  **Get the code:**
    ```bash
    git clone [https://github.com/nayan9572/data-driven-pricing-churn.git](https://github.com/nayan9572/data-driven-pricing-churn.git)
    cd data-driven-pricing-churn
    ```

2.  **Install the necessary stuff:**
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn jupyter
    ```

3.  **Open the notebooks:**
    * You'll likely find two separate Jupyter Notebook files for each problem (e.g., `Airbnb_Pricing_Analysis.ipynb`, `Telecom_Churn_Prediction.ipynb`). Open them with:
        ```bash
        jupyter notebook "Your_Airbnb_Notebook_Name.ipynb"
        jupyter notebook "Your_Telecom_Notebook_Name.ipynb"
        ```
    * Then, just run through the cells to see the process!

## My Results and What I Learned

* **For Airbnb Pricing:** My model provided strong estimates for pricing, which could directly help property owners maximize their income.
* **For Telecom Churn:** I successfully built a churn prediction model that could identify at-risk customers with good accuracy, giving companies a chance to intervene.
* Overall, this project taught me a lot about applying different machine learning techniques (regression vs. classification) to diverse business problems and how to get actionable insights from complex data.

## Get in Touch

Feel free to connect or ask questions!
Nayan Kumar - nayanchaudhary979@gmail.com
