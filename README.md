# AssistantAPItemplate
# OpenAI Assistant API Example

This Python script demonstrates how to use the OpenAI Assistant API to create a conversation with an AI assistant.

## Code Overview

The script performs the following steps:

1. Load environment variables from a .env file. The OpenAI API key is expected to be in this file.

2. Initialize the OpenAI client with the API key.

3. Get a prompt from the user to send to the assistant.

4. Create a new thread.

5. Add the user's prompt as a message to the thread.

6. Create a run to get the assistant's response.

7. Wait for the run to complete. The script continuously polls the API for the run status until it is "completed".

8. Retrieve all messages from the thread.

9. Print the assistant's response.

## Usage

1. Replace the `assistant_id` variable with your actual Assistant ID.

2. Run the script. When prompted, enter your prompt for the assistant.

3. The script will print the assistant's response.

## Requirements

- Python 3.6 or later
- openai Python package
- python-dotenv package
