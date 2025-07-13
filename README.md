\# A Reproducible Pipeline for Leveraging Operational Data through Machine Learning in Digitally Emerging Urban Bus Fleets



This repository contains the complete machine learning pipeline developed for the study:



\*\*"A Reproducible Pipeline for Leveraging Operational Data through Machine Learning in Digitally Emerging Urban Bus Fleets"\*\*, submitted to \*Applied Sciences (MDPI)\*, Special Issue on Big-Data-Driven Advances in Smart Maintenance and Industry 4.0.



---



\## Overview



This work presents a reproducible and adaptive ML pipeline for predictive maintenance in hybrid urban buses operating under data scarcity conditions. The project includes:



\- Preprocessing and cleaning of ECU (Electronic Control Unit) data

\- Feature engineering based on fuel intensity and operational logic

\- Application of interpretable and lightweight models (Linear Regression, Ridge, KNN, Decision Tree)

\- Techniques adapted for limited datasets (SMOGN, LOOCV)

\- Batch retraining strategy based on temporal validation

\- Model evaluation using standard regression metrics (R², MAE, RMSE) and residual plots

\- Explainability via Permutation Importance



---



```



\## 🧠 Folder Structure



urban-bus-ml-pipeline/

├── notebooks/ # Main Jupyter notebook with the full analysis

├── src/ # Python modules for preprocessing, modeling, evaluation

├── data/ # Data folder (excluded from GitHub)

├── figures/ # Generated plots and result visuals

├── requirements.txt # Python dependencies

├── .gitignore # Ignored files and folders

├── LICENSE # Open-source license

└── README.md # Project documentation



```



---



\## 💾 Dataset



The dataset used in this study is publicly available via Mendeley Data:



🔗 \*\*\[Access the dataset here](https://data.mendeley.com/datasets/3sk43brs4p/1)\*\*  

📌 \*\*DOI:\*\* \[10.17632/3sk43brs4p.1](https://doi.org/10.17632/3sk43brs4p.1)



To run the analysis, download the dataset and place the corresponding files in the `data/` directory.



---



\## How to Run



1\. \*\*Clone this repository\*\*:



```bash

git clone https://github.com/ramonsanchez0213/urban-bus-ml-pipeline.git

cd urban-bus-ml-pipeline

```



2\. Install dependencies:





```

pip install -r requirements.txt

```



3\. Run the notebook:



Open notebooks/main\_pipeline.ipynb using Jupyter and execute the cells step by step.



Tested with Jupyter Notebook version 7.2.2.



\### Requirements



This project was developed using:



&nbsp;- Python 3.10

 - pandas

 - numpy

 - scikit-learn

 - seaborn

 - matplotlib

 - imbalanced-learn

 - smogn



(See requirements.txt for the full list.)



\## Author



\*\*Ramón Eduardo Sánchez Márquez\*\*

Email: ramonsanchez0213@gmail.com / resanmar@upv.edu.es / resanmar@mot.upv.es

Ph.D. Candidate – CMT-Clean Mobility \& Thermofluids

Universitat Politècnica de València (UPV)

GitHub: \[@ramonsanchez0213](https://github.com/ramonsanchez0213)



\## License

This project is released under the MIT License. See the LICENSE file for more information.



\## Citation Statement for Publications

To reinforce the reproducibility of this study, the full implementation code is publicly available at:



https://github.com/ramonsanchez0213/urban-bus-ml-pipeline



