# GenAI-CustomerService
A generative AI-powered solution to enhance customer service for Bank of Baroda, providing personalized, efficient, and proactive support across multiple channels.

## Table of Contents 
 
- [Introduction](#introduction)
- [Workflow](#Workflow)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup](#setup)
- [Usage](#usage)
- [Future Work](#future-work)

## Introduction

This project aims to enhance the customer service experience for Bank of Baroda by leveraging generative AI technologies. Our solution automates customer inquiries, provides accurate real-time responses, offers personalized recommendations based on customer data, and integrates seamlessly with existing customer service platforms while maintaining high security and data privacy standards.

## Workflow 

1. **Architecture Design**: Develop a chatbot using RAG (Retriever and Generator) with an SQL database and API integration for Bank of Baroda.
2. **SQL Database**: Store structured data like customer info, transaction history, FAQs, and product details.
3. **Retriever Module**: Implement efficient SQL queries to fetch relevant information from the database.
4. **Generator Module**: Fine-tune a language model (e.g., GPT) to generate coherent responses based on retrieved data.
5. **API Integration**: Interface with external systems to provide real-time banking information and other services.
6. **User Interface**: Design a user-friendly front-end (web or mobile) to interact with the chatbot, send queries, and display responses.
7. **Overview**:This streamlined approach covers the essential components of your project.

## Features

- **Automated Customer Support**: Real-time response generation to customer inquiries.
- **Personalized Recommendations**: Tailored solutions based on customer data and interaction history.
- **Multi-Channel Integration**: Seamless integration with various customer service platforms.
- **Data Privacy and Security**: Ensures the highest level of security and data privacy.

## Tech Stack

- **Backend**: Python, Flask (or FastAPI)
- **Frontend**: Steamlit
- **AI Model**: Gemini pro vision
- **Database**: SQL
- **Vector Database**:Pinecone

## Setup


1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/GenAI-CustomerService.git
    cd GenAI-CustomerService/backend
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up OpenAI API key:
    ```sh
    export OPENAI_API_KEY='your-api-key'  # On Windows use `set OPENAI_API_KEY=your-api-key`
    ```

## Usage

1. Ensure both backend and frontend servers are running.
2. Open your browser and navigate to `http://localhost:3000`.
3. Interact with the chatbot to receive automated customer support and personalized recommendations.

## Future Work

- **Expand Data Integration**: Incorporate more customer data for better personalization.
- **Enhance Security**: Implement advanced security measures for data privacy.
- **Multi-Channel Support**: Extend support to other customer service channels (e.g., voice, social media).
- **Scalability**: Optimize the system for handling a larger volume of inquiries.
- **Chatbot**: Interact with the chatbot to receive automated customer support and personalized recommendations.

## Team Members

- [Sree Vamsi](https://github.com/sreevamsi2005)
- [Madhav](https://github.com/Madhav1303)
- [Jagadeesh](https://github.com/JagadeeshRallabandi)
- [Ayush](https://github.com/AyushSonuu)

