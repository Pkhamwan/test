# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": pdH87qlP3GJ+YjzwLm6tH6IV4E6xIJAH/BdVB7+Ob4SxDjisSl1kErwNeIWMFsBSLRDp/H5vaLGXboanLBBZW70FOGB/Lc86G3rDgB90tHsUl2rjUFtCR/lPJQoTWpLG/Y0hFalt/7cbURq4aq5SrAdB04t89/1O/w1cDnyilFU=,
  "channelSecret": 2910abfc8f92b765f601324d1b08da6a
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
