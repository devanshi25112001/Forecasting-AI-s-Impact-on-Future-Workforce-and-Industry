# **AI Impact Analysis on Industry and Workforce**  
*A Data Science Project on AI’s Influence Across Sectors*

## **Overview**  
This project analyzes **200,000 news articles** to evaluate **AI’s impact on industries and workforce trends**. Using **Natural Language Processing (NLP)** techniques, we identify AI adoption patterns in **technology, finance, healthcare, and energy**, uncover emerging trends, and assess sentiment across sectors. The study provides actionable insights for businesses, policymakers, and academia.

## **Key Findings**
- **Technology & Finance** sectors lead in AI adoption, with the highest positive sentiment.
- **Healthcare & Energy** show emerging potential but face AI-related challenges.
- **AI Disruptions in Jobs:** Repetitive roles like **data entry, customer support, and stock trading** are at risk.
- **Sentiment Analysis:** AI adoption sentiment **declined in 2024**, signaling rising concerns or regulatory challenges.
- **Top AI Influencers:** Organizations like **Microsoft, Google, and IBM** dominate AI discussions.

---

## **Methodology**
### **Data Collection & Preprocessing**
- Scraped and cleaned **200K+ articles** from various sources.
- Removed special characters, duplicate records, and non-AI-related content.
- Applied keyword filtering and **word count thresholds** for quality control.

### **Natural Language Processing (NLP)**
- **Topic Modeling:** Used **Latent Dirichlet Allocation (LDA)** to identify major AI discussions across industries.
- **Named Entity Recognition (NER):** Leveraged **spaCy** to extract key entities (companies, people, locations).
- **Sentiment Analysis:** Implemented **VADER** and **Yelp datasets** to assess AI perception across sectors.
- **Trend Analysis:** Mapped AI-related discussions over time using word frequency tracking.

### **Tech Stack**
- **Python:** Data preprocessing & NLP analysis
- **spaCy:** Named Entity Recognition (NER)
- **VADER & Yelp Datasets:** Sentiment analysis
- **LDA & k-train:** Topic modeling
- **Google Cloud Platform (GCP):** Scalable data storage and processing

# AI Impact on Industry & Workforce

## Setup & Installation

To run the project locally, follow these steps:

### 1. Clone the Repository
Ensure you have Git installed, then run the following command:

git clone https://github.com/your-username/AI-Impact-Industry-Workforce.git

cd AI-Impact-Industry-Workforce

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Run the Analysis

python ai_analysis.py


---
### **Results**
### **Top AI Trends**
| **Industry**                              | **Sentiment Score** | **AI Integration Readiness** |
|------------------------------------------|--------------------|-----------------------------|
| **Technology & AI Innovations**         | 165,927            | High                        |
| **Financial Services**                   | 22,299             | High                        |
| **Manufacturing & Industrial Automation**| 15,212             | Medium                      |
| **Energy & Sustainability**              | 6,727              | Emerging                    |


