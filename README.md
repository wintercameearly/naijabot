# NaijaBot

## A Chatbot built using Flask, Chatterbot and AJAX

LIVE_DEMO : https://naijaaskbot.herokuapp.com/

### Naijabot loves pidgin and can answer simple questions about Nigeria

#### She requires specific questions e.g "Nigeria's Population?" to work properly, NLTK module isn't perfect.

#### Learning Resources; https://www.w3schools.com/jquery/jquery_ajax_load.asp ,https://studygyaan.com/python/create-web-based-chatbot-in-python-django-flask, 

### FLOW :

##### User calls the flask endpoint 
##### Sent message in the message box is sent to '/get' endpoint which calls a function on the trained natural langauge understanding module(chatterbot)

##### Chatterbot model returns a response

##### Jquery Ajax powers the request-response cycle so that there is no page reloading everytime the user sends a message or the bot returns a response

##### Ajax logic in script tags at the bottom of index.html
