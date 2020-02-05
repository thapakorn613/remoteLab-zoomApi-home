# API for create zoom_id and open zoomApp on desktop windows

>

## Getting Started

### Install

Clone the repo using git clone.
` git clone https://github.com/thapakorn613/remoteLab-zoomApi.git`

Install the dependent node modules.

1. ` npm install

2. ` npm install windows-edge

### Config

 In the config.js file, input your client API Key & Secret credentials.
``` 
	const config = {
	production:{	
		APIKey : 'Your environment API Key',
		APISecret : 'Your environment API Secret'
	}
    };
```
> Start the node app.
Type node index.js

> Enter your email and view the API's response.

After you submit an email address, Zoom API call and you will be redirected to localhost:3000/userinfo page that displays the API response

### Run Project 
-> open cmd
-> "node index.js"



