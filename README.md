# AI-Based Cyber Threat Detection Framework

An intelligent intrusion detection system that uses Machine Learning to analyze network traffic and classify potential cyber threats (e.g., DDoS, Brute Force, Infiltration) in real time.

## Binder deployment badge
[(https://mybinder.org)](https://mybinder.org/v2/gh/Ankity399/AI-Based-Cyber-Threat-Detection/HEAD)



## 🚀 Features
* **Data Preprocessing:** Robust cleaning, handling of missing values, and scaling of network packet features.
* **Feature Engineering:** Automated selection of the most critical network indicators using Random Forest feature importance.
* **Anomaly Detection:** Dual-model architecture utilizing **Random Forest** for supervised attack classification and **Isolation Forest** for zero-day anomaly detection.
* **Performance Metrics:** Comprehensive evaluation metrics including Accuracy, Precision, Recall, F1-Score, and a Visual Confusion Matrix.

## 📂 Project Structure
* `cyber_threat_detector.ipynb` -> Main Jupyter Notebook containing the full pipeline.
* `requirements.txt` -> List of dependencies required to run the project.
* `README.md` -> Project documentation and setup guide.

## 🛠️ Local Setup Instructions
1. Clone this repository:
   ```bash
   git clone <your-repository-url>
   cd AI-Based-Cyber-Threat-Detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook cyber_threat_detector.ipynb
   ```

## 📊 Dataset Recommendation
To fully test this framework, download the official **[UNSW-NB15 Dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)** or the **[CICIDS2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)**. Place the CSV files in a `data/` directory before running the notebook.

## 📝 License
This project is licensed under the MIT License.
