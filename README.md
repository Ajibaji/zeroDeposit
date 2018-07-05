BRIEF
=====

A very basic vanilla JavaScript single page app that shows how many blocks of cheese ned can buy from france while still maintaining a UK sales price to his customers of £19.99. 

Security
---------
The entirety of this app is executed client-side and there is no backend. It makes 3rd party API calls for live(ish) forex data from https://openexchangerates.org/ . Naturally, the 3rd party provides an app ID. This case is no different. I chose not to conceal this app ID as it is only capable of making a single type of GET request (retrieviung exchange rates) AND concealing the ID would have meant creating a backend. Since the app performed its function to spec, I feel this is the MVP.

Installation
------------

Just download it and open it locally in a browser. Safari doesn't yet support ES6 and if you're still using internet explorer then you are here by mistake and you probably wanted to go to https://mail.yahoo.com





