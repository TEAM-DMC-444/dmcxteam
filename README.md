## Print Something
```bash
from dmcxteam import p

p('YOUR TXT')
```
## Get Current Time
```bash
from dmcxteam import time

print(time())
```
## Generate Text Logo
```bash
from dmcxteam import makelogo

logo = makelogo(text='DMC')
print(logo)
```
## Random Numbers
```bash
from dmcxteam import random7, random8, random9, random1_2, random1_3, random1_4, random10

print(random7())
print(random8())
print(random9())
print(random1_2())
print(random1_3())
print(random1_4())
print(random10())
```
## System Commands
```bash
from dmcxteam import sysT

sysT('YOUR COMMAND')
```
## HTTP Requests
```bash
from dmcxteam import rqg, rqp

response_get = rqg('https://example.com')
response_post = rqp('https://example.com', data={'key': 'value'})
```
## Random Choices
```bash
from dmcxteam import rc

print(rc([1, 2, 3, 4]))

```
## Base64 Encoding/Decoding
```bash
from dmcxteam import bsec, bsdc

encoded_data = bsec('Hello, World!')
decoded_data = bsdc(encoded_data)
```
## Colors
```bash
# ---[coloure]------

RED = dmcxteam.RED

GREEN = dmcxteam.GREEN

YELLOW = dmcxteam.YELLOW

BLUE=dmcxteam.BLUE

ORANGE =dmcxteam.ORANGE

LI_BLUE = Light_BLUE

LI_MAGENTA = Light_MAGENTA

LI_CYAN = Light_CYAN

LI_WHITE = Light_WHITE

Background colors

BG_BLACK = Background_BLACK

BG_RED = Background_RED

BG_GREEN = Background_GREEN 

```
## get any Facebook id created date
```bash
from dmcxteam import getyearid

# Example: cid = '100000000023456'
print(getyearid(cid))
```
## html_req Function
The html_req function fetches HTML content from the specified URL, using optional headers and data for the request.
```bash
from dmcxteam import html_req

url = 'https://example.com'
headers = {
    'User-Agent': 'Your User Agent',
    'Accept': 'text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8',
    'Accept-Language': 'en-US,en;q=0.9',
    'Accept-Encoding': 'gzip, deflate, br',
    'Connection': 'keep-alive',
}
cookie = {'key': 'value'}  ## Optional Cookes for POST requests
data = {'key': 'value'}  ## Optional data for POST requests
params = {
    'q': 'params_valu',
    }
# you can add json--   json_data={"json" : "valu"}
parsed_html = html_req(url, Headers=headers, Data=data,Cookie=cookie,Params=params) ## data for POST requests 
parsed_html = html_req(url, Headers=headers,Cookie=cookie,Params=params) ##  for Get requests 
print(parsed_html)
```
### [Example of  html_4444 function](https://github.com/TEAM-DMC-444/dmcxteam/tree/main/html_444).


## html_444 Function
The html_444 function fetches HTML content from any request responce.
```bash
from dmcxteam import html_444
responce=requests.get('https://example.com').text
text_html = html_444(responce)
print(text_html)#get respone as html text
```
