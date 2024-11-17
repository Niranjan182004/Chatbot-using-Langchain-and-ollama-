# Chatbot-using-Langchain-and-ollama-
This project demonstrates the integration of Langchain with the Llama2 API for a simple question-answering application using Streamlit. The application allows users to input queries through a text input box, which are then processed by the Llama2 model to generate helpful, accurate responses in real time.

**Project Overview:**
1) Streamlit is used for building the web interface, where users can input their queries or topics.
2) Langchain is utilized to chain together components such as prompts, models, and output parsers, making it easy to integrate language models into Python applications.
3) Llama2 is the language model (provided via Ollama) that processes the user’s input and returns relevant responses.
4) Environment Setup: The project loads environment variables securely using dotenv to manage API keys and configurations.
   
**Features:**
1) Interactive Input Box: Users can type in any topic or question in a text input box, which is captured dynamically.
2) Query Processing: The entered text is passed to the Llama2 language model, which generates a response based on the user's input.
3) Real-Time Results: The response is immediately displayed in the Streamlit app, creating a seamless user experience.
4) Modular Design: The project is structured using Langchain's modular components (prompts, models, and parsers) for easy customization and scalability.
