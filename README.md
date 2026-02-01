# User Data Analysis: Keystroke Dynamics Biometrics

This project implements a behavioral biometric system that analyzes **Keystroke Dynamics** to identify or authenticate users based on their unique typing patterns. By measuring the timing of key presses and releases, we can build a "typing footprint" that is difficult to forge.

---

### 📄 Research Paper
For a detailed breakdown of the methodology, feature engineering, and experimental results, please refer to our paper:
* **Title:** [Insert Your Paper Title Here]
* **Status:** Preprint / In Submission
* **Link:** [Click here to view the paper](https://drive.google.com/file/d/1ivlq5H7iBzZfqyz4ea_gLXvVpQLvzmZP/view?usp=sharing)

---

### 🚀 Features
* **Feature Extraction:** Calculates timing metrics including:
  * **Dwell Time:** The duration a key is held down.
  * **Flight Time:** The time between releasing one key and pressing the next.
  * **N-Graph Timings:** Latency patterns for specific sequences (digraphs, trigraphs).
* **Data Visualization:** Heatmaps of typing speeds and distribution plots of user consistency.
* **Machine Learning Pipeline:** Comparison of various classifiers (e.g., Random Forest, SVM).

---

