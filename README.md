#  Tweets App Server

Use it together with Tweets App

## Setup

Install the project dependencies:

`npm install`

## Running

Update config.json with your Twitter API credentials.
Start the static and proxy servers:

`npm start`

This server will help you to get Twitter's API to send you tweets without you needing to do any authentication.  You don't need to modify server.js at all. 

## Additional info

I modified Node `spawn` functions in `server.js` to run on Windows.
If You want to run server on Mac or Linux just get them back to:
`spawn('twitter-proxy');`
`spawn('http-server');`