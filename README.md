# Chatbot_DialogFlow_practice

A Facebook Messanger chatbot to call API from Youtube based on Google DialogFlow deployed on Firebase

Author: davislf2

Practice from the [tutorial](https://www.youtube.com/watch?v=FuKPQJoHJ_g)

### Prerequisit

Node.js



### Instruction

```sh
npm install -g firebase-tools
firebase login
firebase init
```

functions

firebase deploy

https://medium.com/google-developer-experts/deploy-your-app-to-firebase-in-seconds-b3a9a37dff47

Dialogflow
1.Intents
Fulfillment
Enable webhook call for this intent

2.Fulfillment
Inline Editor: Enabled

npm install request --save

Youtube API key
https://developers.google.com/youtube/v3/getting-started

Create Credentials
API Key
AIzaSyBpRekaKNAR8SadgvqpAkSEXPq3mMWIHQo

Enable YouTube Data API v3
https://console.developers.google.com/apis/library/youtube.googleapis.com?project=dialogflow-watchvideo

Test this on browser

https://www.googleapis.com/youtube/v3/search?part=snippet&safeSearch=strict&maxResults=5&videoSyndicated=true&videoEmbeddable=true&q=howCode&type=video&key=AIzaSyBpRekaKNAR8SadgvqpAkSEXPq3mMWIHQo



GCP

https://console.cloud.google.com/getting-started

1. Select project
2. API & Services => Dashboard
3. Youtube => Enable
4. Credentials => Create API keys
5. Copy and paste the API key to index.js
6. Put index.js into folder /functions
7. ​

```sh
firebase deploy
```



Facebook create a fan page

https://www.facebook.com/Cognitive-Agent-955656154632059/?modal=admin_todo_tour&ref=admin_to_do_step_controller



Facebook create a new app ID

https://developers.facebook.com/apps/

1. Create a new App
2. Messanger
3. Settings
4. Select a fan page
5. DialogFlow => Integration => Facebook Messenger
6. Webhooks => select "messages"
7. Select a page



Callback URL: https://bots.dialogflow.com/facebook/866c558f-e47e-46af-a6a4-ed1b5a79acbe/webhook

Verify token: sdlfjoiroaifwekvlawejaoiwevjaOSIJFklsdfEOIF

Page access token: 

EAADRpgDG4tsBAM4HnMDIfNatZAvNEF316jBR56mvtNODZCQir6GIgdtdxR2uOPZAPJJwyQXWdk38oim4rsigopkr52pRPqjVr1echl4mzdZBEC2AHn6jZC2y5OEBfP1tbZAkct6p9KW8KektFADiUUZCRC54EeMuxGnZAXOZAZBlviEyB8tIuaIGsQwqxpTx2XfGne0V5x25VJZBAZDZD

(From Graph API Explorer)

如何不寫程式取得 Facebook 粉絲專頁永久 Access Token？

http://goodjack.blogspot.com/2017/08/how-to-get-facebook-permanent-page-access-token.html



Firebase

Modify => Plan: Spark to Blaze (pay as you go + extend project to GCP)



```sh
firebase use --add
# Choose a project
# Give an alias e.g. agent
firebase deploy
```



https://console.developers.google.com/apis/api/youtube.googleapis.com/overview?project=dialogflow-watchvideo&duration=PT1H