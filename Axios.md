

1. We can make GET, POST, PUT, PATCH, DELETE Request.


## Installing this library
```shell

npm i axios



```

## GET
```js
import axios from 'axios';

const baseUrl = 'api.example.com' // api.staging.example.com

export async function getPost() {
  // it takes around 100 ms
  const result = await axios.get('/post', {
	baseUrl: baseUrl
  })
  return result 
}


```
