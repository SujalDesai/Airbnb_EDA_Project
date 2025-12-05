<h1>🏠 Airbnb_EDA_Project</h1>

<h2>📌 Overview</h2>
<p>
This project performs <b>Exploratory Data Analysis (EDA)</b> on the New York Airbnb dataset using Python. 
The goal is to uncover insights about listings, hosts, pricing, and neighborhood trends — showcasing skills in 
data cleaning, visualization, and storytelling.
</p>

<h2>🎯 Objectives</h2>
<ol>
  <li>Understand the distribution of Airbnb listings across New York neighborhoods.</li>
  <li>Analyze pricing trends and identify outliers.</li>
  <li>Visualize relationships between location, price, and availability.</li>
</ol>

<h2>🛠️ Tech Stack</h2>
<ul>
  <li>Python (Pandas, NumPy, Matplotlib, Seaborn)</li>
  <li>Jupyter Notebook</li>
  <li>Dataset: New York Airbnb Open Data (CSV format) (from Kaggle)</li>
</ul>

<h2>🚀 How to Run</h2>
<p><b>Clone the repository:</b></p>
<pre><code>git clone https://github.com/your-username/Airbnb_EDA_Project.git
cd Airbnb_EDA_Project
</code></pre>

<p><b>Install dependencies (run this in your terminal):</b></p>
<pre><code>pip install pandas numpy matplotlib seaborn jupyter
</code></pre>

<p><b>Launch Jupyter Notebook:</b></p>
<pre><code>jupyter notebook airbnb_eda.ipynb
</code></pre>

<p><b>Dataset setup:</b> Ensure that the file <code>airbnb.csv</code> is in the same folder as <code>airbnb_eda.ipynb</code>. 
The notebook will read it directly using:</p>
<pre><code>import pandas as pd
df = pd.read_csv("airbnb.csv")
</code></pre>

<h2>📌 Future Work</h2>
<ol>
  <li>Add interactive dashboards (Plotly, Dash, or Streamlit).</li>
  <li>Integrate predictive modeling (e.g., price prediction, demand forecasting).</li>
  <li>Automate data cleaning pipelines.</li>
</ol>
