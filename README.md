<a href="https://www.linkedin.com/in/kristi-mita/"><img src="https://img.shields.io/badge/Kristi Mita-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"></a></br>

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![HTML](https://img.shields.io/badge/HTML-%2008000.svg?style=for-the-badge&logo=npm&logoColor=white)

# Add Interceptors to Browser FETCH API

By default **Fetch API** does not offer support for interceptors, but you can monkey patch it. Monkey patching is an approach that overrides the original functionality with your version of the function

```
const originalFetch = window.fetch;

window.fetch = function(url, options) {
    // Your code goes here...

    return originalFetch(url, options);
  };
```

Checkout the `index.html` file on how to add interceptors to Fetch API
