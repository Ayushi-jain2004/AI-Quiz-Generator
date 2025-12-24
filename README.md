# AI-Quiz-Generator
A robust, full-stack AI implementation designed to automate the pedagogical workflow of quiz creation. This application bridges the gap between raw information and structured learning by leveraging Large Language Models (LLMs) to generate contextually accurate Multiple Choice Questions (MCQs).

The application follows a client-server synthesis model, where the frontend (Streamlit) handles state and user input, while the backend logic (Python) manages the orchestration of data to the OpenAI API.

# Technical Implementation

* Interface Layer: Developed with Streamlit, providing a reactive, state-driven user experience for real-time quiz interaction.

*Orchestration & Logic: Written in Python, managing the communication between the UI and the AI backend, including data cleaning and response parsing.

*AI Integration: Powered by the OpenAI API (GPT-4o). The system utilizes structured prompt engineering to ensure the AI returns consistent, valid, and challenging questions.

*Security & Configuration: Implemented python-dotenv to manage sensitive API credentials through environment variables, following industry best practices for security.

# Features

*Automated Content Synthesis: Automatically identifies key concepts from user input to generate relevant questions.

*Stateful User Experience: Uses Python logic to track user scores and provide immediate feedback on answer selection.

*Robust Error Handling: Designed to manage API interactions and ensure the application remains stable during data transmission.
