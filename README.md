Here's an enhanced and polished version of your README:

# GROQ-Based Movie Agent

## Overview
This project showcases an intelligent Movie Agent powered by the Groq LLM (Large Language Model). Our agent seamlessly connects with the OMDB API and Wikipedia API to fetch and analyze comprehensive information about movies.

## Key Features
- Real-time interaction with multiple APIs
- Intelligent decision-making for API selection
- Dynamic parameter generation for API calls
- Advanced result analysis and synthesis
- Iterative information gathering when needed

## How It Works
Our agentic pipeline operates in real-time, following these steps:

1. **Request Analysis**: The agent interprets the user's query to determine the most appropriate API to utilize.

2. **Parameter Generation**: Based on the query, the agent dynamically generates the necessary parameters for the API call.

3. **API Interaction**: The selected API is called with the generated parameters.

4. **Result Processing**: The agent analyzes the data received from the API.

5. **Response Generation**: The agent either provides a comprehensive answer to the user or initiates additional API calls if more information is required.

## Technologies Used
- Groq LLM: Powers the core intelligence of our agent
- OMDB API: Provides detailed movie information
- Wikipedia API: Offers broader context and additional details
- Custom API integration tools: Enable seamless communication between the LLM and external APIs

## Test on Streamlit
You can see this movie agent in action on Streamlit [here](https://priya-dwivedi-movie-agent.streamlit.app)

## Getting Started
To run this on your own, follow these steps:
1. Git clone the repo
2. Add your OMDB API Key and Groq API key to the envtt file
3. Run the streamlit agent:
   ``` streamlit run chatbot.py```

To learn more about the code behind this, watch my youtube video explaining the basics of the agent and the code [here](https://youtu.be/qDnUNYsO_ig)

