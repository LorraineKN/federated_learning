# Federated Learning for Diabetes Detection

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Node.js](https://img.shields.io/badge/Node.js-18%2B-green)](https://nodejs.org/)

A privacy-preserving system that enables hospitals to collaboratively train diabetes prediction models without sharing patient data.

## Features

- 🛡️ **Privacy-first**: Data never leaves local hospitals
- 🤝 **Collaborative**: Multiple institutions improve model together
- 🏥 **Clinical UI**: Doctor-friendly dashboard with explanations
- ⚡ **Fast predictions**: <500ms inference via ONNX runtime

## Quick Start

### Prerequisites

- Python 3.9+
- Node.js 18+

### Installation

```bash
# Clone repo
git clone https://github.com/LorraineKN/federated_learning.git
cd federated_learning

# Set up Python
python -m venv venv
source venv/bin/activate  # Linux/MacOS
# venv\Scripts\activate  # Windows
pip install -r requirements.txt

# Set up frontend
cd frontend
npm install

# Start backend (Flask + Flower)
cd backend
python flower.py

# In new terminal - start frontend
cd frontend
npm run dev
```

Access: `http://localhost:5173` # Your port could be different

## 🌐 Usage

### For Hospitals

- Upload anonymized patient data through the admin interface
- Participate in federated training rounds
- Monitor local model performance

### For Clinicians

- Enter patient symptoms through the dashboard
- View real-time diabetes risk predictions
- See explainable AI insights




