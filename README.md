# 🔬 Glass Type Classification using Machine Learning

A Machine Learning project to classify different types of glass based on their chemical composition using **K-Nearest Neighbors (KNN)** and **Support Vector Machine (SVM)** algorithms. Different types of glass are used for various purposes, such as windows, containers, tableware, and headlights. Manually identifying the type of glass using chemical composition is difficult and time-consuming. This project automates glass classification using Machine Learning.

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/921d9aa7-e599-4c21-8d44-bb3d7b9fe60e" />
<img width="1097" height="982" alt="image" src="https://github.com/user-attachments/assets/a98fb904-8b48-41b2-bff4-9bdaff024c50" />
<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/57e1e360-71ae-4b91-8207-958110d5f043" />
<img width="726" height="590" alt="image" src="https://github.com/user-attachments/assets/48bde5d5-4c2b-452c-a557-9137dccca18f" />
<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/dee97b48-30cd-4162-b284-64a5e76e1ff8" />
<img width="726" height="590" alt="image" src="https://github.com/user-attachments/assets/7a209433-d1e5-4399-9d04-912eea04b3c0" />
<img width="1389" height="1190" alt="image" src="https://github.com/user-attachments/assets/afad3537-b6af-4cf9-b8a5-80114590a903" />



### Chemical Features
- **RI** - Refractive Index
- **Na** - Sodium (%)
- **Mg** - Magnesium (%)
- **Al** - Aluminum (%)
- **Si** - Silicon (%)
- **K** - Potassium (%)
- **Ca** - Calcium (%)
- **Ba** - Barium (%)
- **Fe** - Iron (%)

### Glass Types
| Type | Description |
|------|-------------|
| 1 | Building Windows (Float Processed) |
| 2 | Building Windows (Non-Float) |
| 3 | Vehicle Windows (Float) |
| 5 | Containers  |
| 6 | Tableware |
| 7 | Headlamps |

> *Note: Type 4 (Vehicle Windows Non-Float) is not present in the dataset*

##  Algorithms Used

### 1. K-Nearest Neighbors (KNN)
- Classifies based on majority vote of k nearest neighbors
- Optimal k value determined through cross-validation
- Simple and interpretable

### 2. Support Vector Machine (SVM)
- Finds optimal hyperplane for class separation
- Multiple kernels tested (Linear, RBF, Polynomial)
- Effective for high-dimensional data

##  Features

- Data preprocessing and exploratory analysis
- Feature scaling using StandardScaler
- Hyperparameter tuning for optimal performance
- Model comparison and evaluation
- Comprehensive visualizations
- **Interactive Glass Classifier** with:
  - Image upload capability
  - Chemical property input sliders
  - Sample data buttons for quick testing
  - Real-time predictions from both models

## 📈 Results

| Model | Accuracy |
|-------|----------|
| KNN | ~70% |
| SVM | ~68% |

*Actual results may vary based on random state*

### Using the Interactive Classifier
1. **Upload an image** (optional) - for visual reference
2. **Enter chemical properties** using sliders OR click sample buttons
3. **Click "CLASSIFY GLASS TYPE"** to get predictions

##  Technologies Used

- **Python 3.8+**
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization
- **Scikit-learn** - Machine Learning
- **ipywidgets** - Interactive UI
- **Pillow** - Image processing


##  Acknowledgments

- UCI Machine Learning Repository for the Glass Identification Dataset
- Scikit-learn documentation and community

## 👤 Author

**HOSEN ARAFAT**  

**Software Engineer, China**  

**GitHub:** https://github.com/arafathosense

**Researcher: Artificial Intelligence, Machine Learning, Deep Learning, Computer Vision, Image Processing**
