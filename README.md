
# Vishnu Bot

- The brief idea of this project is to use the power of Telegram bots for the convenience of students at my institution


- The bot uses the following technologies

    - MongoDB Atlas as the backend for storing the student names.

    - [Nightmare](https://www.npmjs.com/package/nightmare) as the web automater, the usage here is to capture the screenshot from the ECAP website.

    - [Chuck Norris API](https://api.chucknorris.io) to fetch some nice  chuck norris's jokes for you to laugh.




## Run Locally

Clone the project

```bash
  git clone https://github.com/burpcat/vishnubot.git
```

Go to the project directory

```bash
  cd vishnubot
```

Install dependencies

```bash
  npm i nightmare
```

Start the server

```bash
  npm main.js
```

  
## Usage/Examples

- Start the bot using the following command
  ```bash
      /start
  ```
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/start.png"></p>

- Fetch the name of any student with the 19 series roll no at BVRIT
  ```bash
      /rollno 19211A0XXX
  ```
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/1.png"></p>

  - Fetch the attendance from [ECAP](https://www.bvrit.edu.in) through the following command
  ```bash
      /attendance 19211A0XXX;password
  ```
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/2.png"></p>

  - This is the screenshot sent to the Telegram app
 
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/3.png"></p>

  - Get the bot to show you a random Chuck Norris's joke
  ```bash
      /joke
  ```
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/4.png"></p>

  - The bot says byee!
  ```bash
      # Anything with the word bye inside it
  ```
  <p align="left"><img width=25% src="https://github.com/burpcat/vishnubot/blob/master/Sources/5.png"></p>



## Feedback

If you have any feedback, please reach out to us at [Mail](codekurama@gmail.com) or on my [Linkedin](https://www.linkedin.com/in/avinasharutla/)

  