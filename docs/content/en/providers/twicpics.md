---
title: Twicpics Provider
description: ''
position: 14
category: Providers
---

Integration between [Twicpics](https://www.twicpics.com) and the image module.  
To use this provider you just need to specify the base url of your project in Twicpics.

```js{}[nuxt.config.js]
export default {
  image: {
    twicpics: {
      baseURL: 'https://nuxt-demo.twic.pics'
    }
  }
}
```
