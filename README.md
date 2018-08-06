# Fragrance Bot

### Description
This is the final project on the Project Management course that I did with my team (three members). The project is about building a Chatbot that using Microsoft Bot Framework integrates with LUIS service and Azure Search Service, this bot can detect user intents and help them search for fragrance products and suggest fragrances depend on information that is collected from the user.    

### Usage
The bot can handdle some situations below:
- If user say some greetings to the bot, it will say greeting again and ask for user what they want to search(type, gender, smell,...) for fragrances. The user need to provide key words for the bot to search and follow the instructions from the bot. 
- If user send a sentence with the intent to search for fragrance products, for example I want to buy male fragrances, the bot will detect that and start searching for products if in that sentence have some key words about fragrances (like male, female, sweet,...), if not it will ask the user some information to suggest some fragrance brands. 
- If the bot does not understand what the user's intent, it will say sorry.... and then ask the user some information to suggest some fragrance brands. 
