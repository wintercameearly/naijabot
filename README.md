NaijaBot
<br/>
A Chatbot built using Flask, Chatterbot and AJAX
<br/>
Naijabot loves pidgin and can answer simple questions about Nigeria
<br/>
She requires specific questions e.g "Nigeria's Population?" to work properly, NLTK module isn't perfect.
<br/>
Learning Resources; https://www.w3schools.com/jquery/jquery_ajax_load.asp ,
<br/>https://studygyaan.com/python/create-web-based-chatbot-in-python-django-flask, 
<br/>
FLOW :
User calls the flask endpoint 
Sent message in the message box is sent to '/get' endpoint which calls a function on the trained natural langauge understanding module(chatterbot)
<br/>
Chatterbot model returns a response
<br/>
Jquery Ajax powers the request-response cycle so that there is no page reloading everytime the user sends a message or the bot returns a response
<br/>
Ajax logic in script tags at the bottom of index.html
