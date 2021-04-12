# twitAlert

In the current day and age, news and information often gets transmitted on social media at a much quicker pace than traditional news outlets. Thus, it is often the case that people can obtain news about potential emergencies much earlier if they are heavy twitter users. As I am not a regular twitter user, this project was borne out of a desire to eliminate the need for twitter usage while also obtaining information rapidly. This app will inform users in real time if any emergency situations have occurred in their vicinity through the use and analysis of tweets. Users will be able to see a list of relevant tweets in their area, a list of potential incidents that have occurred in their vicinity, and potential resources to help mitigate those emergencies. These incidents will be parsed by a natural language processing API to do both sentiment and content analysis. Eventually I hope to
#### 1. Give users the ability to customize their alerts to the types of incidents they are specifically concerned about
#### 2. Give users the ability to include major current events like the Capitol Riot.
#### 3. Use custom-made ML models in the backend to supply the analysis


#### Deployed App: []()
#### Server Repository: [https://github.com/muichc/twitAlert_server](https://github.com/muichc/twitAlert_server)
#### Client Repository: [https://github.com/muichc/twitAlert_client](https://github.com/muichc/twitAlert_client)


### Technologies Used
* MongoDB
* Flask
* Flask-PyMongo
* Node.js
* React.js
* React-Bootstrap
* SASS

### Installation Instructions for Frontend
#### 1. Install dependencies and start server
- `npm install`
- `npm start`

### Installation Instructions for Backend

#### 1. Set up virtual environment

- `python3 -m venv .venv`
- `source .venv/bin/activate`

#### 2. Install packages from requirements.txt
- `pip3 install -r requirements.txt`

### 3. Change to twitalertapp directory
- `flask run`

### Screenshots

![Landing Page]()
![Login]()
![DashBoard]()


### Wireframes

![Wireframe-Landing Page]()
![Wireframe-Login]()
![Wireframe-Dashboard]()

### ERD
![User model]()


### User Stories

* AAU, I want to be able to sign up and log in
* 

### Unresolved problems/ Major Hurdles

### Future developments