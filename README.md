Ossome Hackathon - Github Community
trAIner
The trAIner is a collaboration website between AI and online fitness training. It might be the first of its kind application that accesses people's health requirements and issues on the basis of the information provided by the user, then curates a fitness regime in accordance the needs. Our AI technology trains the user, corrects one's exercise positions and postures and keeps a check on one's workout plans . Using our website anyone is assured to see improvements in oneself both bodily and mindfully.


# trAIner with Flask and JavaScript

In this tutorial we deploy the trAIner Website for localhost

This gives 2 deployment options:
- Deploy within Flask app
- Downloading the files and running on localhost, (it has some limitations for the chatbot feature).

## Initial Setup:


Clone repo and create a virtual environment
```
$ git clone [https://github.com/python-engineer/chatbot-deployment.git](https://github.com/ShivanshDengla/trAIner.git)
```
Install dependencies
```
$ pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
$ npm run dev-start

```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat_bot.py
```


## Watch the Demonstration Video
<img width="1428" alt="Screenshot 2023-09-15 at 5 31 37 PM" src="https://github.com/ShivanshDengla/trAIner/assets/66008449/8929f1ff-858c-4dc7-836f-2aa0898899cd">

[https://youtu.be/a37BL0stIuM]([https://youtu.be/a37BL0stIuM](https://www.youtube.com/watch?v=DEkWgMLNaX0))

## Note
In the video we give the demonstration of the project.

