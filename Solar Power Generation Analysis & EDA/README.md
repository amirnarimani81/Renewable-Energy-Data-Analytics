<h1 align="center"> Solar Power Generation Analysis & Exploratory Data Analysis (EDA)</h1>

<p align="center">
<b>Solar Photovoltaic (PV) Analytics • Time Series Analysis • Data Visualization • Energy Intelligence</b>
<br><br>
Python • Pandas • Plotly • Seaborn • Renewable Energy Analytics
</p>

---

<h2> 1. Project Overview</h2>

<p>
This project presents a comprehensive <b>Exploratory Data Analysis (EDA)</b> of solar photovoltaic (PV) power generation using operational and environmental datasets collected from two solar power plants.
</p>

<p>
The analysis combines generation data with weather sensor measurements to investigate energy production patterns, evaluate inverter performance, analyze environmental impacts, and identify operational trends that influence solar power generation.
</p>

<p>
The project demonstrates an end-to-end analytics workflow including data cleaning, exploratory analysis, statistical evaluation, time-series visualization, and business interpretation, providing valuable insights for renewable energy management and operational optimization.
</p>

---

<h2> 2. Engineering / Business Problem</h2>

<p>
Solar photovoltaic generation is highly dependent on environmental conditions and equipment performance. Power generation varies continuously due to changes in solar irradiation, module temperature, ambient temperature, weather conditions, and inverter efficiency.
</p>

<p>
Without effective monitoring and data-driven analysis, utility operators may experience reduced energy production, delayed fault detection, lower operational efficiency, and increased maintenance costs.
</p>

<h3>Business Challenges</h3>

<ul>

<li>Understand factors influencing solar power generation.</li>

<li>Monitor inverter and source performance.</li>

<li>Detect abnormal production behavior.</li>

<li>Optimize maintenance scheduling.</li>

<li>Improve forecasting and operational planning.</li>

<li>Maximize renewable energy efficiency.</li>

</ul>

<p>
This project addresses these challenges by analyzing generation and weather datasets to support evidence-based operational and engineering decisions.
</p>

---

<h2> 3. Objectives</h2>

<ul>

<li>Perform comprehensive exploratory data analysis (EDA).</li>

<li>Clean and integrate multi-source solar datasets.</li>

<li>Analyze hourly, daily, weekly, and cumulative energy production.</li>

<li>Evaluate relationships between weather variables and power generation.</li>

<li>Compare AC and DC power generation performance.</li>

<li>Identify trends, seasonal behavior, and anomalies.</li>

<li>Visualize energy production using professional dashboards and statistical plots.</li>

<li>Generate actionable insights for solar plant optimization.</li>

</ul>

---
<h2> 4. Dataset Description</h2>

<p>
The project utilizes operational and weather datasets collected from two photovoltaic (PV) solar plants.
</p>

<table>

<tr>
<th>Dataset</th>
<th>Description</th>
</tr>

<tr>
<td>Plant 1 Generation</td>
<td>AC Power, DC Power, Daily Yield, Total Yield</td>
</tr>

<tr>
<td>Plant 1 Weather</td>
<td>Ambient Temperature, Module Temperature, Irradiation</td>
</tr>

<tr>
<td>Plant 2 Generation</td>
<td>AC Power, DC Power, Daily Yield, Total Yield</td>
</tr>

<tr>
<td>Plant 2 Weather</td>
<td>Ambient Temperature, Module Temperature, Irradiation</td>
</tr>

</table>

<h3>Main Variables</h3>

<ul>

<li>Date & Time</li>

<li>Source Key (Inverter)</li>

<li>AC Power</li>

<li>DC Power</li>

<li>Daily Yield</li>

<li>Total Yield</li>

<li>Ambient Temperature</li>

<li>Module Temperature</li>

<li>Irradiation</li>

</ul>

---

<h2> 5. End-to-End Workflow</h2>

<ol>

<li>

<b>Data Loading</b>

<ul>

<li>Import generation datasets</li>

<li>Import weather datasets</li>

<li>Merge multiple data sources</li>

</ul>

</li>

<li>

<b>Data Cleaning</b>

<ul>

<li>Handle missing values</li>

<li>Remove duplicate observations</li>

<li>Validate data types</li>

<li>Convert timestamps</li>

<li>Data quality assessment</li>

</ul>

</li>

<li>

<b>Exploratory Data Analysis</b>

<ul>

<li>Summary statistics</li>

<li>Distribution analysis</li>

<li>Correlation analysis</li>

<li>Missing value analysis</li>

<li>Outlier detection</li>

<li>Time-series visualization</li>

</ul>

</li>

<li>

<b>Visualization</b>

<ul>

<li>Line Charts</li>

<li>Bar Charts</li>

<li>Boxplots</li>

<li>Histograms</li>

<li>Pie Charts</li>

<li>Correlation Heatmaps</li>

<li>Animated Plotly Visualizations</li>

<li>Moving Average Analysis</li>

</ul>

</li>

<li>

<b>Business Interpretation</b>

<ul>

<li>Operational performance evaluation</li>

<li>Environmental impact assessment</li>

<li>Power generation optimization</li>

<li>Engineering recommendations</li>

</ul>

</li>

</ol>

---

<h2> 6. Technologies Used</h2>

<h3>Programming</h3>

<ul>

<li>Python</li>

</ul>

<h3>Libraries</h3>

<ul>

<li>Pandas</li>

<li>NumPy</li>

<li>Matplotlib</li>

<li>Seaborn</li>

<li>Plotly</li>

</ul>


---

<h2> 7. Results</h2>

<p>
The exploratory analysis revealed several important operational and environmental insights regarding solar photovoltaic system performance.
</p>

<ul>

<li>Daily energy production exhibits moderate variability with occasional production spikes.</li>

<li>Peak electricity generation occurs during midday when solar irradiation is highest.</li>

<li>Morning and evening periods consistently produce lower output.</li>

<li>Strong positive correlation exists between irradiation and generated power.</li>

<li>Module temperature significantly influences DC and AC power production.</li>

<li>AC and DC power remain highly correlated, indicating stable inverter efficiency.</li>

<li>Weekly and monthly analyses reveal recurring operational patterns.</li>

<li>Performance differences exist among inverter sources.</li>

</ul>

---

<h2> 8. Key Insights</h2>

<ul>

<li>Solar irradiation is the strongest driver of photovoltaic power generation.</li>

<li>Module temperature directly influences electricity production efficiency.</li>

<li>Daily production follows predictable solar cycles.</li>

<li>AC and DC power maintain strong correlation throughout the observation period.</li>

<li>Some inverter sources consistently outperform others.</li>

<li>Correlation heatmaps clearly identify environmental variables affecting production.</li>

<li>Moving averages effectively smooth short-term fluctuations.</li>

<li>Interactive visualizations improve operational monitoring.</li>

<li>Combining weather and production datasets provides deeper engineering insights.</li>

<li>Data-driven monitoring supports preventive maintenance and production optimization.</li>

</ul>

---

<h2> 9. Repository Structure</h2>

<pre>
Solar-Power-Generation-EDA/
│
├── data/
│   ├── Plant_1_Generation.csv
│   ├── Plant_1_Weather.csv
│   ├── Plant_2_Generation.csv
│   └── Plant_2_Weather.csv
│
├── notebooks/
│   └── Solar_Generation_EDA.ipynb
│
├── images/
│   ├── distributions/
│   ├── line_plots/
│   ├── heatmaps/
│   ├── boxplots/
│   ├── animated/
│   └── insights/
│
├── src/
│   ├── preprocessing.py
│   ├── visualization.py
│   ├── statistics.py
│   └── analysis.py
│
├── README.md
├── requirements.txt
└── LICENSE
</pre>

---

<h2> 10. Future Improvements</h2>

<ul>

<li>Develop an interactive Streamlit dashboard.</li>

<li>Build machine learning models for solar power forecasting.</li>

<li>Implement anomaly detection for inverter faults.</li>

<li>Predict future power generation using LSTM and GRU models.</li>

<li>Integrate real-time weather APIs.</li>

<li>Perform predictive maintenance analysis.</li>

<li>Develop energy efficiency monitoring dashboards.</li>

<li>Optimize inverter performance using machine learning.</li>

<li>Deploy cloud-based renewable energy analytics applications.</li>

<li>Expand analysis using additional photovoltaic plant datasets.</li>

</ul>

---

<h2> Conclusion</h2>

<p>
This project demonstrates a complete end-to-end exploratory data analysis workflow for solar photovoltaic power generation by integrating operational generation data with environmental sensor measurements.
</p>

<p>
The analysis uncovers important relationships between weather conditions and energy production, identifies operational trends, evaluates inverter performance, and provides actionable insights for improving solar plant efficiency. By combining statistical analysis, time-series exploration, and interactive visualization, the project establishes a strong foundation for predictive analytics, intelligent monitoring, and data-driven renewable energy management.
</p>