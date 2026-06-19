### 1: Download Code
make github account : www.github.com

download zip file of this repo : https://github.com/mr-ahtashamulhaq/research-agent-proj-v1


### 2: Set Up Your API Keys

> 🔑 Get your keys from:
> - **Groq**: https://console.groq.com
> - **Tavily**: https://tavily.com

Create a `.env` file in this folder:


GROQ_API_KEY = put your_groq_api_key_here
TAVILY_API_KEY = put your_tavily_api_key_here



### 3: Open it in VScode and run these commands one by one

python -m venv venv

venv\Scripts\activate

pip install -r requirements.txt

streamlit run frontend.py

🎉 Open your browser at **http://localhost:8501** and start researching!


### Make any changes in code if needed.



### Open Github
create new repo (give any name)

drag and drop this complete code folder there


### Open streamlit
Go to `share.streamlit.io` and sign in with GitHub

Click "New app" and Select your repo

Set `Main file path` → frontend.py

Click "Advanced settings" → paste your secrets

GROQ_API_KEY = "your key in double quotes"
TAVILY_API_KEY = "your key in double quotes"


Click "Deploy!"