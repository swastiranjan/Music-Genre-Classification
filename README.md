## Music Genre Classification (GTZAN Dataset)

This project classifies music into 10 genres using audio features extracted from the GTZAN dataset.
A Random Forest classifier is trained on both 30-second and 3-second versions of the dataset.

📊 Results
Dataset	Samples	Accuracy
30-second clips	1000	78%
3-second sliced clips	~10,000	87% ✔️

The 3-second dataset greatly improves accuracy due to more training samples.

📂 Project Structure
music-genre-classification/
│
├── music-genre-classification.ipynb
├── images/
│   ├── confusion_matrix30s.png
│   └── confusion_matrix3s.png
└── data/
    └── README.md


The GTZAN dataset and trained model (.joblib) are not included due to size restrictions.

🧠 Features Used

Extracted using librosa:

MFCCs

Chroma STFT

Spectral Centroid & Rolloff

Zero-Crossing Rate

RMS Energy

Tempo

🏁 Summary

Built ML pipeline for audio classification

Trained and compared models on two dataset versions

Achieved 87% accuracy with Random Forest on 3-second data

Included confusion matrices and evaluation metrics
