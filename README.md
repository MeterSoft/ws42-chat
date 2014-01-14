# Websocket Chat

This is a small app I made using another user's repo: https://github.com/themgt/ws42-chat which was itself mostly cribbed from a now defunct repo.

It is an interesting application. And though most of the business logic is written in coffee script, I am able to appreciate how powerful the asset pipeline is and websockets are using this small application.

I also integrated bootstrap-sass into this project.

# Please make sure to run the following command when deploying to Heroku, and you will get the output that follows:

```
$ heroku labs:enable websockets
Enabling websockets for <$your_app_name>
WARNING: This feature is experimental and may change or be removed without notice.
For more information see: https://devcenter.heroku.com/articles/heroku-labs-websockets```

This caused a lot of frustration until I realized you had to let the server sit for a few minutes to allow websockets. Then you have to force reload the page so it doesn't load from cache. Then it should work.