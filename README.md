📊 **Real-Time Student Feedback Sentiment Analysis**

A Machine Learning & NLP-powered system that analyzes student feedback in real-time to classify sentiments, uncover rating trends, and help educators make data-driven decisions.
________________________________________
**📌 Project Overview**

This project performs real-time sentiment analysis on student feedback data using Machine Learning (ML) and Natural Language Processing (NLP) techniques. The system processes feedback collected across multiple subjects, sessions, and faculties — classifying sentiments and revealing hidden patterns through powerful visualizations and clustering.

The goal is to help educational institutions understand how students feel about their learning experience and take actionable steps to improve teaching quality, technology usage, and overall satisfaction.
________________________________________
**🎯 Objectives**

•	Analyze student feedback to identify positive, neutral, and negative sentiments.

•	Discover subject-wise and faculty-wise performance trends.

•	Apply KMeans Clustering to group technology & subject feedback.

•	Perform time-based analysis — daily, weekly, and monthly trends.

•	Visualize insights through interactive charts and heatmaps.
________________________________________
**🛠 Tools & Technologies**

• **Python**	              **:**  Core programming language

• **Pandas & NumPy**	      **:**  Data manipulation and numerical analysis

• **Matplotlib & Seaborn**	**:**  Data visualization

• **Scikit-learn**	        **:**  Machine Learning (KMeans, StandardScaler)

• **Jupyter Notebook**	    **:**  Interactive development environment
________________________________________
**📂 Dataset**

•	**File:** Student_Feedback_Dataset.csv

•	**Total Records:** 600 student feedback entries

________________________________________
**🔍 Analysis Performed**

**1️⃣   Exploratory Data Analysis (EDA)**

•	Shape, data types, statistical summary.

•	Missing values detection.

•	Unique value counts per column.

**2️⃣   Visual Analysis**

•	**Gender Distribution** — Countplot showing male vs. female student breakdown.

•	**Overall Rating Distribution** — Histogram of rating frequencies.

•	**Technology Feedback** — Countplot of technology usage feedback categories.

•	**Session Code vs Overall Rating** — Regression plot showing correlation trend.

•	**Correlation Heatmap** — Numeric feature correlation matrix.

**3️⃣   Faculty & Subject Analysis**

•	**Faculty-wise Count** — Bar chart with direct labels.

•	**Subject-wise Rating** — Histogram with hue for each subject (IOT, FDS, DW, Power BI).

•	**Technology vs Rating** — Mean overall rating grouped by technology feedback.

**4️⃣   Machine Learning — KMeans Clustering**

•	**Technology Clustering** — Grouped technology feedback by mean rating → scaled → 3-cluster KMeans.

•	**Subject Clustering** — Grouped subjects by mean rating → KMeans classification into performance tiers.

**5️⃣   Time-Series Analysis**

•	Date parsing with dayfirst=True format handling.

•	Extracted Day, Week, and Month features from date column.

•	**Daily Analysis** — Min, Max, Mean rating per faculty per day.

•	**Weekly Analysis** — Weekly performance aggregation per faculty.

•	**Monthly Analysis** — Monthly performance trend per faculty.
________________________________________
**📊 Visualizations Included**

**Gender Distribution  :**  Countplot

**Overall Rating Distribution  :**  Histogram

**Technology Feedback  :**  Countplot

**Session Code vs Rating :**  Regression Plot

**Correlation Matrix  :**  Heatmap

**Faculty-wise Count  :**  Bar Chart (with labels)

**Subject-wise Rating  :**  Histogram with Hue

**Clustering Results  :**  KMeans Output

**Full Correlation Heatmap  :**  Coolwarm Heatmap
________________________________________
**📌 Key Insights**

•	📈 Higher session codes show a mild correlation with better overall ratings, suggesting student comfort increases over time.

•	🏫 Faculty-wise performance varies significantly — some professors consistently receive higher ratings across sessions.

•	💻 Technology usage quality directly impacts student satisfaction — students who rated technology as "Excellent" also gave higher overall ratings.

•	📚 Subject-wise clusters reveal that certain subjects (e.g., Power BI) receive consistently higher satisfaction scores than others.

•	📅 Weekly and monthly trends show dips and peaks in feedback, helping identify specific sessions that need attention.

•	⚖️ Gender distribution is relatively balanced, ensuring feedback is representative across the student population.
________________________________________

**▶️ How to Run**

1.	**Clone the repository**
   
   git clone https://github.com/your-username/student-feedback-sentiment-analysis.git
   cd student-feedback-sentiment-analysis
   
2.	**Install required libraries**
   
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   
3.	**Launch Jupyter Notebook**
   
   jupyter notebook project.ipynb
   
4.	Run all cells to reproduce the full analysis and visualizations.
________________________________________
**📋 Requirements**

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter
________________________________________

**🚀 Future Scope**

•	🔤 NLP Text Analysis — Add text-based feedback column and apply VADER / TextBlob for deeper sentiment scoring

•	📡 Real-Time Dashboard — Build a live Streamlit or Power BI dashboard connected to live feedback forms

•	🤖 Predictive Modeling — Train classification models to predict student satisfaction from session attributes

•	📧 Alert System — Automated alerts to faculty/admin when ratings drop below a threshold

•	🌐 Web Integration — Embed feedback collection and live analysis into a student portal

