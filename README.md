# AI chat bot

An AI chatbot that utilizes natural language processing and neural networks is a software program that can understand natural language queries and provide human-like responses. Natural language processing allows the chatbot to understand the intent and meaning behind a user's message, and neural networks enable it to learn and improve over time by analyzing large amounts of data.

The frontend of this chatbot is designed to be easily customizable and adaptable to a variety of use cases. Whether you want to create a customer service chatbot for your business, a personal assistant to help with daily tasks, or a chatbot to provide information and support for a specific topic, the frontend can be tailored to meet your specific needs.



![crypto](https://github.com/vavinash992/AI-chat-bot/blob/main/static/Screenshot%20from%202023-05-06%2009-18-50.png)
## Packages used

- Flask==2.1.2
- keras==2.11.0
- nltk==3.8.1
- numpy==1.22.3





## Setup

- To deploy this project run

```bash
  $ pip install -r /path/to/requirements.txt
```
- Than run the app.py 
```bash
  $ python3 app.py
```
- A link will appear on the command line copy it and paste it in the browser

    by default it runs in the following website http://127.0.0.1:5000/


## Training the model on new questions

- Go to data.json file and question in patterns and the response, than assign it a tag and context.

- Than run the Training.py file using the following command

```bash
    $ python3 Training.py
```
