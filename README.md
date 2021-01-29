### AMP

* AMP is a web component framework to easily create user-first websites.

* AMP is an open-source HTML framework that provides a straightforward way to create web pages that are fast, smooth-loading and prioritize the user-experience above all else. 

* Documentation - https://amp.dev/documentation/guides-and-tutorials/start/create/?format=websites

* Example:

```
<!DOCTYPE html>
<html ⚡>
  <head>
    <meta charset="utf-8" />
    <title>My AMP Page</title>
    <link rel="canonical" href="self.html" />
    <meta name="viewport" content="width=device-width" />
    <style amp-boilerplate>body{-webkit-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-moz-animation:-amp-start 8s steps(1,end) 0s 1 normal both;-ms-animation:-amp-start 8s steps(1,end) 0s 1 normal both;animation:-amp-start 8s steps(1,end) 0s 1 normal both}@-webkit-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-moz-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-ms-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@-o-keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}@keyframes -amp-start{from{visibility:hidden}to{visibility:visible}}</style><noscript><style amp-boilerplate>body{-webkit-animation:none;-moz-animation:none;-ms-animation:none;animation:none}</style></noscript>
    <script async src="https://cdn.ampproject.org/v0.js"></script>
    <style amp-custom>
      h1 {
        margin: 1rem;
      }
    </style>
  </head>
  <body>
    <h1>Hello AMPHTML World!</h1>
  </body>
</html>
```

![alt text](https://i.imgur.com/CM9eKOB.png)