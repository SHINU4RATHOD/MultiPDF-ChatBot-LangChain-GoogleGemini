# MultiPDF-ChatBot-LangChain-GoogleGemini

# workflow
* clone repo

### STEP 01- Create a conda environment after opening the repository
```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE-GEMINI credentials as follows:

```ini
GOOGLE_GEMINI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

# Run app file 
```bash
streamlit run app.py
```