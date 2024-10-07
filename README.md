# Generative AI Customer Relationship Management (CRM) Chatbot

**Overview**
Welcome to my Generative AI CRM chatbot project, designed as part of my data science portfolio. This chatbot is built to assist Revenue Services Lesotho (RSL) by answering frequently asked questions, enhancing customer interaction through AI-driven natural language processing. The chatbot uses GPT-2, fine-tuned with RSL's FAQ data, to generate responses.

The project not only demonstrates my ability to work with advanced machine learning models but also highlights my skills in full-stack development, as I have implemented the user interface using Django.

**Project Goals**
Create a Generative AI CRM system for RSL that can handle user inquiries efficiently.
Build an intuitive Django-based interface where users can interact with the chatbot.
Showcase my data science and machine learning expertise by fine-tuning GPT-2 to generate responses from the FAQ data.
Store, process, and evaluate large-scale language models to simulate a conversational agent for customer relationship management.

**Key Features**
GPT-2 Fine-Tuning: The GPT-2 model has been fine-tuned on RSL's frequently asked questions to provide contextually relevant responses.
Django Frontend: A clean and intuitive interface built with Django, where users can interact with the chatbot.
Error Handling: Input validation and basic error handling to ensure the chatbot remains functional, even with misspelled or incomplete user inputs.
Generative AI Expertise: This project demonstrates my understanding of natural language processing and generative models, which are crucial skills in the field of data science.


**Tech Stack**
Machine Learning Model: GPT-2 (fine-tuned)
Backend Framework: Django (Python)
Frontend: HTML, CSS, JavaScript (for chatbot interface)
Deployment: (Planned for deployment on Render/Heroku)
Model Training: TensorFlow and Hugging Face transformers library


**Installation**
**1. Clone Repository**
  git clone https://github.com/LeratoTheko/RSL-CRM-Chatbot.git
  cd generative-ai-crm-chatbot
**2. Install Dependencies**
  pip install -r requirements.txt
**3. Run Django Server**
  py manage.py runserver
**4. Training the GPT-2 model**: If you wish to train the model yourself, you can follow these steps in the GPT-2 Model Training section below.

**GPT-2 Model Training**
The chatbot is built using a fine-tuned GPT-2 model. Here’s how you can fine-tune the model:

**Prepare your dataset:** Format the FAQ data as question-answer pairs.
**Train the model:** Use the transformers library from Hugging Face and TensorFlow to fine-tune GPT-2. Refer to the Fine-Tuning Guide for detailed steps.
**Integrate the trained model:** After training, save the model and load it in the Django app for generating responses.
Usage
**Run the chatbot:** Once the server is running, navigate to http://localhost:8000/chatbot/ to interact with the CRM chatbot. Enter a question related to RSL, and the chatbot will generate a response based on the fine-tuned GPT-2 model.
Contribution
Feel free to contribute to this project by:

Adding new features or improving the interface.
Enhancing the AI model's capabilities by adding more diverse data or experimenting with newer architectures.
Providing suggestions to improve model accuracy or user experience.
Contact
If you have any questions or would like to discuss this project, feel free to reach out to me:

Email: thekothekolerato@gmail.com
Cell Number: +266 5761 2519
LinkedIn: Lerato Joseph

