# Multiple_PDF_Q-A
An LLM Application which uses google gemini model and can perform question answering on multiple pdf's

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/siddhantsharma97/Multiple_PDF_Q-A.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n gemini python=3.9 -y
```

```bash
conda activate gemini
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```
### STEP 03- Store the Google API key in .env file

```bash
 GOOGLE_API_KEY="<Your_API_Key"
```
### STEP 04- Run the streamlit application
```bash
streamlit run app.py
```