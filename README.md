# FAQ Chatbot

This FAQ Chatbot is designed to provide automated responses to frequently asked questions. The chatbot is built using Python and can handle basic conversational interactions such as greeting the user, responding to "thank you", and ending the conversation when the user says "bye".

## Features

- **Interactive Chat**: Engage in a conversational manner with the chatbot.
- **Polite Responses**: The chatbot responds politely when the user says "thank you".
- **Exit Conversation**: The chatbot ends the conversation gracefully when the user says "bye".
- **FAQ Handling**: The chatbot can respond to predefined frequently asked questions.

## Prerequisites

- Python 3.x: Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).

## Setup

1. **Clone the Repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Install Dependencies**:
   There are no additional dependencies for this simple chatbot. Ensure your Python environment is set up correctly.

## Usage

1. **Run the Chatbot**:
    ```sh
    python chatbotforfaqs.py
    ```

2. **Start a Conversation**:
   - The chatbot will greet you and prompt you to ask a question.
   - Type your question and press Enter to receive a response.

3. **Special Commands**:
   - Type 'bye' to end the conversation.
   - Type 'thank you' to receive a polite response from the chatbot.

## File Overview

- `chatbotforfaqs.py`: The main script containing the chatbot logic.

## Example Interaction

Here are some frequently asked questions:
- What is the starting price of the Rezvani Vengeance?
- What engine options are available for the Rezvani Vengeance?
- What are the key safety features of the Rezvani Vengeance?
- Does the Rezvani Vengeance offer customization options?
- What is the seating capacity of the Rezvani Vengeance?
- What kind of warranty is provided with the Rezvani Vengeance?
- Can the Rezvani Vengeance be used for off-road driving?
- What are the dimensions of the Rezvani Vengeance?
- How do I order a Rezvani Vengeance?
- Where is the Rezvani Vengeance manufactured?
- What is the fuel efficiency of the Rezvani Vengeance?
- What are the available color options for the Rezvani Vengeance?
- Is the Rezvani Vengeance available internationally?
- What technology features are included in the Rezvani Vengeance?
- What is the top speed of the Rezvani Vengeance?
- How long does it take to manufacture a Rezvani Vengeance?
- Can I test drive the Rezvani Vengeance before purchasing?





 Hello! I am an FAQ Chatbot. Ask me anything from the FAQs.
Type 'bye' to end the conversation.

You: What is the starting price of the Rezvani Vengeance?
Bot: The starting price of the Rezvani Vengeance is approximately $285,000. However, the final price may vary depending on customizations and additional features.
You: What is the top speed of the Rezvani Vengeance?
Bot: The top speed of the Rezvani Vengeance is approximately 155 miles per hour, depending on the engine configuration.
You: price
Bot: I'm sorry, you can only ask questions about the FAQs provided.
You: bye
Goodbye! 
 < Thank You For Using Me >

 

## Implementation Details

### Functions

- **display_faqs()**:
  - Displays a list of frequently asked questions.
  - Modify this function to include actual FAQs and their answers.

- **chatbot_response(user_input)**:
  - Generates a response based on user input.
  - Replace the placeholder implementation with actual response logic.

- **chat_with_bot()**:
  - Main function to handle the conversation loop.
  - Prompts the user for input, processes commands, and generates responses.

### Control Flow

- The chatbot starts by displaying a welcome message and FAQs.
- Enters a loop to continuously prompt the user for input.
- Handles special commands ('bye' to end the conversation and 'thank you' for a polite response).
- Generates responses using the `chatbot_response` function.
