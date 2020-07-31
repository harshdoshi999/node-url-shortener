
#About
node-url-shortener help you to shorten your big URLs. Currently we support only is.gd because it does not need any kind of API key. You can shorten number of URLs without any limit without using any API keys.

Note: From 29th July, 2020 - We are trying to integrate another platform to balance load. You don't have to worry at all as there won't be any code change required and your previous URLs will keep working as it is. We'll keep you posted on further news.

# Installation

Install via NPM

```js

npm install node-url-shortener --save

```

# Example

```js

var shortUrl = require('node-url-shortener');

shortUrl.short('https://google.com', function(err, url){
    console.log(url);
});

```
