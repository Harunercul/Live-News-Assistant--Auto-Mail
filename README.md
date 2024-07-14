<p>Tabii, işte İngilizce açıklama:</p>
<hr>
<p><strong>Project Name:</strong> Live News Assistant</p>
<p><strong>Description:</strong>
This project aims to create a GPT-4-1106-preview model that gathers real-time information on specific events worldwide by researching websites. The primary goal of the project is to collect current news on defined topics and send an email every morning at 8 AM.</p>
<p>The project&#39;s workflow is as follows:</p>
<ol>
<li><strong>Creating the News Assistant:</strong> Initially, specific rules are defined to create a news assistant.</li>
<li><strong>Using OpenAI API:</strong> An assistant is created using the OpenAI API key. However, there is a limitation where the OpenAI API key restricts internet access.</li>
<li><strong>Internet Access with Tavily API:</strong> To overcome this restriction, the Tavily API is used to gain internet access.</li>
<li><strong>Query and Research:</strong> The assistant is asked a question related to a specific day or topic, which it then researches online via the Tavily API, gathering results.</li>
<li><strong>Text Editing:</strong> The ChatGPT assistant evaluates, edits, and makes necessary additions or removals to the gathered text.</li>
<li><strong>Daily Email Sending:</strong> Every morning at 8 AM, the results are sent via email. Access to Gmail is provided using a keyword and password for sending the email.</li>
</ol>
<p>The project is entirely developed in Python and utilizes the OpenAI API, Tavily API, and Gmail API.</p>
<hr>
<p>You can add this description to your project&#39;s GitHub page.</p>
