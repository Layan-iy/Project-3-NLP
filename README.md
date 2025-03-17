# Federated Learning for Movie Review Classification

## Project Objective
This project implements a **federated learning model** for **movie review classification**, based on the **Large Movie Review Dataset (IMDB)**. The main objective is to compare the **federated learning approach** with the **centralized learning approach**, evaluating their performance, implications for data privacy, and communication costs.

### **Federated Learning vs Centralized Learning:**
- **Federated Learning**: The data is not centralized; each client trains a model locally and only sends model updates. This helps preserve data privacy and manage scalability better.
- **Centralized Learning**: All data is sent to a central server for training, which raises privacy concerns and can be more costly in terms of communication.

This project aims to **evaluate the impact of federated learning** on model accuracy while reducing the risks associated with centralizing data.

---

##  Technologies Used
- **Python**  
- **Pandas, NumPy** (Data manipulation and preprocessing)
- **Scikit-learn** (Classification models)
- **TensorFlow / PyTorch** (Machine learning)
- **Flower** (Federated learning framework)
- **Matplotlib, Seaborn** (Visualization of results)

---

## Data Used
**Dataset: Large Movie Review Dataset (IMDB)**  
- **25,000 movie reviews** for training  
- **25,000 movie reviews** for testing  
- **Objective**: Predict whether a review is **positive or negative**

📎 **Dataset Reference**: [IMDB Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)  

The reviews are provided in **raw text** and are used to train a **supervised classification model**.

---

## Project Presentation
In the **`docs/`** folder, you will find a presentation file **`Presentation_Federated_Learning.pptx`** that provides a detailed overview of the project. This presentation covers the following aspects:

- **Federated Learning**: A comprehensive explanation of the method used to train a machine learning model without centralizing the data.
- **Comparison between Federated Learning and Centralized Learning**: The project explores the key differences between these two methods, particularly in terms of privacy, efficiency, and communication costs.
- **Technologies Used**: An overview of the tools and libraries employed in the project.
- **Results**: The model's performance and the analysis of privacy benefits through federated learning.

You can view and download this presentation to better understand the project’s objectives and implementation.

📎 **Link to the presentation**: [Project Presentation (PPT)](docs/Presentation_Federated_Learning.pptx)

---

## Project Execution

### Clone the Repository
Clone the project from GitHub using the following command:
```bash
git clone https://github.com/Layan-iy/Project-3-NLP.git
cd Project-3-NLP
```
Install dependencies
```bash
pip install -r requirements.txt
```
Run the training
```bash
python Python_Code.py
```
