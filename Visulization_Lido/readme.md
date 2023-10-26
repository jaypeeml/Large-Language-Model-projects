# Automatic Generation of Visualizations and analyzing data with LLM.

Tech Stack: LLM GPT 3.5-turbo-0301, LIDA, Streamlit, Google cloud, Vertex AI, Jupyter Notebook, Hugging Face

<h1> How to run the app?</h1>
<p> OpenAI instantly revokes the API key once it detects that the key has been exposed publicly. So, that's the only thing to take care of.</p>
 
 Generate your OpenAI API key here: <a href="https://platform.openai.com/account/api-keys"> Click Here </a>
<br>
<h2> Run on Colab </h2>
<p> If you are running the app on google colab notebook, then you can use the API key. 
  
  ```
  
  openai_api_key = 's#-#####################jz'
  
  #can set the API key directly, if running locally.
  
  ```
 
 Else if you want to keep the key private, store it in an environment variable named 'API_KEY' in your OS and then refer the key in app.py by:
 
  ```
  from dotenv import load_dotenv
  load_dotenv()
  openai_api_key = os.getenv("OPENAI_API_KEY")
 
  ```
  
 
  Henceforth make sure to have Streamlit installed in your system. Run the app by:
  

 <h2> Run on Cloud </h2>
 
 <p> You can also run this app locally on Streamlit Cloud, which is a free Cloud Hosting Service. 
 <br>
 Make a .env  file and store the key as 
 
 ```
 OPENAI_API_KEY='##-###############'
 
 ```
