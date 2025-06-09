# Data Annnotation Platform

![Annotation Interface Preview](https://i.imgur.com/JQ7Gh5l.png) *(Example screenshot placeholder)*

A collaborative platform for labeling and analysing Data with:
- **Multi-user annotation support**
- **Custom labeling schemas**
- **Quality control metrics**
- **ML-assisted tagging**

## 🚀 Features

| Feature | Description |
|---------|-------------|
| **Flexible Schemas** | Define custom labels for sentiment, intent, toxicity etc. |
| **Active Learning** | Prioritises uncertain samples for annotation |
| **IAA Metrics** | Calculates Cohen's Kappa for annotator agreement |
| **Export Formats** | CSV, JSON, or direct database connection |


## 📦 Installation

### Prerequisites
- Python 3.8+
- Google API Key ([Get one here](https://console.cloud.google.com/apis/credentials))

### Quick Start
```bash
# Clone repo
git clone https://github.com/jinka97/data-annotation.git
cd data-annotation

# Install dependencies
pip install -r requirements.txt

# Configure environment
cp .env.example .env
# Edit .env with your API keys

# Launch interface
python app.py
