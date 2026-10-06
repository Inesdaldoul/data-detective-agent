# 🕵️ Data Detective Agent
An AI agent that profiles, cleans and analyzes any messy CSV, then exports a PDF insight report.

**Live demo:** https://inesdaldoul.github.io/data-detective-agent/ (bring your own DeepSeek API key)

## Pipeline
Profile → Clean → Detect anomalies (IQR & Z-score) → 4 charts → DeepSeek insight report → PDF

## Run it
1. `pip install openai pandas numpy matplotlib seaborn reportlab`
2. `export DEEPSEEK_API_KEY=your_key`
3. Open `data_detective_agent.ipynb` and run all cells with `sample_dirty_data.csv`
