# Negotiator-Chatbot
This project is a Python-based negotiation chatbot that simulates price negotiations between a customer and a supplier. It leverages pre-trained AI models like OpenAI's GPT and VADER sentiment analysis to create dynamic, natural conversations around price negotiations. The chatbot can interact with users, accept offers, propose counteroffers, and finalize deals based on predefined pricing logic.

Features:
Price Negotiation: The chatbot initiates negotiations for a product priced at $100, allowing users to offer their desired price.
Counteroffers: The chatbot proposes counteroffers if the user’s offer is within a negotiable range (between $80 and $100).
Sentiment Analysis: The chatbot uses sentiment analysis to assess the user's tone (politeness) and adjust its counteroffer accordingly.
Deal Finalization: The chatbot can recognize when the user agrees to a deal by typing responses like "deal" or "accept."
Input Handling: It accepts both numeric offers and non-numeric inputs like "accept" or "deal" to conclude the negotiation.

Technologies:
Python: Core programming language.
OpenAI GPT API: For generating dynamic conversational responses (integrated for future AI-based conversational flow).
VADER Sentiment Analysis: To evaluate the sentiment of user input and adjust negotiation outcomes.
NLP: Handles natural language processing to understand user input and respond appropriately.

How It Works:
The chatbot starts by offering a product at a base price of $100.
The user can submit price offers or accept/reject the current offer.
If the user offers a price within the acceptable range, the bot counteroffers based on preset rules.
The conversation continues until a deal is reached or the bot rejects the offer for being too low.

Installation:
Clone the repository.
Install required dependencies: pip install -r requirements.txt
Set up your OpenAI API key for chatbot integration.
Run the negotiation_bot.py script to start the chatbot.


