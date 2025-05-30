# 🎬 Movie Dataset Analysis App (Shiny + R)

An interactive, modular Shiny application built in R for uploading, exploring, editing, and visualizing structured movie datasets. This dashboard-based tool enables users to perform data preprocessing and gain valuable insights from genre, year, and revenue trends—without writing code.

---

## 📌 Features

- ✅ Upload CSV or Excel files
- 🧮 View summary statistics and descriptive analysis
- ✍️ Edit records interactively using a data table
- 📊 Visualize data with bar charts, line graphs, pie charts, and heatmaps
- 🎯 Genre-based filtering
- 📤 Export cleaned data as a downloadable CSV

---

## 🧱 Modules

1. **Data Upload & Preprocessing** – Accepts and validates CSV/Excel datasets  
2. **Data Editing** – Inline editing with `DT` table  
3. **Summary & EDA** – Displays mean, median, and quantiles for numeric columns  
4. **Visualization** – Generates dynamic charts with filtering support  
5. **Report & Export** – Download transformed data  
6. **UI & Dashboard** – Responsive layout using `shinydashboard` and `bslib`

---

## 📦 Packages Used

- `shiny`  
- `shinydashboard`  
- `DT`  
- `dplyr`  
- `ggplot2`  
- `shinyWidgets`  
- `bslib`  
- `readxl`  
- `shinyjs`

---

## 🚀 Getting Started

### Prerequisites
Install R and RStudio. Then install the required packages:

```r
install.packages(c("shiny", "shinydashboard", "DT", "dplyr", 
                   "ggplot2", "bslib", "shinyWidgets", "shinyjs", "readxl"))
Running the App
Clone the repository

Open app.R or paste the code into RStudio

Click Run App

📁 Input Requirements
File format: .csv or .xlsx

Required columns: Title, Genre, Year, Revenue

📈 Screenshots
![Uploading image.png…]()


🛠 Future Enhancements
Real-time machine learning for revenue prediction

Recommendation system based on genre/year

Cloud-based storage and multi-user support

Sentiment analysis from movie reviews

📄 License
MIT License © 2024

🙌 Acknowledgements
RStudio Shiny Team

tidyverse contributors

R for Data Science by Wickham & Grolemund
