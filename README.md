# Cyber-Threat-Classification-Using-Machine-Learning-Models
<h1 align="center">🛡️ Cyber Threat Classification</h1>
<p align="center">
  <b>Detecting and Classifying Network Threats Using Machine Learning</b><br>
  <i>Developed with Python, Scikit-learn, Pandas, and Visualization Libraries</i>
</p>

<hr>

<h2>📌 Project Overview</h2>
<p>
  This project focuses on identifying and classifying cyber attacks from network traffic data. Using multiple machine learning algorithms, we analyze patterns in features and build predictive models to differentiate between normal and malicious behavior.
</p>

<h2>📊 Dataset Reference<h2>

This project uses the **ToN_IoT Datasets** provided by UNSW Sydney.

- **Citation**:  
  UNSW Sydney. (n.d.). *ToN_IoT Datasets*. UNSW Research. Retrieved from [https://re-search.unsw.edu.au/projects/toniot-datasets](https://re-search.unsw.edu.au/projects/toniot-datasets)

- **Note**:  
  The dataset is not included in this repository due to size and licensing restrictions. Please visit the link above to download the data directly from the official source.


<h2>🧠 Technologies Used</h2>
<ul>
  <li>Python</li>
  <li>Jupyter Notebook</li>
  <li>NumPy & Pandas</li>
  <li>Scikit-learn</li>
  <li>Matplotlib & Seaborn</li>
</ul>

</pre>

<h2>🔍 Features</h2>
<ul>
  <li><b>Target:</b> <code>label</code> column (0 = Normal, 1 = Attack)</li>
  <li><b>Extra Class:</b> <code>type</code> column showing specific attack types</li>
  <li><b>Dropped Columns:</b> Sparse or irrelevant columns like <code>ssl_*</code>, <code>http_*</code>, and <code>weird_*</code></li>
  <li><b>EDA:</b> Value counts, bar plots, heatmaps for correlation and nulls</li>
</ul>

<h2>🧪 Models Used</h2>
<ul>
  <li>Logistic Regression</li>
  <li>Random Forest Classifier</li>
  <li>Decision Tree Classifier</li>
  <li>Support Vector Classifier (SVC)</li>
  <li>K-Nearest Neighbors</li>
  <li>MLP Classifier (Neural Network)</li>
</ul>

<h2>📈 Evaluation Metrics</h2>
<ul>
  <li>Accuracy Score</li>
  <li>Precision / Recall / F1 Score</li>
  <li>Confusion Matrix</li>
  <li>ROC Curve and AUC Score</li>
  <li>Classification Report</li>
</ul>

<h2>📊 Visualizations</h2>
<ul>
  <li>Label distribution (0 vs. 1)</li>
  <li>Attack type distribution</li>
  <li>Correlation heatmap of numeric features</li>
  <li>Missing values heatmap</li>
</ul>

<h2>🚀 How to Run</h2>

<ol>
  <li>Clone the repository:</li>
  <pre><code>git clone https://github.com/yourusername/Cyber_Threat_Classification.git
cd Cyber_Threat_Classification</code></pre>

  <li>Install dependencies:</li>
  <pre><code>pip install -r requirements.txt</code></pre>

  <li>Run the notebook:</li>
  <pre><code>jupyter notebook Cyber_Threat_Classification_(1).ipynb</code></pre>
</ol>

<h2>📈 Future Improvements</h2>
<ul>
  <li>Advanced model tuning with GridSearchCV</li>
  <li>Model export and deployment using Flask or FastAPI</li>
  <li>Real-time traffic classification</li>
  <li>Integration with live packet capture (e.g., using Scapy)</li>
</ul>

<h2>📜 License</h2>
<p>This project is licensed under the <b>MIT License</b>.</p>

<h2>🤝 Contributing</h2>
<p>Pull requests and suggestions are welcome. Fork the repo and open a PR to get started!</p>
