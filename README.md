# Solar Energy Generation Monitoring System Using Fundamental Data Structures and Lightweight Machine Learning Techniques.

**Project Overview:**

   1. This project presents a clean, interpretable, and reproducible solar energy monitoring system designed for small rooftop and decentralized renewable energy installations.
   2. Instead of relying on complex deep learning or proprietary tools, the system demonstrates how fundamental data structures, classical statistics, and lightweight machine learning can be effectively used
   3. Record daily solar energy generation
   4. Analyze system performance over time
   5. Detect abnormal or low-generation days\
   6. Support early fault identification
   7. Provide clear visual insights for operators
   8. The project prioritizes explainability, simplicity, and real-world usability.

**Objectives:**

   1. Enable daily recording of solar energy generation (kWh).
   2. Maintain clean and validated historical data.
   3. Compute key performance metrics (total, average, variability)
   4. Identify anomalous or underperforming days.
   5. Present results through clear and intuitive visualizations.
   6. Ensure the entire system is easy to run on Google Colab.

**Key Concepts Used:**

   1. Fundamental Data Structures.
   2. Lists (time-ordered energy values).
   3. Dictionaries (date-wise storage and indexing).
   4. Structured records using Python data classes.

**Statistical Analysis:**

   1. Mean, minimum, maximum.
   2. Standard deviation and variability.
   3. Z-score–based anomaly detection.
   4. Lightweight Machine Learning.
   5. Isolation Forest (used only for diagnostic anomaly support).
   6. No black-box prediction or heavy training pipelines.

**System Features:**

✔ Validated daily data entry.
✔ Automatic handling of duplicate dates.
✔ Summary performance statistics.
✔ Detection of unusual generation patterns.
✔ Clean plots for trends and distributions.
✔ Fully reproducible execution.
✔ Minimal setup, runs directly on Google Colab.

**Outputs Generated:**

1. Numerical summaries.
2. Total energy generated.
3. Average daily generation.
4. Count of detected anomalies.

**Visual outputs**

1. Daily energy generation trend.
2. Distribution of energy values.
3. Highlighted abnormal days.
4. These outputs help operators understand behavior, not just numbers.

**Tech Stack:**

Programming Language: Python.
Data Handling: Python Lists, Dictionaries, Dataclasses.
Numerical Analysis: NumPy.
Data Management: Pandas.
Visualization: Matplotlib, Seaborn.
Machine Learning (Lightweight): Scikit-learn (Isolation Forest).
Environment: Google Colab.

**How to Run:**

1. Open Google Colab.
2. Upload the notebook.
3. Run all cells from top to bottom.
4. No additional configuration required.
5. The notebook is designed to be plug-and-play.

**Use Cases:**

1. Rooftop solar plant operators.
2. Renewable energy students and researchers.
3. Engineers needing interpretable monitoring tools.
4. Educational demonstrations of applied data analytics.
5. Portfolio projects for data, ML, or sustainability roles.

**Limitations:**

1. Weather parameters (irradiance, temperature) are not explicitly modeled.
2. Dataset size is limited to demonstration scope.
3. Focus is on monitoring and diagnostics, not forecasting.
4. These are intentional design choices to preserve clarity and simplicity.

**Key Takeaway**:
 - Transparent data collection combined with basic analytical techniques is sufficient to deliver meaningful insights for renewable energy monitoring—without heavy models or complex infrastructure.

**Key Contributions:**

Agnish Brahma(prototyping), Dr. Prasun Bhattacherjee(Research Mentor).
B.Tech CSE (Final Year).
Focus Areas: Data Analytics, Machine Learning, Renewable Energy Systems.

📄 License

This project is intended for academic, educational, and portfolio use.
