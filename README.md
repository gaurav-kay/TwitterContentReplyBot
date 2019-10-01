# Twitter Content Reply Bot

## Hacktoberfest

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) on how to contribute to this project.

## How to run the code with mock data
```
python twitter.py
```
This will start an endless loop that check user tweets every minute, and replies if there are any match from [content.json](content.json).

## Running the bot on your own Twitter account

- Apply for a Twitter developer account [here](https://developer.twitter.com/en/apply-for-access)
- This will give you access to your own API keys and access tokens.
- Now, change the file called `config.py` inside the working directory and fill it in

```
API_key = "YOUR OWN API KEY"
API_secret_key = "YOUR OWN API SECRET KEY"
Access_token = "YOUR OWN ACCESS TOKEN"
Access_token_secret = "YOUR OWN SECRET ACCESS TOKEN"
```

Also remember to set

```
DEBUG = false
```

in [twitter.py](twitter.py).
