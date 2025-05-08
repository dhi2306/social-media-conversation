# social-media-conversation
OpenAI API Integration: The script utilizes the openai Python library to interact with OpenAI's GPT-3.5-turbo model. This model is designed for conversational tasks, making it ideal for chat applications.

Environment Configuration: The API key is securely handled using environment variables, ensuring that sensitive information is not hardcoded into the script.

Conversation History Management: A list named messages is used to store the conversation history. This list includes both user inputs and assistant responses, which are sent to the API to maintain context.

Dynamic Interaction: The script enters a loop where it continuously prompts the user for input, sends the conversation history to the API, and displays the assistant's response. The conversation continues until the user types 'exit'.
