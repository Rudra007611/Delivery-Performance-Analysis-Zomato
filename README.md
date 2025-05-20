
# 📦 Zomato Delivery Performance Analysis using R

This project analyzes operational efficiency and delivery performance for Zomato, one of India's leading food delivery platforms. Using a dataset of **45,584 records and 20 features**, the goal was to identify key factors affecting delivery times, including **traffic conditions, weather, vehicle health, delivery personnel ratings, and festival periods**.

📌 Problem Statement

> What operational and external factors most significantly impact delivery time in Zomato's last-mile logistics?

We aimed to explore relationships between variables such as **road traffic density**, **weather conditions**, **vehicle condition**, and **delivery person ratings**, with delivery time as the primary outcome.

 🧰 Tools & Technologies

* **Language:** R
* **Libraries:** ggplot2, dplyr, tidyverse
* **Visualization:** Bar plots, Scatter plots, Box plots, Histograms, Line plots, Pie charts
* **Environment:** RStudio

📊 Key Visualizations & Findings

* **🚦 Traffic Density:** High traffic zones lead to a **\~25% increase** in delivery time.
* **⭐ Delivery Person Ratings:** Personnel rated 4.5+ deliver **\~12% faster** on average.
* **🛵 Vehicle Condition:** Minimal direct impact, though poor condition shows higher variance.
* **🎉 Festival Impact:** \~20% of deliveries occurred during festivals, with delivery times **spiking by 18%**.
* **⏱️ Time Trends:** Delivery time fluctuated up to 10 minutes depending on external factors like weather and day of the week.
* **📈 Histograms:** Majority of deliveries fall in the **30–40 min** range.

🧠 Conclusion

* **Optimizing delivery routes during peak traffic hours**, **incentivizing highly-rated personnel**, and **staffing for holidays** can significantly improve operational performance.
* The project delivers actionable insights for **logistics managers and operations teams** to enhance customer satisfaction.

📁 Dataset

The dataset was sourced from a Zomato delivery simulation and includes:

* `Time_taken (min)` – Target variable
* `Weather_conditions`, `Road_traffic_density`, `Festival` – External factors
* `Delivery_person_Ratings`, `Vehicle_condition`, `multiple_deliveries` – Operational metrics
* `Order_Date`, `City`, `Type_of_vehicle`, etc.

 📌 Project Structure

├── data/
│   └── delivery_data.csv
├── plots/
│   ├── traffic_vs_time.png
│   ├── rating_vs_time.png
│   └── ...
├── Zomato_Delivery_Analysis.R
└── README.md



