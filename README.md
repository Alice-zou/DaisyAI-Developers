# Natural-Disaster-Chatbot by DAISY-AI Developers
For the NeurIPS Highschool Challenge, our team "DAISY-AI Developers" developed a chatbot named DAISY (Disaster Awareness and Information Serving You). DAISY specifically focuses on recent and real-time data on natural disasters around the world, such as hurricanes, tornadoes, subsidence, wildfires, floods, and earthquakes. It is designed to provide accurate and timely information about natural disasters.
DAISY employs advanced Large Language Models (LLMs) to enhance user interaction and information dissemination. It offers real-time updates, educational content, and safety tips related to various natural disasters, including hurricanes, volcanic eruptions, wildfires, subsidence, tornadoes, earthquakes, and floods. 
This code repo includes the following programs. 
1. Real_Time_Weather_Updates_Dominick-Pelaia.ipynb
   
   This fetches real-time data from the Global Disaster Alert and Coordination System (GDACS) archives regarding natural disaster information.
   
3. Dataset_QA_Generation_Alice_jsonl_version.ipynb
   
   This generates question-and-answer pairs based on the natural disaster information. It takes a PDF file as input and then uses a LLM model to generate the Q&A pairs.
   
5. Dataset_QA_Generation_Alice_jsonl_multipdf_version.ipynb
   
   Similar to the above file, but it takes multiple PDF files as input and merges them into one.
   
7. FineTune28_QA.ipynb
   
   This fine-tunes the GPT-3.5-turbo model with Q&A pairs and then runs a chatbot to take user questions and provide answers.
   
9. Disaster_chatbot_Zephyr_7B_Alpha.ipynb
    
   It runs a chatbot using the Zephyr 7b Alpha model with RAG. It takes multiple PDF files as input and generates a public URL through which user can access the chatbot.

![image](https://github.com/Alice-zou/DaisyAI-Developers/assets/136283245/59762035-25fb-40f3-be5a-2e57f0abd2dc)
