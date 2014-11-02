Yo! with Alfred
=========

## Setting up

1. You must have Alfred powerpack to use workflows. Buy the powerpack [here](https://buy.alfredapp.com/).

2. Click [here](https://raw.github.com/lambtron/yo-alfred/master/yo-alfred.alfredworkflow) to download the workflow.

3. Double click on the file to add it to Alfred.

_Optional, if you want to change the sender name from YOALFRED._

4a. Register an application with Yo! [here](http://dev.justyo.co/) with an app name of your choosing. Note this app name will be what the recipient sees.

4b. Paste your Yo! app token in the Alfred workflow script, as such:

```
TOKEN={{YOUR_YO_TOKEN}}
curl --data "api_token=$TOKEN&username={query}" http://api.justyo.co/yo/
```

__You are set!__ Yo! to your heart's content and to your friends' growing annoyances.

## How to use

Just type `yo! andyjiang` in your Alfred console.

Happy coding! Direct all hate tweets @andyjiang.