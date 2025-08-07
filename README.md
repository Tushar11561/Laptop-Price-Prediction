# 💻 Laptop Price Prediction using Machine Learning

Welcome to the **Laptop Price Prediction** project!  
This ML project uses real-world laptop specifications to predict the price using regression models.

## 📌 Project Objective

To build a machine learning model that can accurately predict laptop prices based on technical specifications like RAM, processor, storage, GPU, OS, etc., and deploy it using **Gradio** for user interaction.

## 📁 Dataset

The dataset contains specifications of various laptops:
- RAM (in GB)
- Weight
- Touchscreen / IPS display
- Screen size & resolution (PPI calculated)
- CPU and GPU brand
- HDD / SSD details
- Operating System
- Price (Target Variable)

## ⚙️ Tools & Technologies Used

- **Python**
- **Pandas, Numpy, Matplotlib, Seaborn**
- **Scikit-learn** (Preprocessing, Regression, Pipeline)
- **Gradio** (For deployment)
- **Jupyter Notebook**

## 🔍 Key Highlights

- Performed **extensive EDA**
- Feature Engineering:
  - Extracted CPU/GPU brands
  - Converted screen resolution to PPI
  - Handled categorical variables using Label Encoding
- Built a **Linear Regression pipeline**
- Evaluated using:
  - **R² Score**
  - **Mean Absolute Error**
- Created an **interactive Gradio web app** inside notebook

## 🚀 Deployment

The model was deployed locally using **Gradio** inside the Jupyter Notebook.  
To use it:
1. Clone the repo
2. Run the notebook
3. Gradio will launch on `localhost` in your browser

> Note: The current version is deployed **locally**, not on cloud (like Hugging Face or Render). You can host it on platforms for public access.

## 📸 UI Preview


## 🧠 Model Performance

- **R² Score:** *~0.81*
- **MAE:** *~0.21*

## 🧾 How to Run

1. Clone this repository: git clone https://github.com/Tushar11561/Laptop-Price-Prediction
2. Install requirements: pip install -r requirements.txt
3. Run the notebook: jupyter notebook Laptop_price_pred.ipynb 
4. Gradio UI will open on `http://127.0.0.1:7860/`

## 🙋‍♂️ Author

**Tushar Mohite**  
LinkedIn: www.linkedin.com/in/tushar-mohite-29966628a

## ⭐️ Show Your Support

If you liked the project, please ⭐ the repository!  
Feel free to fork it and contribute ideas or improvements!

## 📌 Future Work

- Add cloud deployment (Hugging Face, Render, etc.)
- Add more regression models and comparison
- Improve UI and performance

