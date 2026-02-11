# Solar Energy Generation Monitoring System Using Fundamental Data Structures and Lightweight Machine Learning Techniques.

**Project Overview:**

   1. This project presents a clean, interpretable, and reproducible solar energy monitoring system designed for small rooftop and decentralized renewable energy installations.
   2. Instead of relying on complex deep learning or proprietary tools, the system demonstrates how fundamental data structures, classical statistics, and lightweight machine learning can be effectively used.
   3. Record daily solar energy generation.
   4. Analyze system performance over time.
   5. Detect abnormal or low-generation days.
   6. Support early fault identification.
   7. Provide clear visual insights for operators.
   8. The project prioritizes explainability, simplicity, and real-world usability.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Objectives:**

   1. Enable daily recording of solar energy generation (kWh).
   2. Maintain clean and validated historical data.
   3. Compute key performance metrics (total, average, variability)
   4. Identify anomalous or underperforming days.
   5. Present results through clear and intuitive visualizations.
   6. Ensure the entire system is easy to run on Google Colab.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Key Concepts Used:**

   1. Fundamental Data Structures.
   2. Lists (time-ordered energy values).
   3. Dictionaries (date-wise storage and indexing).
   4. Structured records using Python data classes.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Statistical Analysis:**

   1. Mean, minimum, maximum.
   2. Standard deviation and variability.
   3. Z-score–based anomaly detection.
   4. Lightweight Machine Learning.
   5. Isolation Forest (used only for diagnostic anomaly support).
   6. No black-box prediction or heavy training pipelines.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**System Features:**

1. Validated daily data entry.
2. Automatic handling of duplicate dates.
3. Summary performance statistics.
4. Detection of unusual generation patterns.
5. Clean plots for trends and distributions.
6. Fully reproducible execution.
7. Minimal setup, runs directly on Google Colab.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Outputs Generated:**

1. Numerical summaries.
2. Total energy generated.
3. Average daily generation.
4. Count of detected anomalies.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Visual outputs**

1. Daily energy generation trend.
2. Distribution of energy values.
3. Highlighted abnormal days.
4. These outputs help operators understand behavior, not just numbers.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Tech Stack:**

1. Programming Language: Python.
2. Data Handling: Python Lists, Dictionaries, Dataclasses.
3. Numerical Analysis: NumPy.
4. Data Management: Pandas.
5. Visualization: Matplotlib, Seaborn.
6. Machine Learning (Lightweight): Scikit-learn (Isolation Forest).
7. Environment: Google Colab.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**How to Run:**

1. Open Google Colab.
2. Upload the notebook.
3. Run all cells from top to bottom.
4. No additional configuration required.
5. The notebook is designed to be plug-and-play.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Use Cases:**

1. Rooftop solar plant operators.
2. Renewable energy students and researchers.
3. Engineers needing interpretable monitoring tools.
4. Educational demonstrations of applied data analytics.
5. Portfolio projects for data, ML, or sustainability roles.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Limitations:**

1. Weather parameters (irradiance, temperature) are not explicitly modeled.
2. Dataset size is limited to demonstration scope.
3. Focus is on monitoring and diagnostics, not forecasting.
4. These are intentional design choices to preserve clarity and simplicity.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Key Takeaway**:

 - Transparent data collection combined with basic analytical techniques is sufficient to deliver meaningful insights for renewable energy monitoring—without heavy models or complex infrastructure.
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**Key Contributions:**

   1. Agnish Brahma(prototyping).
   2. Dr. Prasun Bhattacherjee(Research Mentor).
____________________________________________________________________________________________________________________________________________________________________________________________________________________

**License:** MIT License.
____________________________________________________________________________________________________________________________________________________________________________________________________________________
