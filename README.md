# Natural-Disaster-Chatbot by DAISY-AI Developers
For the NeurIPS Highschool Challenge, our team "DAISY-AI Developers" developed a chatbot named DAISY (Disaster Awareness and Information Serving You). DAISY specifically focuses on recent data and real time data on natural disasters around the world, such as hurricanes, tornadoes, subsidence, wildfires, floodings, and earthquakes. It is designed to provide accurate and timely information about natural disasters.
DAISY employs advanced Large Language Models (LLMs) to enhance user interaction and information dissemination. It offers real-time updates, educational content, and safety tips related to various natural disasters, including hurricanes, volcanic eruptions, wildfires, subsidence, tornadoes, earthquakes, and floods. 
This code repo includes the following programs. 
1. Real_Time_Weather_Updates_Dominick-Pelaia.ipynb
   It downloads real-time data from Internet regarding natural disaster information.
3. Dataset_QA_Generation_Alice_jsonl_version.ipynb
   It generates question and answer pairs based on the natural disaster information. It takes a PDF file as input and then uses a LLM model to generate the Q&A pairs.
4. Dataset_QA_Generation_Alice_jsonl_multipdf_version.ipynb
   Similar as above but it takes multiple PDF files as input and merge then into one. So that it saves user time when there are many files to be processed.
5. FineTune28_QA.ipynb
   It fine-tunes GPT-3.5-turbo model with Q&A pairs. And then it runs a chatbot using the fine-tuned model to take user questions and provide answers.
6. Disaster_chatbot_Zephyr_7B_Alpha.ipynb
   It runs a chatbot with RAG and Zephyr model. It takes multiple PDF files as input. It generates a public URL via which user can access the chatbot in a web page UI.    

![image](https://github.com/Alice-zou/DaisyAI-Developers/assets/136283245/59762035-25fb-40f3-be5a-2e57f0abd2dc)
