# GPT-4 Query

This script provides an interface to interact with the GPT-4 language model using the OpenAI API. You can have a conversation with the model by inputting messages and receiving responses.


## Todo
- [x] Basic retrying gpt_chat functionality for cli 
- [ ] Add stream=True option for more interactive conversations

## Prerequisites

- Python 3.x
- Required Python packages:
  - openai
  - retrying

## Getting Started

1. Install the required dependencies:

```shell
pip install openai retrying IPython
```

2. Set the OpenAI API key:
```shell
export OPENAI_API_KEY=your_api_key
```

Replace your_api_key with your actual OpenAI API key.

3. Run the script:
```shell
python gpt4_query.py
```

4. Start the conversation by entering your messages when prompted. Type "quit" to exit the program.

## Usage
The gpt4_query.py script allows you to have a conversation with the GPT-4 language model. You can input messages and receive model-generated responses.

Example usage:
```plaintext
You: Hello, how are you?
GPT-4: I'm an AI language model, so I don't have feelings, but I'm here to assist you. How can I help you today?
You: Can you tell me a joke?
GPT-4: Sure! Why don't scientists trust atoms? Because they make up everything!
```

Feel free to modify and customize the script according to your specific use case.




