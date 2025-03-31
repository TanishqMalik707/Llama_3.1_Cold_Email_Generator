#  Cold Mail Generator
AI-powered cold email generator for a services company using Groq, LangChain, and Streamlit. This tool enables users to input the URL of a company's careers page, automatically extracting job listings and analyzing job descriptions. It then generates highly personalized cold emails tailored to each role, incorporating relevant portfolio links retrieved from a vector database for maximum impact. By leveraging cutting-edge AI models and natural language processing, the system ensures that outreach efforts are precise, engaging, and optimized for higher response rates.


## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   
