# Generate README.txt file
content = """Surface Roughness & Cost Analysis

Predict surface roughness (Ra) and process cost (Kp) in dry turning of AISI H13 steel with CC6050 and PCBN7025 tools. Includes data prep, correlation & clustering analyses, box-/heat-maps, ML pipelines (DNN & Decision Tree) and GPT-based benchmarks.

🚀 Quickstart

1. Clone  
   git clone https://github.com/your-username/your-repo.git  
   cd your-repo

2. Create & activate your Python env  
   python3 -m venv .venv && source .venv/bin/activate

3. Install dependencies  
   pip install -r requirements.txt  
   apt-get install -y fonts-liberation

4. Run analyses  
   - Data prep & sampling:  
     python data_prep.py  
   - Correlation & clustering:  
     python correlation_clustering.py  
   - Boxplots & pairplots:  
     python viz_box_pair.py  
   - ML training & evaluation:  
     python ml_models.py  
   - GPT predictions (API key required):  
     python gpt_predictions.py

📁 Structure

data_prep.py
correlation_clustering.py
viz_box_pair.py
ml_models.py
gpt_predictions.py
requirements.txt
README.txt

⚙️ Configuration

- Font: Liberation Serif  
- ENV VAR for GPT:  
  export OPENAI_API_KEY=your_key_here

📊 Outputs

- Plots saved to plots/ (PNG)  
- Tables/Excel: comparative_ra_predictions.xlsx, resultados_*.csv
"""
with open('/mnt/data/README.txt', 'w') as f:
    f.write(content)

"/mnt/data/README.txt"
