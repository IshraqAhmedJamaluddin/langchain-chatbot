# langchain-chatbot

A small project using langChain

It takes maintains a conversation with the user using the terminal.
![List of Messages start with a System Message, then a sequence of User, Assistant Messages exchanged](architecture.png)
![Terminology mapping from OpenAI roles to LangChain roles](terminologyMapping.png)

## Setup and Running

add a `.env` file to your base directory that includes your `OPENAI_API_KEY` e.g:

```
OPENAI_API_KEY=[YOUR KEY HERE]
```

to run just type `python main.py`
