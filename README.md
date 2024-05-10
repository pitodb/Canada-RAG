# Multi-Agent Information Retrieval System

## Overview
This project is a multi-agent application designed to retrieve information from various sources such as PDF files, CSV files, and allow users to write and save notes in a text file format. It utilizes a combination of tools and agents to assist users in obtaining specific information efficiently.

## Features
- **Information Retrieval from PDF**: Utilizes a PDF reader to extract information from PDF files.
- **Data Retrieval from CSV**: Parses data from CSV files containing population statistics.
- **Note Taking**: Allows users to write and save text-based notes into a text file.
- **Interactive Querying**: Users can interactively query the system using prompts to retrieve desired information.
- **Agent Assistance**: Uses agents powered by OpenAI's GPT-3.5 for natural language understanding and assistance in retrieving information.

## Components
1. **PDF Reader**: Reads PDF files to extract information.
2. **CSV Parser**: Parses CSV files containing population statistics.
3. **Note Saver**: Saves user-generated notes into a text file.
4. **Query Engine**: Utilizes Pandas for querying CSV data and OpenAI's GPT-3.5 for natural language processing.
5. **Agent**: ReActAgent handles interactions between users and the system, providing assistance and executing queries.

## Setup
1. Clone the repository.
2. Ensure Python and necessary dependencies are installed (`dotenv`, `pandas`, `llama_index`, etc.).
3. Create an `.env` file in the project root directory.
4. Add your OpenAI API key to the `.env` file in the following format:
   ```plaintext
   OPENAI_API_KEY=your-api-key-here
5. Run the application

## Usage

Interact with the system by entering prompts.
Query for specific information such as population statistics or details about a country.
Save notes using the provided tool
