# Web Content Classification with DistilBERT

An end-to-end project that fine-tunes a DistilBERT model for sequence classification and uses Selenium with BeautifulSoup to scrape web pages and predict their content categories. This project showcases the power of HuggingFace Transformers in building custom NLP solutions.

---

## 🚀 Features

- **Custom Fine-Tuning:**  
  Fine-tune DistilBERT on a custom dataset for precise web content classification.

- **Web Scraping:**  
  Utilize Selenium and BeautifulSoup to extract textual data from live web pages.

- **Inference Pipeline:**  
  Predict and categorize web content into labels like Business, Health, Sports, and more.

- **Data Visualization:**  
  Visualize training data distributions and monitor model performance with Matplotlib and Seaborn.

---

## 🔧 Tech Stack

- **Languages:** Python  
- **Libraries & Frameworks:**
  - [Transformers](https://huggingface.co/transformers/)
  - [PyTorch](https://pytorch.org/)
  - [Selenium](https://www.selenium.dev/)
  - [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
  - [Pandas](https://pandas.pydata.org/)
  - [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/)
  - [scikit-learn](https://scikit-learn.org/)
- **Environment Management:** dotenv

---

## 📁 Project Structure
├── huggingface.py # Inference script: Load model, scrape webpage, and classify content ├── transformer.py # Fine-tuning script: Data preprocessing, model fine-tuning, and training visualization ├── Dataset - Training Data.csv # Training dataset for fine-tuning ├── requirements.txt # Python dependencies └── README.md # Project documentation


---

## 🔥 Getting Started

### Prerequisites

- Python 3.7+
- Google Chrome (for Selenium WebDriver)

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/your_username/web-content-classification.git
   cd web-content-classification

