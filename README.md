# Rotate-Proxy

Rotate proxies using Python and Requests!!

Add Rotate.py to the working directory of any webscraper or Python script you are wanting to mask your IP Address from the server you are making a single or multiple requests to. Then import into your scraper with:

`from Rotate import *`

# How to Use

``` proxy = Random_Proxy()

url = 'https://www.youtube.com'
request_type = "get"

r = proxy.Proxy_Request(url=url, request_type=request_type)
print(r) ```
