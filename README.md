# Instatags

Instatags is a tool that generates random tags for your profile picture, photos and post[DCP '21]

## Open Source Programs 
<img src="https://github.com/Ayush7614/Instatags/blob/master/devincept.gif" alt="DevIncept" />

[![Instatags](https://img.shields.io/badge/Instatags-dodgerblue.svg?style=flat&logo=instagram&logoColor=white)](https://github.com/Ayush7614/Instatags) [![Google Vision](https://img.shields.io/badge/Vision-API-critical.svg?style=flat&logo=google&logoColor=white)](https://cloud.google.com/vision/docs/quickstart) [![Imgur API](https://img.shields.io/badge/Imgur-API-critical.svg?style=flat&logo=highly&logoColor=white)](https://api.imgur.com/)


### APIs Used

- [Google Vision API](https://cloud.google.com/vision/docs/quickstart) - Google Cloud’s Vision API offers powerful pre-trained machine learning models through REST and RPC APIs.

- [Imgur API](https://api.imgur.com/) - Imgur's API exposes the entire Imgur infrastructure via a standardized programmatic interface. Using Imgur's API, you can do just about anything you can do on imgur.com, while using your programming language of choice.

### Getting Started

- Get your own imgur clientID [here](https://api.imgur.com/endpoints/image).
- Replace `XXXXXXXXX` with your clientID in `js/upload.js`.

```javascript
new Imgur({ 
    clientid: 'XXXXXXXXX', // replace this 
    callback: feedback 
});
```
- Get API keys for [Google Cloud Vision API](https://cloud.google.com/vision/docs/quickstart).

- Replace `XXXXXXXX` with your API keys in `js/upload.js`
```javascript

var settings = {
      "async": true,
      "crossDomain": true,
      // change the key below
      "url": "https://vision.googleapis.com/v1/images:annotate?key=XXXXXXXXXXXXXXXXXXX",
      "method": "POST",
      "headers": {
        "Content-Type": "application/json",
        "cache-control": "no-cache"
      },
      "processData": false,
      "data": str
    }

```

- Now open `index.html`
