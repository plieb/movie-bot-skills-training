# skills

This is the backend for two different skills you can add to your bot on [Recast.ai](http://recast.ai/).

To start the API after cloning the project:
```bash
npm install
npm start
```
Since this API relies on external services, you can setup your tokens for [Open Weather Map](https://openweathermap.org/api) and [The Movie Database](https://www.themoviedb.org/) either in `./config.js` or as environment variables : `OPENWEATHER_TOKEN` and `MOVIEDB_TOKEN`.

You can also change the port of the API in `./config.js` (it listens on port `5000` by default)

Then you need to go to the settings of your bot on Recast.ai and change the field `Bot base URL` to the URL of your server.

[Ngrok](https://ngrok.com/) could come in handy if you just want to try out the API without having to host this code on a public server :)

## Requirements

#### Node version

v6.0 or higher required
