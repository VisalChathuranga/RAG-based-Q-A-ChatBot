# Interview-Question-Creator-Project

### How to run?

1. Create an environment

```bash
conda create -n qachatbot python=3.10 -y
```
2. Activate an environment

```bash
conda activate qachatbot    or   
source activate qachatbot

```

3. install requirements

```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory and add your Gemini credentials as follows:

```ini
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

5. Run Programme

```bash
 streamlit run app.py
 ```