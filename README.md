# Black Lives Matter Ward Emailer
The City of Chicago (my hometown) is split up into 50 Wards each run by an Alderman. This Alderman represents the ward on the City Council.
If you want local change where you live, your alderman is the person to contact. To make this easy, put in your Ward and this site generates an email in your default Mail application on your device, prepoulated with your name and the necessary details. All you need to do is press send. Make sure your voice is heard!

## Current Deployment
The site is currently live at [here](http://email-your-alderman.surge.sh/). It is a slightly less complex version, just emailing one alderwoman criticizing her her most recent city budget vote. The original site would allow the user to email any alderman and include the mayor, however, it wouldn't make sense to criticize all of the aldermen. 
Deployed using [surge](https://surge.sh/)

## Run
- clone this repo
- `yarn install`
- `yarn start`
You will have a local version on your computer

## API 
This uses the Chicago Ward API.
[Here](https://data.cityofchicago.org/resource/htai-wnw4.json) you can find the raw JSON format of all of the data on all of the Wards.
To query a specific Ward:
`https://data.cityofchicago.org/resource/htai-wnw4.json?ward={WARD}`

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
