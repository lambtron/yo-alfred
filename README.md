Yo! with Alfred
=========

## Setting up

1. You must have Alfred powerpack to use workflows. Buy the powerpack [here](https://buy.alfredapp.com/).

2. Register an application with Yo! [here](http://dev.justyo.co/).

3. Paste your Yo! app token in the Alfred workflow script, as such:

```
TOKEN={{YOUR_YO_TOKEN}}
curl --data "api_token=$TOKEN&username={query}" http://api.justyo.co/yo/
```

4. Yo! to your heart's content and to your friends' growing annoyances.

## How to use

Just type `yo! andyjiang` in your Alfred console.

Happy coding!