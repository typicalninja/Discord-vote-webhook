# Halted

- The development of this project is halted.There is no eta on when i will resume the development of this project
- in the current state, the project is outdated and is not recomended for usage


## Discord vote webhook

#### Easy to use Vote Webhook handler for discord bot lists

---------------------------------

#### Requirements :

- Basic knowledge in javascript

- Node.js > v12

- Packages used :
 > 1. [express](https://www.npmjs.com/package/express)
 > 2. [discord.js](https://discord.js.org/#/)
 > 3. [chalk](https://www.npmjs.com/package/chalk)
 > 4. [node-fetch](https://www.npmjs.com/package/node-fetch)
 > 5. [querystring](https://www.npmjs.com/package/querystring)
 > 6. [raw-body](https://www.npmjs.com/package/raw-body)
 > 7. [consola](https://www.npmjs.com/package/consola)
 

------------------------------------


#### Config 

The config can be found in config.js

> A example of full config.js using `dotenv` for secret's
```
  "mode": "bot",
  "messageType": "embed",
  "webhook": {
         "botToken": process.env.TOKEN,
        "channelID": "776291354430930944",
        "serverID": "735024688224272395",
        "avatarURL": "{{user:avatar}}",
        "name": "{{user:name}}",
        "text": "New vote from {{user:mention}}"
  },
  "port": "3000",
  "embed": {
    "title": "",
    "description": "thanks {{user:name}} for voting for {{server}}",
    "footer": "Thanks for voting",
    "url": "https://top.gg/bot/715178668393103420/",
    "image": "",
    "color": ""

  }
```


#### Adding lists 


Adding a new list is easy

1. Go to lists.js
2. Add The list you need in to the lists(example below) 
  ex :- to add a bot lists called top.gg we will do 

   ```
   "top.gg": "kindofapassword",
   ```

   you can have the "top.gg" changed to whatever your like, basically it is

   ```
   "name": "password"
   ```

  where password is what you put as the authentication password in your botlists webhook page, and name of what ever of your liking

3. Go to https://localhost:3000/top.gg to see if your webhook path is alive


if everything is well you should see this

![alt text](https://raw.githubusercontent.com/typicalninja493/Discord-vote-webhook/master/images/expect1.png)


** Please change https://localhost:3000/top.gg to the url you use(ip or like that)

*** port can be changed in the config


#### on The edit page of your botlists webhook config

Make sure all the credntials are correct in your webhook edit page on your preffered botlist



### Issues:

Please report all the issue to https://github.com/typicalninja493/Discord-vote-webhook/issues

#### support

[Ninja lands](https://discord.gg/BtGVEREhPm)


##### Todo

```
❌ - Not yet started

✖️ - ongoing

✅ - Done
```


| Todo | Status |
| ----------- | ----------- |
| Handle errors nicely | ❌ |


#### Hosting/running

> Suggested Host

1. [repl.it](https://repl.it/)

Here a quick button for repl.it 

[![Run on Repl.it](https://repl.it/badge/github/typicalninja493/Discord-vote-webhook)](https://repl.it/github/typicalninja493/Discord-vote-webhook)
