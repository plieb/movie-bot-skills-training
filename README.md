[logo]: https://github.com/plieb/movie-bot-skills-training/blob/master/assets/logo.png "Movie Bot Skills Training"
![Movie Bot Skills Training][logo]

# Movie Bot Skills Training using Recast.AI

This is the backend for the skills for the Movie Bot Skills Training workshop

Follow the instructions below to create your own instance of the bot:

## Step 1: Clone the project & install ngrok

1. Git clone this project locally on your computer
1. Install [Ngrok](https://ngrok.com/)

## Step 2: Get your Recast.AI bot

1. Make sure you are logged in to your [Recast.AI account](https://recast.ai/)
1. Follow this link [Movie Bot Skills Training](https://recast.ai/pe/movie-bot-skills-training/train) and fork the bot to your account

## Step 3: Get your The Movie DB API key

1. Make sure you are logged in to your [The Movie DB account](https://www.themoviedb.org/login?language=en)
1. Follow this link [The Movie DB API](https://developers.themoviedb.org/3/getting-started) and follow the steps to get your API key
1. Setup your token for [The Movie Database](https://www.themoviedb.org/) either in `./config.js` or as environment variables : `MOVIEDB_TOKEN`.


## Step 4: Start your bot

1. Make sure your bot and ngrok are running on your computer on the port 5000 (You can also change the port of the API in `./config.js`)
1. Then you need to go to the settings of your bot on Recast.ai and change the field `Bot base URL` to the URL of your server with the https URL of ngrok.

To start the API after cloning the project:
```bash
npm install
npm start
```

To launch ngrok:
```bash
./ngrok http 5000
```

## Requirements

#### Node version

- v6.0 or higher required
- ngrok
- The Movie Database token

## Authors

Nathan Grasset [@Nathan_Grasset](https://twitter.com/Nathan_Grasset)

PE Lieb [@liebpe](https://twitter.com/liebpe)

You can follow us on Twitter at [@recastai](https://twitter.com/recastai) for updates and releases.

## Special thanks

- [The Movie DB API](https://developers.themoviedb.org)

## License

Copyright (c) [2017] [Recast.AI](https://recast.ai)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
