# Car chat Bot
Car chatbot built with: Node, Express and IBM Watson AI.

## How the app works
The app interface is designed and trained for chatting with a cognitive car. The chat interface is on the left, and the
JSON that the JavaScript code receives from the server is on the right. Your questions and commands are run against a small set of sample data trained with intents like these:

    turn_on
    weather
    capabilities

These intents help the system to understand variations of questions and commands that you might submit.

Example commands that can be executed by the Conversation service are: 

    turn on windshield wipers
    play music

## Before you begin
1 Ensure that you have a [Bluemix account](https://console.ng.bluemix.net/registration/).

2 Ensure that you have the necessary space available in your Bluemix account. This action deploys 1 application and 1 service.

   * You can view this on your Bluemix Dashboard. Tiles will show what space you have available.
   * For example, for Services & APIS

Setup:

1. Log into IBM Bluemix and create new conversation service- creates a new workspace.
2. Create new service credentials to download and setup information.
3. Download the usernames and passwords and into .env files
4. Extract from workspace details workspace id and add into .env files.
5. To connect to workspace hit npm start which will connect to the local files to Watson.
