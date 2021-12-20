# 🦊 | University Chatbot
> AI Chatbot
> 
> ![image](https://user-images.githubusercontent.com/42824659/146613666-228a236a-9e68-44d5-8f97-0ad81612bb6c.png)

## Highlights
1. This application based on `Rasa framework`
2. This chatbot gives responses to the student queries regarding University
3. It understands typos and grammatical mistakes and is still able to respond to the question
4. Conversing with this feels much more natural and human-like

## Let have a look how it works
https://user-images.githubusercontent.com/42824659/146637566-1ff03e9c-2de4-4052-b91c-63cb9fae2922.mp4

## Getting Started
Extend template or clone project using following command below:
```sh
git clone https://github.com/Kanu-Priya-Sehrawat/UniversityChatbot.git
```

Install required dependencies
In a Python3 virtual environment run:
```sh
pip install -r requirements.txt
```
To install development dependencies, run:
```sh
pip install -r requirements-dev.txt
pre-commit install
```
## Operating Commands
Use ``` rasa train ``` to train a model.

Then, to run, first set up your action server in one terminal window:
```sh
rasa run actions
```
In another window, run the duckling server (for entity extraction):
```sh
docker run -p 8000:8000 rasa/duckling
```
Then to talk to the bot, run:
```sh
rasa shell --debug
```
Note that --debug mode will produce a lot of output meant to help you understand how the bot is working under the hood. You can also add this flag to the action server command. To simply talk to the bot, you can remove this flag.
## Prerequsite
* Python virtual environment

## Version Information
Current Version: 1.0.0

## Authors
* **Kanu Priya** 

## Contributor(s)
 * Not Available

## Copyright
* **Kanu Priya**

## License
MIT
