# Langflow-RAG-Powertrain-software-requirement

## Overview

This project implements a Retrieval-Augmented Generation (RAG) agent using Langflow, designed to assist with powertrain software updates for automotive systems. The agent is capable of analyzing code files and answering questions related to specific requirements for powertrain software updates. By leveraging natural language processing and document parsing, the agent provides accurate and context-aware responses based on the content of the uploaded files.
Intended use case:
- For example, given a software requirement, the Agent can analyze through the code files and give specific inforomation on which code file to modify to meet the software requirements
 

## Prerequisites

1. Python 3.8 or higher
2. Langflow framework
3. Git (for cloning the repository)
4. Access to Google Generative AI API (API key required)

Usage

1. Upload Files: Load your powertrain software code files (e.g., combined_c_files.pdf) into the agent via the "File" node in the Langflow interface.
2. Parse Data: The "Parse Data" node will convert the file content into a text format for processing.
3. Input Query: Use the "Chat Input" node to enter questions such as "What is the update process for the powertrain software?" or "Are there any bugs in the current code?"
4. Get Response: The agent will process the query using the "Google Generative AI" node and display the answer in the "Chat Output" node.
5. Customize Settings: Adjust the temperature (e.g., 0.18) or max output tokens in the "Language Model" node for desired response behavior.

Example:
![image](https://github.com/user-attachments/assets/a23c8b58-41e1-420e-8177-3bca2ceecf6f)
