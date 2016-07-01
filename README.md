# SiteMonitorPage
A simple Web Site monitoring page. ([See Demo](https://samejack.github.com/SiteMonitorPage))  

# Features
  - Simple JSON File Configuration
  - Responsive Web Design
  - Async check by AJAX

# Library
  - jQuery
  - AngularJS
  - Bootstrap

# JSON Configuration
Modify /config.json
```js
{
  "site": {
    "Chinese": [
      {
        "title": "GitHub",
        "url": "https://zh.wikipedia.org/wiki/GitHub"
      },
      {
        "title": "Wiki Padia",
        "url": "https://zh.wikipedia.org/wiki/Main_Page"
      },
      {
        "title": "Fail Site",
        "url": "https://gg.site.fail/"
      }
    ],
    "English": [
      {
        "title": "GitHub",
        "url": "https://en.wikipedia.org/wiki/GitHub"
      },
      {
        "title": "Wiki Padia",
        "url": "https://en.wikipedia.org/wiki/Main_Page"
      }
    ]
  },
  "timeout": 3000
}
```

# License
Apache 2.0 License
