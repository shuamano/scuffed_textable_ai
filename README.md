# Textable AI
## replies to google voice text messages with ai generated replies, allowing sms converstations with ai models. has some bloat, and unfinished sections for generating images.
* scrapes inbox for text notifs from gvoice
* uses gpt4all for some models
* uses the free huggingface inference api for the default model(llama 3.2 3b instruct)
* creates context windows for each user

Issues:
* unfinished sections for generating images
* when the context window reaches max length, it ends/crashes the script
* mail.noop() socket errors
