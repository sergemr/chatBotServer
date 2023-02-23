# Connect OpenAI to Dialogflow CX

### Things you will need

- Dialogflow CX agent
  > some knowledge of Dialogflow CX as well
- OpenAI account and API Key
  > create an account [here](https://openai.com/)
- NGROK for exposing our local server to internet for testing

  > get it from [here](https://ngrok.com/)

  > start with ngrok http 5001

- Nodejs as a programing tool
  > install it from [here](https://nodejs.org/en/download/)

### How to use it

- install all the required packages in the project folder
  > use the command `npm install --save`
- create a `.env` file in the folder and set two variables `PORT` and `OPENAI_API_KEY`
- run the local server `npm run start`
- start NGROK engine
  > make sure the ports are same
- set the NGROK url in Webhook section
  > `YOUR NGRK URL/dialogflow` it should be something like this
- test the connection

# chatBotServer
