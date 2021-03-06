# twitAlert

In the current day and age, news and information often gets transmitted on social media at a much quicker pace than traditional news outlets. Thus, it is often the case that people can obtain news about potential emergencies much earlier if they are heavy twitter users. As I am not a regular twitter user, this project was borne out of a desire to eliminate the need for twitter usage while also obtaining information rapidly. This app will inform users in real time if any emergency situations have occurred in their vicinity through the use and analysis of tweets. Users will be able to see a list of relevant tweets in their area, a list of potential incidents that have occurred in their vicinity, and potential resources to help mitigate those emergencies. These incidents will be parsed by a natural language processing API to do both sentiment and content analysis. Eventually I hope to: 
1. Give users the ability to customize their alerts to the types of incidents they are specifically concerned about
2. Give users the ability to include major current events like the Capitol Riot.
3. Use custom-made ML models in the backend to supply the analysis


#### Deployed App: []()
#### Server Repository: [https://github.com/muichc/twitAlert_server](https://github.com/muichc/twitAlert_server)
#### Client Repository: [https://github.com/muichc/twitAlert_client](https://github.com/muichc/twitAlert_client)


### Technologies Used
* MongoDB
* Flask
* Flask-PyMongo
* Node.js
* React.js
* Panda
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

![Landing Page](./screenshots/landing.png)
![DashBoard](./screenshots/dashboard.png)


### Wireframes

![Wireframe-Landing Page](./wireframes/landing-wireframe.png)
![Wireframe-Login](./wireframes/login-wireframe.png)
![Wireframe-Dashboard](./wireframes/dashboard-wireframe.png)

### ERD
![User model](./dataModels/user-model.png)


### User Stories

* AAU, I want to be able to sign up and log in
* AAU I would like to be able to sign up for an account and log in.
* AAU I would like to be able to set my current location.
* AAU I would like to see a list of tweets in my vicinity that I might be concerned about.


### Unresolved problems/ Major Hurdles
There were relatively few resources for learning Flask and authentication with Flask and it took me a while to piece together from various resources the overall structure and workflow for a Flask app. As a result, I was unfortunately unable to get to a lot of the features I had intended to include. I did not manage to implement an alert for potential emergencies, and I was not able to display tweets obtained from my server directly on my front end. The tweets that are displayed are currently hard-coded in, and the logic for filtering the tweets is rudimentary. Currently the logic is simply based upon a simple sentiment analysis, and any tweets with a negative sentiment is automatically included. 

### Future developments
* Fix display of live tweets
* Implement alert system
* Improve logic behind alerts and filter tweets better
* Load live stream of tweets
* Include resources for disasters
* Responsive design