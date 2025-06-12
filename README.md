# 🛍️ GenAI-Powered E-Commerce Product Recommendation System

This project builds an intelligent recommendation engine using Generative AI for an e-commerce platform. It processes product data and user interactions to deliver personalized product suggestions. Ideal for enhancing shopping experiences and boosting product visibility.

---

## 🚀 Features

- Product recommendation using Generative AI logic
- Preprocessing of e-commerce product dataset
- User input-based query interface
- Simple Streamlit interface for deployment
- Example dataset from Flipkart's product listings

---

## 📂 Project Structure

├── app.py # Main Streamlit app
├── data_processing.py # Data cleaning & transformation
├── recommendation.py # Recommendation logic (GenAI-enhanced)
├── flipkart_com-ecommerce_sample.csv # Sample dataset
├── requirements.txt # Python dependencies
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🧠 How It Works

1. **Load & Clean Data**: The dataset is cleaned and structured using `data_processing.py`.
2. **Text Embedding & Recommendation**: `recommendation.py` computes similarity scores using AI-powered embeddings.
3. **User Interface**: `app.py` provides a Streamlit UI where users input a product query and receive recommendations.

---

## 📊 Dataset

- **Source**: Flipkart Product Listings  
- **Columns**: Product name, Category, Rating, Price, Description

---

## 🛠️ Installation & Usage

```bash
# Clone the repo
git clone https://github.com/yourusername/Ecommerce_recommendation_using_GenAI.git
cd Ecommerce_recommendation_using_GenAI

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
🧪 Example Use Case
User inputs:
"Looking for budget smartphones under 10,000 with good camera"

→ System returns 5+ relevant recommendations with key product info.

📌 Tech Stack
Python, Pandas, NumPy

Streamlit for UI

Sentence Transformers / Embeddings for semantic similarity

CSV data backend

📄 License
This project is licensed under the MIT License.

🙌 Contributions
Pull requests and ideas are welcome! For major changes, please open an issue first to discuss what you would like to change.

kotlin
Copy
Edit
