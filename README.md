# Live-News-Assistant--Auto-Mail
This project aims to create a GPT-4-1106-preview model that gathers real-time information on specific events worldwide by researching websites. The primary goal of the project is to collect current news on defined topics and send an email every morning at 8 AM.


The project's workflow is as follows:

Creating the News Assistant: Initially, specific rules are defined to create a news assistant.
Using OpenAI API: An assistant is created using the OpenAI API key. However, there is a limitation where the OpenAI API key restricts internet access.
Internet Access with Tavily API: To overcome this restriction, the Tavily API is used to gain internet access.
Query and Research: The assistant is asked a question related to a specific day or topic, which it then researches online via the Tavily API, gathering results.
Text Editing: The ChatGPT assistant evaluates, edits, and makes necessary additions or removals to the gathered text.
Daily Email Sending: Every morning at 8 AM, the results are sent via email. Access to Gmail is provided using a keyword and password for sending the email.
The project is entirely developed in Python and utilizes the OpenAI API, Tavily API, and Gmail API.
