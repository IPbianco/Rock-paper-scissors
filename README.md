# Rock, paper, scissors!

This app allows the user to play a game of Rock, paper, scissors against a sneaky bot called Zoe 5.1. 
You can check it out here: https://ipbianco-rps.herokuapp.com/

The application was built in one weekend using technologies like Ruby, HTML, CSS, Sinatra, RSpec and Capybara

## Getting started
```
$ git clone https://github.com/IPbianco/Rock-paper-scissors.git
$ bundle install
```
## Usage
```
$ rackup
```
Navigate to http://localhost:9292/
## Running tests
```
$ rspec
```
## User stories

```
As a user
So that I can see my name in lights
I would like to register my name before playing an online game

As a user
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```

Requirements:

- The user should be able to enter their name before the game
- The user will be presented the choices (rock, paper and scissors)
- The user can choose one option
- The bot (Zoe 5.1) will choose a random option
- A winner will be declared
