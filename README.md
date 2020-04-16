# django-proxy

## Dead simple Django proxy for making API requests.

Sometimes developers are faced with blocking various websites for political 
reasons. For such purposes, I made a dead simple application for making API 
requests to blocked resources, such as [telegram](http://telegram.org) in Russia.

Everything you need to configure your own API proxy app is to click on this 
button and make same simple configuration.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## How to use

After you finish deployment just make a request, for example in python it 
looks something like this

```python
import requests

base_url = "https://appname.herokuapp.com/"
api_url = "https://api.website.com/"

response = requests.get(f"{base_url}{api_url}")
```

or use Postman

[![Run in Postman](https://run.pstmn.io/button.svg)](https://www.postman.com/)

## Happy coding ❤️
