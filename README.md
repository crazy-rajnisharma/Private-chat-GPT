Chat-with-docs-or-url-Chatbot
This Chatbot is an interactive app developed to assist users to interact with their PDF, Docs, txt or urls. It is built using Open Source Stack. No OpenAI is required.

Getting Started
Follow these steps to set up and run the project on your local machine.


#Installation
**Clone the repository**
git clone <repository_url>


**Create the necessary folders**

mkdir db
mkdir docs

**Add your model files to the 'models' folder**
clone LaMini-T5-738M from its git repository
https://huggingface.co/MBZUAI/LaMini-T5-738M


----
### Usage 


**Run the ingestion script to prepare the data** 
`python ingest.py`


**Start the chatbot application using Streamlit** 
`streamlit run chatbot_app.py`



![Screenshot 2024-01-29 143726 1](https://github.com/Tech-Savvy-Rajni/Private-chat-GPT/assets/157015217/657f7ae8-8010-4200-90a3-bddba9b66f10)
![Screenshot 2024-01-29 143645 1](https://github.com/Tech-Savvy-Rajni/Private-chat-GPT/assets/157015217/89ab8306-41c4-41ec-967b-443bb645419e)
![Screenshot 2024-01-29 143536 1](https://github.com/Tech-Savvy-Rajni/Private-chat-GPT/assets/157015217/36757e07-cc6f-4487-8e60-cebb4f3283cb)
![Screenshot 2024-01-29 143551 1 (1)](https://github.com/Tech-Savvy-Rajni/Private-chat-GPT/assets/157015217/1bb2b820-4280-4140-a8e2-55c1733d76de)
