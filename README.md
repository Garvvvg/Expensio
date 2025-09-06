## Introduction:
The core concept of our project revolves around creating a comprehensive finance
application aimed at providing users with deep insights into their financial behaviors and patterns. Users will be able to add & enter their expenses either in a text format, audio format or within a form. It will also generate a summary based on user's expenditure and show interactive visualization based on user's expenditure patterns.
  
## Table of Contents:
Here are the key features that our application will offer:
* Users can track their expenses.
* Generate a summary of their expenses.
* Leveraging cutting-edge NLP and Deep Learning techniques, the application will
delve into understanding the user's relationship with money on a deeper level.
* Users will have liberty to enter their expense in text format, audio format or within a form.
* To facilitate better understanding and decision-making, the application will offer
dynamic visualizations of expenditure patterns.

## Technology Stack:
  1) NLP & Deep Learning
  2) Node.js
  3) React.js
  4) Flask
  5) MongoDB
  
## How to run our app on your machine.
* Clone the repository
* Start these one by one in the terminal.
* NLP model: go to newNlpModels folder and type commands: pip install -r requirements.txt, then python app2.py
* backend: go to server folder, command: npm install > npm run dev
* frontend: go to client folder, command: npm install --force > npm start
* and then you can visit the website at the react specified url.
ALERT:: there is a .env file in server folder of the form

## .env file config
* PORT=5000
* MONGO_URI=
* GOOGLE_CLIENT_ID=
* GOOGLE_CLIENT_SECRET=
* JWT_SECRET=
* OPENAI_API_KEY=
* DEEPGRAM_API_KEY=
