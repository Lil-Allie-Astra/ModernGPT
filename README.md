# ModernGPT
A ChatGPT chatbot with variable conversational awareness, and additional features.
Now with automatic retrying upon a failed API call, with a graduating delay between retries; if retry count reaches 5, it stops trying.

# Commands
Enter commands after the first ">" user prompt by typing ">>>" followed by an available command.
To find a list of available commands, type ">>>HELP" or ">>>?" at the non-initial ">" user prompts.
Typing ">>>HELP [any command]", or ">>>[any command]?" will list additional infomation about the command.

# !! IMPORTANT !!
You'll need to make a new environment variable named "OPENAI_API_KEY" to store your own OpenAI API key. This software does not come with an OpenAI API key.
